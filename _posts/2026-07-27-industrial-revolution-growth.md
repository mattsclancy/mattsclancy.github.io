---
layout: post
title: "Is the Industrial Revolution an Existence Proof for 10× AI Growth?"
subtitle: "Historical growth rates from the Maddison Project Database suggest it is not"
date: 2026-07-27
categories: [data, economics, growth]
---

One line of evidence that AI might lead to explosive economic growth is the precedent set by the Industrial Revolution. For hundreds of years — 1252 to 1652, to be precise — the average annual growth rate of per capita real GDP in the UK was 0.30%. It then began to accelerate, settling into a new steady state of around 1.05% per year by 1850, which it held until 1913. In other words, growth accelerated by roughly 15 times before, in compound terms; the argument goes that this should make us humble about predicting it can't happen again, and perhaps we should be open to accelerations of 10 times or more.

I think this argument is overstated and the analogy between a 10× acceleration today and the acceleration that occurred during the Industrial Revolution is misleading. The goal of the first part of this post is to provide evidence for two claims:

1. At the outset of the Industrial Revolution, annual growth that was 10× the long-run average was relatively common.
2. In the contemporary world, annual growth that is 10× the long-run average for the world is much more rare.

The second part of this post characterizes the acceleration that occurred during the Industrial Revolution in terms of the standard deviation of year-to-year variation in growth rates. Applying the same approach to contemporary growth suggests that an IR-style acceleration would take growth in frontier economies to around 2.8% per year — meaningfully faster than today, but well below the 10× claim that is often advanced.

Why go through this exercise? A common reaction to claims that AI will lead to annual growth rates in excess of 20% per year is skepticism and incredulity — it would be so far outside historical experience. A common retort is that the same incredulity would have been wrong in the 1700s: had someone been told that future growth would be 10× the average and dismissed it, they would have made an error.

The goal here is to rescue that initial reaction. A 10x acceleration today is not the same thing as a 10x acceleration in 1700. A person living in the 1700s would have been asked to envision good years becoming much more common — a rate they had already experienced many times. A person today is being asked to envision a qualitatively different kind of economic dynamics, one that falls several standard deviations outside norm for the world today.

All estimates use the [Maddison Project Database 2023](https://www.rug.nl/ggdc/historicaldevelopment/maddison/releases/maddison-project-database-2023), which reports GDP per capita in 2011 USD and population in thousands.

## How common was 10× faster growth in the pre-IR UK?

We will start by establishing that it was quite common for growth to exceed 10× the long-run average in the UK prior to the Industrial Revolution. Over 1252–1652, the long-run average was 0.30% per year. The compound growth rate over this period — the rate at which wealth actually accumulated across generations — was around 0.07% per year. Roughly 10× this compound rate — around 0.66% per year — was exceeded in about 46% of years. (This figure is not sensitive to the exact window chosen: the compound growth rate ranges from 0.07% to 0.18% across plausible alternative start and end years, and the share of years exceeding 10× that rate ranges from about 40% to 50%.)

[![UK annual GDP per capita growth, 1252–1652](/assets/images/growth_accel2_fig1.png)](/assets/images/growth_accel2_fig1.png)

*Distribution of annual GDP per capita growth for the UK, 1252–1652. The dashed red line marks 10× the compound growth rate (0.66%/yr). About 46% of years exceeded this threshold.*

Economic statistics from hundreds of years in the past, before we had statistical offices, are of course highly unreliable, and so the rest of this section will try to provide alternative evidence that 10× faster growth was probably reasonably common. First, to eliminate the importance of year-to-year fluctuations, we can focus on 20-year compound average growth rates. The mean compound rate across all 20-year windows is 0.06% per year, consistent with the full-period CAGR of 0.07%, so 10× that is a threshold of around 0.6%. About 17% of 20-year windows exceeded it. If this data is to be believed, it implies that generation-long runs of 10× faster growth were not unheard of.

[![UK 20-year compound annual growth, 1272–1652](/assets/images/growth_accel2_fig2.png)](/assets/images/growth_accel2_fig2.png)

*Distribution of 20-year compound annual GDP per capita growth rates for the UK, 1272–1652. The dashed red line marks 10× the long-run average (0.60%/yr). About 17% of 20-year periods exceeded this threshold.*

Our second robustness check is to look for similar patterns over 1960–2022 for countries with characteristics similar to the pre-IR UK. We are assuming that the growth dynamics of this set of contemporary countries is a reasonable analogue for the growth dynamics of the pre-IR UK — and hoping that the data for these modern countries is more reliable than reconstructions of pre-IR UK real GDP per capita.

We identify this set of countries based on GDP per capita, population, and long-run average growth rate. In the Maddison data, pre-IR UK real GDP per capita ranged from $995 to $2,056 (2011 USD), and population data available for 1500 and 1600 shows a range of 3.9 to 6.2 million, with growth averaging 0.30% per year. We identify countries with real GDP per capita between $800 and $2,500, population between 1 million and 10 million, and average growth between −0.3% and 0.9%. Eight countries satisfy these conditions: Benin, Burundi, Chad, Haiti, Senegal, Sierra Leone, Togo, and Zimbabwe. Their average compound growth rate is 0.35%/yr, and 10× that — around 3.5% per year — was exceeded in about 19% of country-years. This again suggests it was likely the case in the pre-IR UK that annual growth rates exceeding 10× the average were relatively common.

[![Annual GDP per capita growth, modern analogues](/assets/images/growth_accel2_fig3.png)](/assets/images/growth_accel2_fig3.png)

*Distribution of annual GDP per capita growth for 8 modern analogue countries (Benin, Burundi, Chad, Haiti, Senegal, Sierra Leone, Togo, Zimbabwe), 1960–2022. The dashed red line marks 10× the average compound growth rate (3.5%/yr). About 19% of country-years exceeded this threshold.*

Our final analysis draws on the entire contemporary dataset. The chart below bins all countries in the Maddison data by their 1950–1985 baseline growth rate and shows what share of each group had at least one year between 1986 and 2022 in which growth exceeded 10× that baseline. Countries with zero or negative baseline growth are excluded.

[![Share of countries with at least one 10× growth year, by baseline growth rate](/assets/images/growth_accel2_fig4.png)](/assets/images/growth_accel2_fig4.png)

*Share of countries in each baseline-growth bin (1950–1985 average) that had at least one year of growth exceeding 10× their baseline during 1986–2022. n gives the number of countries in each bin.*

Among the slowest-growing economies — those averaging 0–1%/yr, the same range as our analogues — 94% experienced at least one 10× year. That share falls to 22% for countries averaging 1–2%/yr and to essentially zero above 2%/yr. We find that 10× faster growth is much more common for slow-growing countries, suggesting that a slow-growing economy like the pre-IR UK likely had many years in which growth exceeded 10× its long-run average.

## How common is 10× faster growth today?

Imagine living in Britain around 1700, on the eve of the Industrial Revolution. Annual GDP per capita growth had averaged around 0.30% for the past several centuries — but your experience was not of slow, steady progress. Harvest failures, wars, and disease sent annual growth swinging by 10 percentage points or more in either direction. A year of 0.66% growth — ten times the compound growth rate — was not at all unusual: about one year in two already exceeded that threshold. If someone had told you that growth was about to permanently accelerate tenfold, the new rate would have been something you had already lived through many times. It would have felt, year to year, like a run of good harvests.

Today the story is very different. In the contemporary USA, 10× the compound growth rate implies annual growth of roughly 19% per year. Looking only at the experience of Americans living today, they have *never* experienced this level of growth, even for a single year.

What if we broaden our aperture to the whole world? Below is a histogram of the annual growth rates of all countries in the Maddison dataset from 1950–2022. Only 0.76% of country-years have experienced annual growth rates in excess of 19%.

[![Annual GDP per capita growth, all countries, 1950–2022](/assets/images/growth_accel2_fig5.png)](/assets/images/growth_accel2_fig5.png)

*Distribution of annual GDP per capita growth rates across all countries in the Maddison database, 1950–2022. The dashed red line marks 18.9%/yr — 10× the modern frontier compound growth rate. About 0.8% of country-years exceeded this threshold.*

It is worth examining the 89 country-years that did exceed 20%. The large majority fall into two categories that offer no meaningful precedent for an AI-driven acceleration. The first is oil and resource windfalls: Kuwait's GDP per capita rose 105% in 1992 as oil production restarted after the Gulf War; Libya appears repeatedly through the 1960s oil boom and again in 2012 after Gaddafi fell; Equatorial Guinea, Qatar, Oman, Nigeria, and Gabon each have years driven by commodity discoveries or price spikes. The second is post-conflict recovery: Lebanon in multiple years through its civil war and aftermath, Bosnia in 1996, Rwanda in 1995, Afghanistan in 2002, Iraq in 2004. These are cases of GDP returning to a level it had previously reached, not of an economy operating in a new gear.

A third, smaller category is more genuinely interesting: a handful of countries — South Korea in 1953, Botswana in the early 1970s, some Soviet-bloc countries in the early 1950s — achieved brief periods of very fast growth from genuinely low starting points during early industrialization. This category is worth taking seriously as a partial analogue for the AI argument. If AI unlocks a fundamentally new production frontier, one might argue that today's economies are "at a low base" relative to that frontier's potential, just as early industrializing economies were relative to the technology they were adopting. We think this is the strongest version of the IR-as-precedent argument, and we do not want to dismiss it entirely. What the data do show, however, is that even in this most favorable category, very fast growth was brief and transitional — not a permanent new steady state — and it occurred in economies far poorer and less technologically developed than today's frontier.

In sum, a 10× growth acceleration in the contemporary world, even for a single year, would feel qualitatively different from almost all lived experience. It would be a new way for the economy to operate. In contrast, during the Industrial Revolution, a 10× acceleration would feel like a rather ordinary good year for the economy — with the main difference being that these good years would keep on coming.

## The standard deviation approach

Suppose we understand the Industrial Revolution as "more of the good years, fewer of the bad years." What would that feel like today?

If we want to capture what an IR-level acceleration would feel like today relative to our lived experience, we need a ruler calibrated to current growth experience. The standard deviation of annual growth rates is a useful measure here. For reference, the standard deviations across various samples are:

| Sample | Annual SD |
|--------|-----------|
| Pre-IR UK, 1252–1652 | 6.9% |
| Modern analogue countries (8 countries, 1960–2022) | 5.5% |
| USA, 1950–2022 | 2.3% |
| All countries, 1950–2022 | 6.2% |

Using the pre-IR UK data, the Industrial Revolution amounted to an increase in the compound growth rate from 0.07% to 1.02% — a 15× acceleration, not 10×. The compound rate is the right measure here because it reflects how wealth actually accumulated over time, rather than an arithmetic average inflated by year-to-year volatility. In terms of standard deviations of annual growth rates, going from 0.07% to 1.02% represents an increase of about 0.14 standard deviations measured against the pre-IR UK annual distribution, or 0.17 standard deviations measured against the modern analogue countries.

Taking the US compound growth rate of 1.9% per year as the frontier baseline, a similarly sized increase — 0.17 standard deviations of the analogue distribution, our preferred measure since it doesn't rely on the reliability of pre-IR UK data — would take growth to about 2.8% per year. Using the US standard deviation instead gives about 2.3% per year; using the all-country standard deviation gives about 3.0%. For comparison, a genuine 10× increase in the compound growth rate — from 1.9% to 18.9% — would be an increase of 3.1 standard deviations using the analogue SD, or 7.5 standard deviations using the US SD.

## Reproducing this analysis

The full code and data are in the [growth-acceleration](https://github.com/mattsclancy/growth-acceleration) repository.

### Data

| File | Source |
|------|--------|
| `mpd2023_web.xlsx` | Maddison Project Database 2023, sheet "Full data" |

### Dependencies

```
pip install pandas numpy matplotlib openpyxl
```

Python 3.9+.

### Generating the charts

```
python3 analysis.py
```

Output is saved to `output/`.
