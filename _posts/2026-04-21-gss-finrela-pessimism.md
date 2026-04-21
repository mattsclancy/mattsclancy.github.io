---
layout: post
title: "Feeling Below Average at the Median"
subtitle: "GSS finrela responses by HH-equivalised income band, 1972–2024"
date: 2026-04-21
categories: [data, economics, wellbeing]
---

Among Americans right at the middle of the household income distribution, the share reporting that their family income is "below average" or "far below average" has roughly doubled since the early 1970s — from around 15% to around 30%. Most of this increase occurred after 2000. Among Americans in the upper half of the income distribution, the same share has been essentially flat across five decades, holding between 8 and 11%.

The chart below shows both trends. The GSS `finrela` question asks respondents to place their family income relative to American families in general, on a scale from "far below average" to "far above average." Respondents are divided into two bands each year based on their HH-equivalised household income: those in the 45th–55th percentile (the median band, in blue) and those above the 55th percentile (in orange).

![Share feeling below average on finrela by HH-equivalised income band, 1972–2024](/assets/images/finrela_percentile_bands.png)

*Share of respondents reporting "below average" or "far below average" on finrela, by HH-equivalised income band. The median band (blue) covers the 45th–55th percentile of equivalised household income within each survey year; the above-median band (orange) covers the 55th–100th percentile. Lines are 5-year centred rolling averages; faint dots show raw annual values.*

The above-median group (orange) is broadly stable across the entire period, oscillating between roughly 8% and 11% with no net trend. The median band (blue) is different: it starts around 15% in the early 1970s, spikes during the 1982 recession to around 30%, partially recovers through the 1990s to roughly 20%, then rises again starting around 2008 and remains elevated through the most recent waves. By the late 2010s and 2020s, the smoothed series for the median band sits near 30%.

## Data

`finrela` is a five-category GSS variable recording self-assessed financial standing relative to other American families. Household income is `coninc`, which gives constant-dollar income derived from categorical brackets, equivalised for household size using `hompop` and the OECD square-root scale (`coninc / sqrt(hompop)`). Survey weights use `wtssps`.

## Reproducing this analysis

The full code is in the [gss-finrela-pessimism](https://github.com/mattsclancy/gss-finrela-pessimism) repository.

### Data

The GSS data is not included in the repository. Download your own extract from [GSS Data Explorer](https://gssdataexplorer.norc.org/) with these variables:

| Variable  | Description |
|-----------|-------------|
| `finrela` | Opinion of family income relative to others (5 categories) |
| `coninc`  | Family income in constant dollars |
| `hompop`  | Number of people in household |
| `wtssps`  | Post-stratification survey weight |

Save the file as `data/GSS.xlsx` in the project root. Note that `wtssps` must be added explicitly — it is not included in GSS extracts by default.

### Dependencies

```
pip install pandas openpyxl matplotlib
```

Python 3.9+.

### Generating the chart

```
python3 gss_finrela_pessimism.py
```

Output is saved to `output/finrela_percentile_bands.png`.

---

*Related: [Have our expectations outpaced economic growth?](https://mattsclancy.github.io/2026/04/12/happiness-is-reality-minus-expectations.html) uses the same GSS data to estimate the income level at which people begin to report financial dissatisfaction, and finds a similar post-2008 divergence from median income.*

*Data: General Social Survey, NORC at the University of Chicago, 1972–2024. Income adjusted to constant dollars and equivalised for household size (OECD square-root scale). Survey weights (wtssps) applied throughout.*
