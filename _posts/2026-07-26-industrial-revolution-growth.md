---
layout: post
title: "Is the Industrial Revolution an Existence Proof for 10× AI Growth?"
subtitle: "Historical growth rates from the Maddison Project Database suggest it is not"
date: 2026-07-26
categories: [data, economics, growth]
---

Some AI optimists cite the Industrial Revolution as a precedent for rapid accelerations in growth, since the UK managed roughly 17 times faster compound growth after the IR than before. But I think this framing is misleading.

Imagine living in Britain around 1700, on the eve of the Industrial Revolution. Annual GDP per capita growth had averaged around 0.3% for the past several centuries — but your experience was not of slow, steady progress. Harvest failures, wars, and disease sent annual growth swinging by 10 percentage points or more in either direction. A year of 3% growth — ten times the historical average — was not at all unusual: about one year in three already exceeded that threshold. If someone had told you that growth was about to permanently accelerate tenfold, the new rate would have been something you had already lived through many times. It would have felt, year to year, like a run of good harvests.

Compare this to claims that AI might accelerate contemporary growth to 10x its normal speed. Such a claim is different in kind. Global GDP per capita has grown at around 2% per year in the modern era, with far lower year-to-year volatility than pre-IR Britain. A 10× acceleration from today's baseline would mean 20% annual growth — a rate that falls 7 standard deviations above the modern distribution and has never been sustained by any country in the postwar record. That is not growth into familiar territory.

## Data

All estimates use the [Maddison Project Database 2023](https://www.rug.nl/ggdc/historicaldevelopment/maddison/releases/maddison-project-database-2023), which reports GDP per capita in 2011 USD and population in thousands. The pre-IR UK window is 1252–1652 (400 years before the IR began); the settled post-IR baseline uses 1850–1913 (after the transition period but before WWI). The modern cross-country panel covers 1950–2022.

When assessing how much precedent there is for dramatically faster growth in the contemporary period, this post uses data for all countries in the database rather than the UK alone. This is the most favorable framing for finding precedents: many developing countries have experienced rapid growth episodes, and including them provides the widest possible search for precedents for 10× accelerations (including examples of rapid technological upgrading of the economy). If we restricted to the US or other high-income countries, the evidence against 10× growth would be even stronger — no wealthy country has come close.

## Annual distributions: pre-IR UK and modern analogues

One critique of using historical UK data is that year-to-year GDP estimates for the thirteenth through seventeenth centuries are too unreliable to draw conclusions from. To address this, I identify contemporary countries that approximately match pre-IR UK on three dimensions: GDP per capita between \$800 and \$2,500 (2011 USD), population between 1 million and 20 million, and average annual growth between −0.5% and 2%. Twenty-three countries qualify — mostly in Sub-Saharan Africa — for whom we have reliable modern data.

[![Annual growth distributions: pre-IR UK and modern analogues](/assets/images/growth_accel_fig1.png)](/assets/images/growth_accel_fig1.png)

*Left: annual GDP per capita growth for the UK, 1252–1652 (mean 0.30%/yr). Right: annual GDP per capita growth for 23 modern analogue countries, 1960–2022 (mean 0.90%/yr). The dashed red line in each panel marks 10× that distribution's mean.*

For pre-IR UK, a 10× acceleration above the average means growth above about 3%/yr — a threshold crossed by 30% of years. For modern analogues, the mean is higher at 0.90%/yr, so a 10× acceleration implies growth above about 9%/yr, cleared by only 4.6% of country-years.

The contrast between the two panels is itself worth pausing on. The pre-IR UK figure of 30% is far higher than the 4.6% seen in modern economies with similar profiles. Part of this gap almost certainly reflects measurement noise in centuries-old GDP estimates: errors in the historical series may inflate apparent volatility, which mechanically inflates the share of years crossing any given threshold. The modern analogue data may be a more reliable guide. They show that 10× years are uncommon in economies like pre-IR UK — roughly 1 in 20 — but not unprecedented.

The broader postwar dataset further supports the idea that 10× years were genuinely common in slow-growing economies, not just an artifact of noisy pre-IR data — and confirms that this is a feature of slow-growing economies specifically, not of economies in general. The chart below bins all 143 countries by their 1950–1985 baseline growth rate and shows what share of each group had at least one year between 1986 and 2022 in which growth exceeded 10× that baseline.

[![Share of countries with at least one 10× growth year, by baseline growth rate](/assets/images/growth_accel_fig1b.png)](/assets/images/growth_accel_fig1b.png)

*Each bar shows the share of countries in that baseline-growth bin (1950–1985) that had at least one year of growth exceeding 10× their baseline average during 1986–2022. n gives the number of countries in each bin.*

Among the slowest-growing economies — those averaging 0–1%/yr in the baseline period, the same range as the modern analogues — 94% experienced at least one 10× year. That share falls to 22% for countries averaging 1–2%/yr, and to essentially zero above 2%/yr. The non-zero values in higher bins involve a small number of countries — 7 in the 1–2% bin and 5 across the two faster bins — and on inspection every single one is a post-conflict rebound or a resource shock: Rwanda and Sierra Leone recovering from civil wars, Nigeria and Venezuela from oil-price swings, Equatorial Guinea from an oil discovery, Iraq and Lebanon from invasions and civil conflict, and Bosnia and Libya from near-total economic collapse. These are cases of GDP returning to a prior level, not economies accelerating beyond their historical trajectory. The main takeaway is that a 10× year is a relatively routine feature of very slow-growth economies and essentially absent from fast-growing ones. Since modern global growth averages around 2%/yr, a 10× acceleration to 20%/yr sits well outside the range where such events have ever occurred.

## The Industrial Revolution shock in standard deviations

Annual data are noisy. A cleaner way to measure the IR shock is to smooth out year-to-year variation using 20-year compound growth rates, then express the shock in terms of the standard deviation of the pre-IR distribution.

[![SD framing: pre-IR UK 20-year distribution and modern 20-year distribution](/assets/images/growth_accel_fig2.png)](/assets/images/growth_accel_fig2.png)

*Left: distribution of pre-IR UK 20-year compound annual growth rates, 1272–1652 (mean 0.06%/yr, SD 0.63 pp). The dashed red line marks the post-IR settled rate of 1.02%/yr. Right: distribution of modern 20-year compound growth rates across all countries, 1980–2022 (mean 2.01%/yr, SD 2.49 pp). The dashed orange line marks the IR-equivalent threshold (5.8%/yr); the dashed red line marks 10× the modern compound rate (20.1%/yr).*

The pre-IR UK 20-year compound growth rate averaged 0.06%/yr with a standard deviation of 0.63 pp. The settled post-IR rate of 1.02%/yr lies 1.52 standard deviations above the pre-IR mean — about 7.3% of pre-IR 20-year windows exceeded it (the shaded right tail in the left panel).

Applying the same 1.52-SD shift to the modern distribution yields a threshold of 5.8%/yr. That is uncommon — only about 5% of modern country-years have achieved a 20-year compound growth rate above 5.8% — but it is not without precedent. The 10× benchmark of 20.1%/yr, by contrast, is 7.2 standard deviations above the modern mean. No country in the modern dataset has ever achieved that.

## 20-year compound growth: pre-IR UK and the modern world

Smoothing over 20-year rolling windows removes the year-to-year noise and shows the underlying trend rates directly.

[![20-year rolling compound growth histograms](/assets/images/growth_accel_fig3.png)](/assets/images/growth_accel_fig3.png)

*Left: distribution of 20-year annualised compound growth rates for the UK, 1272–1652. Right: distribution of 20-year compound growth rates across all countries, 1980–2022. The dashed red lines mark the relevant threshold in each panel (post-IR UK rate on the left; 10× the modern mean on the right).*

The left panel shows the pre-IR UK compound growth distribution clustered tightly around zero, with 7.3% of windows exceeding the post-IR baseline. The right panel shows the modern distribution centered near 2%/yr, concentrated well below 10%/yr. The 10× benchmark of 20.1%/yr falls entirely off the right edge of the modern distribution; 0.00% of modern 20-year country-windows have exceeded it.

## Postwar precedents for 10× accelerations

The charts above look at long-run compound growth. We can also ask a more lenient question: has any country ever experienced a run of years in which growth dramatically exceeded its own prior baseline — the pattern we would expect to see in the early stages of an AI-driven takeoff?

To measure this cleanly, I split the postwar data into two halves: a baseline period (1950–1985) and an acceleration test period (1986–2022). For each country, I compute the average annual growth rate during the baseline period, then find what fraction of years in the acceleration period saw growth exceed 10× that baseline average. Countries whose baseline growth was zero or negative are excluded.

[![Scatter: first-half baseline growth vs share of second-half 10× years](/assets/images/growth_accel_fig4.png)](/assets/images/growth_accel_fig4.png)

*Each point is one of the 27 countries (out of 143 with sufficient data in both halves) that had at least one year in 1986–2022 exceeding 10× their 1950–1985 baseline average. The x-axis is the 1950–1985 baseline average; the y-axis (log scale) is the share of 1986–2022 years exceeding 10× that baseline. Countries with zero such years are not shown; their median baseline growth was 2.84%/yr, versus 0.81%/yr for countries shown. Faster-growing countries have a higher baseline, making a 10× year harder to achieve.*

Twenty-seven of 143 countries had at least one such year. They cluster sharply toward the left — countries with very slow baseline growth. The countries with the highest shares of 10× acceleration years are those with the weakest baseline track records; their extreme years typically reflect post-conflict recovery or one-time resource windfalls rather than sustained technological transformation. The 116 countries with zero 10× years in the post-1985 data had nearly four times higher median baseline growth (2.84%/yr vs. 0.81%/yr). The pattern is consistent: the same feature that makes a 10× threshold easy to cross in a low-baseline country — having a very low denominator — makes it essentially unreachable for countries that are already growing at modern rates.

## Reproducing this analysis

The full code and data are in the [growth-acceleration](https://github.com/mattsclancy/growth-acceleration) repository.

### Data

| File | Source |
|------|--------|
| `mpd2023_web.xlsx` | Maddison Project Database 2023, sheet "Full data" |

### Dependencies

```
pip install pandas numpy matplotlib scipy openpyxl
```

Python 3.9+.

### Generating the charts

```
python3 analysis.py
```

Output is saved to `output/`.
