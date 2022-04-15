---
id: mbm1vidwed90xyd1t5gtfa6
title: Relative Strength Index (RSI)
desc: ''
updated: 1649985172741
created: 1649905202115
---
# Relative Strength Index (RSI)

ref: [Investopedia](https://www.investopedia.com/terms/r/rsi.asp), [Wikipedia](https://en.wikipedia.org/wiki/Relative_strength_index)

The relative strength index (RSI) is a popular momentum oscillator developed in 1978.

The RSI is displayed as an oscillator (a line graph that moves between two extremes) and can have a reading from 0 to 100.

The RSI measures the magnitude of recent price changes to evaluate overbought or oversold conditions in the price of a stock or other asset. 
- An asset is usually considered overbought or overvalued when the RSI is above 70 and may be primed for a trend reversal or corrective pullback in price
- An RSI reading of 30 or below indicates an oversold or undervalued condition

![rsi-example](https://www.investopedia.com/thmb/WogEtwrQv5MwcshRV5qs66BJB10=/660x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/dotdash_final_Relative_Strength_Index_RSI_Jul_2020-01-98fcd0c032cb4f0da005c31c44440c90.jpg){max-width: 300px, display: block, margin: 0 auto}

## Interpretation of RSI

The RSI was designed to indicate whether a security is overbought or oversold in relation to recent price levels. The RSI is calculated using average price gains and losses over a given period of time. The default time period is 14 periods, with values bounded from 0 to 100.

[[Moving Average Convergence Divergence (MACD)|notes.tutorial.finance.technical-analsis.macd]] and Relative Strength Index (RSI) are indicators that measure the momentum of an asset. However, they measure different factors, so they sometimes give contradictory indications. 
- For example, the RSI may show a reading above 70 for a sustained period of time, indicating the security is overextended to the buy side
- At the same time, the MACD could indicate that buying momentum is still increasing for the security

The basic idea behind the RSI is to measure how quickly traders are bidding the price of the security up or down. Traders will often place this RSI chart below the price chart for the security, so they can compare its recent momentum against its market price.

## Calculation

For each trading period an upward change $U$ or downward change $D$ is calculated. 

- Up periods are characterized by its close being higher than the previous close.

    $$U = close_{now} - close_{previous}$$
    
    $$D = 0$$

- Down period is characterized by the close being lower than the previous period's close

    $$U = 0$$
    
    $$D = |close_{now} - close_{previous}|$$

- If the last close is the same as the previous, both $U$ and $D$ are zero

