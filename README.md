# Fair Tontine Toolbox

Jupyter notebooks for equitable mixed-cohort retirement tontines: participation-rate (π) solvers, outlier analysis, annuity comparisons, and mortality visualization.

**Disclaimer:** This project is for research and educational purposes only. It is not financial, investment, or actuarial advice.

## Requirements

- Python 3.10+
- Dependencies: `pip install -r requirements.txt`

## How to run

Open Jupyter from the project root (imports assume the working directory is the repo root):

```bash
jupyter notebook
```

Suggested order:

1. `TontineToolboxQXVisualizer.ipynb` — optional; sanity-check mortality tables
2. `TontineToolboxMain.ipynb` — core π solvers and pool simulation
3. `TontineToolboxOutlierMath.ipynb` — optional; replicate Milevsky & Salisbury outlier curves
4. `TontineToolboxAnnuity.ipynb` — optional; fair annuity payout and pool volatility

## References

### Mortality data

U.S. Social Security Administration, Period Life Table 4C6 (2021 period, as used in the 2024 Trustees Report).  
https://www.ssa.gov/oact/STATS/table4c6.html

### Academic sources

This repository implements and extends the framework in:

> Milevsky, M. A., & Salisbury, T. S. (2016). *Equitable Retirement Income Tontines: Mixing Cohorts Without Discriminating.* ASTIN Bulletin, 46(3), 571–604.  
> [Cambridge](https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/equitable-retirement-income-tontines-mixing-cohorts-without-discriminating/3174FE869098E8E47A738CC1C2E06A86) · [SSRN](https://ssrn.com/abstract=2700362)

Related (natural tontine / Gompertz parameters used in the QX visualizer):

> Milevsky, M. A., & Salisbury, T. S. (2015). *Optimal Retirement Income Tontines.* Insurance: Mathematics and Economics, 64, 91–105.

This project is **not affiliated with or endorsed by** the authors.

## License

MIT License — see [LICENSE](LICENSE). Mortality data is U.S. government data; cite SSA as the source when redistributing.
