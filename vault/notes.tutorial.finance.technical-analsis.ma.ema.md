---
id: 9o5c8jy9akypc7rwk2v8sgh
title: Exponential Moving Average (EMA)
desc: ''
updated: 1649903455930
created: 1649902259855
---
# Exponential Moving Average (EMA)

ref: [Investopedia](https://www.investopedia.com/terms/e/ema.asp)

The EMA is a moving average that places a greater weight and significance on the most recent data points.

An exponentially weighted moving average reacts more significantly to recent price changes than a [[simple moving average (SMA)|notes.tutorial.finance.technical-analsis.ma.sma]], which applies an equal weight to all observations in the period.

Since EMAs place a higher weighting on recent data than on older data, they are more responsive to the latest price changes than SMAs.

## Formula

$$EMA = ClosingPrice * multiplier + EMA_{previousDay} * (1 - multiplier)$$

where:
- $multiplier = \frac{smoothing(weighting)}{number\ of\ Observations + 1}$
- there are many possible choices for the smoothing factor, the most common choice is: $smoothing=2$

Example: a 20-day EMA, the multiplier would be $\frac{2}{20+1} = 0.0952$.

## What Does the Exponential Moving Average Tell You?

The 12- and 26-day exponential moving averages (EMAs) are often the most quoted and analyzed short-term averages. The 12- and 26-day are used to create indicators like the [[moving average convergence divergence (MACD)|notes.tutorial.finance.technical-analsis.macd]]