---
id: WXoYpLmbGZWi9gVX
title: How to Collect Market Data (stocks/crypto)
desc: ''
updated: 1642895494829
created: 1626513463054
---
# How do I get stocks/crypto trading data

Ref: [Towards Data Science](https://towardsdatascience.com/best-5-free-stock-market-apis-in-2019-ad91dddec984), [Algotrading101](https://algotrading101.com/learn/yfinance-guide/), [awesome-quant | Data Sources](https://github.com/wilsonfreitas/awesome-quant#data-sources)

Paid official data provider:
- [IEX Cloud](https://iexcloud.io/)
    - [Pricing](https://iexcloud.io/pricing/) starts at USD 19/month. Has free plan 
- [Alpha Vantage](https://www.alphavantage.co/)
    - Has [addon](https://www.alphavantage.co/spreadsheets/) for spreadsheet apps
    - [Premium plan](https://www.alphavantage.co/premium/) starts at USD 50/month. It also has Free API key for consumers
- [polygon.io](https://polygon.io/)
    - Different [Pricing](https://polygon.io/pricing) for stocks, currencies and options. Has free plan

Free unofficial community package:
- manually download historical data from <https://www.investing.com/> or use [investpy](https://github.com/alvarobartt/investpy)
- [pandas-datareader](https://pydata.github.io/pandas-datareader/) Python package
- and many other can be found in this list [awesome-quant | Data Sources](https://github.com/wilsonfreitas/awesome-quant#data-sources)

## Helpful resources

[awesome-quant | curated list of libraries, packages and resources for Quants](https://github.com/wilsonfreitas/awesome-quant)

[Algotrading101 | Yahoo Finance API Guide](https://algotrading101.com/learn/yahoo-finance-api-guide/)

[Algotrading101 | Alpha Vantage API Guide](https://algotrading101.com/learn/alpha-vantage-guide/)

[Algotrading101 | IEX API Guide](https://algotrading101.com/learn/iex-api-guide/)

[IEX cloud blog | How to Get Market Data in Python](https://iexcloud.io/community/blog/how-to-get-market-data-in-python)

[Analyzing Alpha | Get Historical Price Data from Polygon.io](https://analyzingalpha.com/get-historical-price-data-polygon)

[Thecleverprogrammer | Pandas Datareader using Python](https://thecleverprogrammer.com/2021/03/22/pandas-datareader-using-python-tutorial/)

[[Analyze cryptoassets using PostgreSQL and TimescaleDB|notes.reading.timescaledb-analyze-cryptoassets]]

[Create Tables with PostgreSQL and TimescaleDB](https://www.youtube.com/watch?v=P-flYBbmCws&list=PLvzuUVysUFOsrxL7UxmMrVqS8X2X0b8jd&index=4)

[TimescaleDocs | Analyze historical intraday stock data](https://docs.timescale.com/timescaledb/latest/tutorials/analyze-intraday-stocks/)

[Erol Aspromatis | Get Stock Pricing Data From The Polygon.io API For Algo-Trading Using Python](https://www.youtube.com/watch?v=sTlBQ3nVuJE)

[[PythonForFinance - Build Financial Data Database with Python|notes.reading.build-financial-database-with-python]]