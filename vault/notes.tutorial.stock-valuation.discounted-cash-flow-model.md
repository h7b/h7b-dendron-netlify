---
id: y0xnookb0xf0ifb3kaal0t1
title: Discounted Cash Flow Model
desc: ''
updated: 1649562546251
created: 1647317532092
---
# Discounted Cash Flow Model
ref: 
- [Investopedia](https://www.investopedia.com/terms/d/dcf.asp)
- [Aswath Damodaran | Session 2: Intrinsic Value - Foundation](https://www.youtube.com/watch?v=8vYQpWXQ5hE&list=PLUkh9m2BorqnKWu0g5ZUps_CbQ-JGtbI9&index=2)
- [Aswath Damodaran | Discounted Cashflow Valuation: Equity and Firm Models](https://people.stern.nyu.edu/adamodar/pdfiles/ovhds/dam2ed/dcfveg.pdf)

Discounted cash flow (DCF) analysis attempts to figure out the value of an investment today, based on projections of how much money it will generate in the future.

![dcf-model](https://ik.imagekit.io/casa/h7b-dendron/Screenshot_2022-03-21_230130_Hml7ZRE5b.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1647900103621){max-width: 300px, display: block, margin: 0 auto}

## Formula

In general,

$$Value = \frac{CF_1}{(1+r)^1} + \frac{CF_2}{(1+r)^2} + ... + \frac{CF_n}{(1+r)^n}$$

where
- $CF =$ the cash flow for the given year
  - $CF_1 =$ the cash flow for the 1st year
  - $CF_2 =$ the cash flow for the 2nd year
  - $CF_n =$ the cash flow for the year $n^{th}$
- $r =$ the discount rate
  - Companies typically use the weighted average cost of capital (WACC) for the discount rate, because it takes into consideration the rate of return expected by shareholders

## What DCF Can Tell You

The purpose of DCF analysis is to estimate the money an investor would receive from an investment, adjusted for the time value of money. The time value of money assumes that a dollar today is worth more than a dollar tomorrow because it can be invested.

## Variations of DCF
ref: [Aswath Damodaran](https://pages.stern.nyu.edu/~adamodar/New_Home_Page/lectures/basics.html), [Simply Wall St Help Center](https://support.simplywall.st/hc/en-us/articles/360001741016-How-is-fair-value-calculated)

### Which DCF model to choose?

The fundamental choices for DCF valuation:
- Cashflows to Discount
    - Dividends
        - for firms which pay dividends (and repurchase stock) which are close to the Free Cash Flow to Equity (over a extended period)
        - for firms where FCFE are difficult to estimate (Example: Banks and Financial Service companies)
    - Free Cash Flows to Equity (FCFE)
        - for firms which pay dividends which are significantly higher or lower than the Free Cash Flow to Equity. (What is significant? ... As a rule of thumb, if dividends are less than 75% of FCFE or dividends are greater than FCFE)
        - for firms where dividends are not available (Example: Private Companies, IPOs)
        - for firms which have stable leverage, whether high or not, and
        - if equity (stock) is being valued
    - Free Cash Flows to Firm (FCFF)
        - for firms which have high leverage, and expect to lower the leverage over time, because
            - debt payments do not have to be factored in
            - the discount rate (cost of capital) does not change dramatically over time.
        - for firms for which you have partial information on leverage (eg: interest expenses are missing..)
        - in all other cases, where you are more interested in valuing the firm than the equity.
- Expected Growth. Use the growth model only if cash flows are positive
    - Stable Growth
    - Two Stages of Growth: High Growth -> Stable Growth
        - Use the two-stage growth model if the firm is growing at a moderate rate ( within 8% of the stable growth rate)
    - Three Stages of Growth: High Growth -> Transition Period -> Stable Growth
        - Use the three-stage growth model if the firm is growing at a high rate ( more than 8% higher than the stable growth rate)
- Discount Rate: should be consistent with the cash flow being discounted
    - Cash Flow to Equity -> Cost of Equity
    - Cash Flow to Firm -> Cost of Capital
- Base Year Numbers
    - Current Earnings / Cash Flows
    - Normalized Earnings / Cash Flows

Fig: The building blocks of Valuation

![building-blocks-of-valuation](https://ik.imagekit.io/casa/h7b-dendron/Screenshot_2022-04-09_000324_X5I-DEaP8.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1649455494781){max-width: 300px, display: block, margin: 0 auto}

#### Three stages of Growth

According to *Sharpe, Alexander, and Bailey 1999* [^1], growth falls into three stages:
- Growth phase
    - A company in its growth phase typically enjoys rapidly expanding markets, high profit margins, and an abnormally high growth rate in earnings per share
    - Companies in this phase often have negative free cash flow to equity because the company invests heavily in expanding operations
    - Given high prospective returns on equity, the dividend payout ratios of growth-phase companies are often low or even zero
    - As the company’s markets mature or as unusual growth opportunities attract competitors, earnings growth rates eventually decline
- Transition phase
    - In this phase, which is a transition to maturity, earnings growth slows as competition puts pressure on prices and profit margins or as sales growth slows because of market saturation
    - earnings growth rates may be above average but declining toward the growth rate for the overall economy
    - Capital requirements typically decline in this phase, often resulting in positive free cash flow and increasing dividend payout ratios (or the initiation of dividends)
- Mature phase
    - In maturity, the company reaches an equilibrium in which investment opportunities on average just earn their opportunity cost of capital
    - The dividend and earnings growth rate of this phase is called the **mature growth rate**
    - This phase reflects the stage in which a company can properly be valued using the Gordon growth model

[^1]: Sharpe, W. F., Alexander, G. J., & Bailey, J. V. (1999). Investments: International Edition (6th ed.). London: Prentice Hall International Inc. [URL to Google Books](https://books.google.fr/books/about/Investments.html?id=8D2tQgAACAAJ)

Fig: Three typical growth patterns

![growth-pattern](https://pages.stern.nyu.edu/~adamodar/New_Home_Page/lectures/Image7.gif){max-width: 300px, display: block, margin: 0 auto}

#### Summary - DCF model choice

Fig: Steps to choose DCF model

![classify-dcf-models](https://ik.imagekit.io/casa/h7b-dendron/Screenshot_2022-04-09_000415_MjgmDhuu_.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1649455494772){max-width: 300px, display: block, margin: 0 auto}

| | Dividend Discount Model | FCFE Model | FCFF Model |
|:---|:---|:---|:---|
| Stable Growth Model |- Growth rate in firm's earnings is stable ($g_{firm-economy}$+1%)<br>- Dividends are close to FCFE (or) FCFE is difficult to compute<br>- Leverage is stable |- Growth rate in firm's earnings is stable ($g_{firm-economy}$+1%)<br>- Dividends are very different from FCFE (or) Dividends not available (Private firm)<br>- Leverage is stable |- Growth rate in firm's earnings is stable ($g_{firm-economy}+1%)<br>- Leverage is high and expected to change over time (unstable) |
| Two-Stage Model |- Growth rate in firm's earnings is moderate<br>- Dividends are close to FCFE (or) FCFE is difficult to compute<br>- Leverage is stable |- Growth rate in firm's earnings is moderate<br>- Dividends are very different from FCFE (or) Dividends not available (Private firm)<br>- Leverage is stable |- Growth rate in firm's earnings is moderate<br>- Leverage is high and expected to change over time (unstable) |
| Three-Stage Model |- Growth rate in firm's earnings is high<br>- Dividends are close to FCFE (or) FCFE is difficult to compute<br>- Leverage is stable |- Growth rate in firm's earnings is high<br>- Dividends are very different from FCFE (or) Dividends not available (Private firm)<br>- Leverage is stable |- Growth rate in firm's earnings is high<br>- Leverage is high and expected to change over time (unstable) |

#### Growth and Firm Characteristics

|  | Dividend Discount Model | FCFE Discount Model | FCFF Discount Model |
|:---|:---|:---|:---|
| High growth firms generally |- Pay no or low dividends<br>- Earn high returns on projects (ROA)<br>Have low leverage (D/E)<br>- Have high risk (high betas) |- Have high capital expenditures relative to depreciation.<br>- Earn high returns on projects<br>- Have low leverage<br>- Have high risk |- Have high capital expenditures relative to depreciation<br>- Earn high returns on projects<br>- Have low leverage<br>- Have high risk |
| Stable growth firms generally |- Pay large dividends relative to earnings (high payout)<br>- Earn moderate returns on projects (ROA is closer to market or industry average)<br>- Have higher leverage<br>- Have average risk (betas are closer to one) |- narrow the difference between cap ex and depreciation (Sometimes they offset each other)<br>- Earn moderate returns on projects (ROA is closer to market or industry average)<br>- Have higher leverage<br>- Have average risk (betas are closer to one) |- narrow the difference between cap ex and depreciation (Sometimes they offset each other)<br>- Earn moderate returns on projects (ROA is closer to market or industry average)<br>- Have higher leverage<br>- Have average risk (betas are closer to one) |

### DCF model for Firm with stable growth

aka Gordon growth model or constant growth forever

$$V_0=\frac{CF_1}{r-g}$$

where:
- $V_0=$ Value of Equity (if cash flows to equity are discounted) or Firm (if cash flows to firm are discounted)
- $CF_1=$ Cash Flow in period after the most recent $CF_0$; Dividends or FCFE if valuing equity; FCFF if valuing firm
- $r=$ Cost of Equity (if discounting Dividends or FCFE) or Cost of Capital (if discounting FCFF)
- $g=$ Expected growth in Cash Flow being discounted in stable period

Use the stable growth model, if the firm is growing at a rate which is below or close (within 1-2%) to the growth rate of the economy

#### Related readings

- pp. v3_440 - v3_448. Section *3 The Gordon Growth Model*. Book *2022 CFA Program Curriculum Level II Box Set Volumes 1-6*. Calibre Library.

### DCF model for Firm with two distinct stages of growth

aka two-stage growth model.

Basically, the two-stage DCF is a multiple-period model. It means that simply find the present value of the first $n$ dividends and the present value of the projected value at time $n$

$$V_0 = \displaystyle\sum_{t=1}^n \frac{CF_t}{(1+r)^t} + \frac{V_n}{(1+r)^n}$$

The two-stage model assumes that the first $n$ dividends grow at an extraordinary short-term rate, $g_S$.

$$CF_t = CF_0(1+g_S)^t$$

After time $n$, the annual dividend growth rate changes to a normal long-term rate, $g_L$. The cash flow at time $n+1$ is:

$$CF_{n+1} = CF_n(1+g_L) = CF_0(1+g_S)^n(1+g_L)$$

Applying Gordon growth model to find:

$$V_n = \frac{CF_{n+1}}{r-g_L} = \frac{CF_0(1+g_S)^n(1+g_L)}{r-g_L}$$

Which leads to the formula to find the value at $t=0$

$$V_0 = \displaystyle\sum_{t=1}^n \frac{CF_0(1+g_S)^t}{(1+r)^t} + \frac{CF_0(1+g_S)^n(1+g_L)}{(1+r)^n(r-g_L)}$$

where:
- $V_0=$ Value of Equity (if cash flows to equity are discounted) or Firm (if cash flows to firm are discounted)
- $CF=$ Cash Flow in period t; Dividends or FCFE if valuing equity; FCFF if valuing firm
- $r=$ Cost of Equity (if discounting Dividends or FCFE) or Cost of Capital (if discounting FCFF)
- $g_S=$ Expected high growth short-term rate for the initial period
- $g_L=$ Expected sustainable growth long-term rate for the next period

Suitable for companies that are not expected to grow at a constant rate over time. These companies tend to be high-growth initially and become stable after a couple of years.

#### Related readings

- pp. v3_456 - v3_461. Section *6.1 Multistage Dividend Discount Models: Two-Stage Dividend Discount Model and Valuing a non-dividend paying company*. Book *2022 CFA Program Curriculum Level II Box Set Volumes 1-6*. Calibre Library.

### DCF model for Firm with three distinct stages of growth

aka three-stage growth model.

Fuller and Hsia (1984) developed H-model, a variant of the two- stage model in which growth begins at a high rate and declines linearly throughout the supernormal growth period until it reaches a normal rate at the end.

#### Related readings

- pp. v3_461 - v3_461. Section *7 The H-model and three-stage Dividend Discount Model*. Book *2022 CFA Program Curriculum Level II Box Set Volumes 1-6*. Calibre Library.

### Excess Returns Model

Used for financial companies such as banks and insurance firms. These companies generally do not have a significant proportion of physical assets and face different regulatory requirements for cash holdings to other businesses.

### Adjusted-Funds-From-Operations (AFFO) 2-Stage Discounted Cash Flow Model

Used for Real Estate Investment Trusts (REITs) as these companies incur capital gains and other real estate-specific factors which impacts their free cash flows.

### [[Dividend Discount Model (DDM)|notes.tutorial.stock-valuation.dividend-discount-model]]

Suitable for companies that consistently pay out a meaningful portion of their earnings as dividends.
