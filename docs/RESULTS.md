# Plot gallery

Pre-rendered outputs from the Fair Tontine Toolbox notebooks. Highlight plots also appear on the [README](../README.md).

## Mortality inputs

Empirical SSA period life table (qx) vs. the Gompertz model from the paper, linear scale:

![Mortality rate, linear scale](plots/mortality-rate-linear.png)

Same comparison on a log scale:

![Mortality rate, log scale](plots/mortality-rate-log.png)

Mortality tables as Python lists (`MALE_QX`, `FEMALE_QX`):

![Mortality tables as Python lists](plots/mortality-tables-python-lists.png)

## Annuity baseline

Survival-weighted present value of a $1 payout, ages 60–100, r = 0% (fair annual payout ≈ $0.046):

![Actuarial PV of a $1 perpetuity](plots/actuarial-pv-1-dollar-perpetuity.png)

Annuity-pool Monte Carlo: surviving population and pool balance with ±3σ bands:

![Annuity pool Monte Carlo](plots/annuity-pool-monte-carlo.png)

1σ of end balance vs start/end age (N = 500, r = 0%):

<img src="plots/annuity-volatility-surface.png" alt="Annuity volatility surface" width="700">

## Mixed-cohort tontine (20,000 members)

50- and 60-year-old cohorts sharing one pool. Mean discounted cumulative payouts ±1σ:

![20,000-member mixed cohort, cumulative payouts](plots/mixed-cohort-50-60yo-20000-cumulative-payouts.png)

Mean shares outstanding and payout rate d(t):

![20,000-member mixed cohort, shares outstanding](plots/mixed-cohort-50-60yo-20000-shares-outstanding.png)

Conditional annual payout while alive ±1σ:

![20,000-member mixed cohort, conditional payout](plots/mixed-cohort-50-60yo-20000-conditional-payout.png)

## Pool-size comparison

Larger pools compress payout volatility. Each size shows the same three views: discounted cumulative payouts, shares outstanding + d(t), and conditional annual payout while alive.

### Homogeneous 60-year-old cohort

**100 members**

![100-member 60yo cohort, cumulative payouts](plots/cohort-60yo-100-cumulative-payouts.png)

![100-member 60yo cohort, shares outstanding](plots/cohort-60yo-100-shares-outstanding.png)

![100-member 60yo cohort, conditional payout](plots/cohort-60yo-100-conditional-payout.png)

**1,000 members**

![1,000-member 60yo cohort, cumulative payouts](plots/cohort-60yo-1000-cumulative-payouts.png)

![1,000-member 60yo cohort, shares outstanding](plots/cohort-60yo-1000-shares-outstanding.png)

![1,000-member 60yo cohort, conditional payout](plots/cohort-60yo-1000-conditional-payout.png)

**10,000 members**

![10,000-member 60yo cohort, cumulative payouts](plots/cohort-60yo-10000-cumulative-payouts.png)

![10,000-member 60yo cohort, shares outstanding](plots/cohort-60yo-10000-shares-outstanding.png)

![10,000-member 60yo cohort, conditional payout](plots/cohort-60yo-10000-conditional-payout.png)

### Mixed 50- and 60-year-old cohorts

**200 members**

![200-member mixed cohort, cumulative payouts](plots/mixed-cohort-50-60yo-200-cumulative-payouts.png)

![200-member mixed cohort, shares outstanding](plots/mixed-cohort-50-60yo-200-shares-outstanding.png)

![200-member mixed cohort, conditional payout](plots/mixed-cohort-50-60yo-200-conditional-payout.png)

**2,000 members**

![2,000-member mixed cohort, cumulative payouts](plots/mixed-cohort-50-60yo-2000-cumulative-payouts.png)

![2,000-member mixed cohort, shares outstanding](plots/mixed-cohort-50-60yo-2000-shares-outstanding.png)

![2,000-member mixed cohort, conditional payout](plots/mixed-cohort-50-60yo-2000-conditional-payout.png)

**20,000 members** (same three charts as in the section above)

![20,000-member mixed cohort, cumulative payouts](plots/mixed-cohort-50-60yo-20000-cumulative-payouts.png)

![20,000-member mixed cohort, shares outstanding](plots/mixed-cohort-50-60yo-20000-shares-outstanding.png)

![20,000-member mixed cohort, conditional payout](plots/mixed-cohort-50-60yo-20000-conditional-payout.png)

## Outlier / π analysis

Participation rate (π) for a single outlier vs. an age-60 cohort, by cohort size and outlier age:

<img src="plots/pi-rates-outlier-vs-60yo.png" alt="Pi rates, outlier vs 60-year-old cohort" width="700">

Participation rate for a 75-year-old outlier vs. a homogeneous age-65 cohort, by cohort size and outlier investment:

<img src="plots/cohort-size-vs-outlier-investment-pi.png" alt="Cohort size vs outlier investment, pi" width="700">
