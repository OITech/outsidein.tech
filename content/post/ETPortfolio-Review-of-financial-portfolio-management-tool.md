+++
title = "ET Portfolio - Review of a Financial Portfolio Management Tool"
date = "2017-04-13"
tags = [ "personal-finance" ]

draft = false
+++

[Economic Times Portfolio](https://etportfolio.indiatimes.com) is a financial portfolio tracking tool which can be used manage financial assets. There are a few such portfolio management tools which have been listed in an earlier [post]({{< ref "portfolio-management-tool.md" >}}). ETPortfolio allows multiple portfolios, tracking of different asset classes like shares, mutual funds, fixed income instruments, loans and so on. It can track your goals and their progress and can generate useful reports like capital gains tax liability, IRR and profit & loss. Here is a full review of ETPortfolio:

<!--more-->

The main screen that you see on logging in {{% footnote id="1" %}}Three portfolios: *Retirement*, *Ch1 Education*, *Ch1 Marriage* are added for illustration{{% /footnote %}}

{{< img src="/outsidein.tech/img/ETPortfolio_Overview.png" caption="Main Screen" >}}

### Goal-based Investing

Any successful portfolio is designed around goals. There is a goal planner included in ETPortfolio where you can add different goals like retirement, education, marriage and so on. Each goal can be linked with a portfolio to track goal progress.

{{< img src="/outsidein.tech/img/ETPortfolio_FinancialGoal_New.png" caption="Add a new financial goal" >}}

Goal progress is shown for each goal:
{{< img src="/outsidein.tech/img/ETPortfolio_FinancialGoal_overview.png" alt="Goal progress" caption="" >}}

Investment amount required for goal is calculated based on the inflation adjusted goal amount. The targets can be calculated as fixed or increasing (based on expected increase in salary)

{{< img src="/outsidein.tech/img/ETPortfolio_FinancialGoal_MoneyTarget.png" caption="Yearly target for the goal" >}}

The "retirement" goal is treated differently from other goals. The goal target is calculated automatically based on inflation, the expected expenditure post retirement and the expected yearly return of investments. One flaw in the retirement calculator is that the start date for retirement computation can't be changed. It is fixed from the day the goal is added. So, if you have already planned for retirement using some other tool, then importing it is difficult. The value of an existing portfolio tagged for retirement cannot be added to the calculation, so the calculator might throw up high targets if you have started using it late.

{{< img src="/outsidein.tech/img/ETPortfolio_FinancialGoal_Retirement.png" caption="Assets invested for retirement vs needed values" >}}

### Supported Account Types

ET Portfolio supports almost all of the common financial instruments. In fact, only EPF is missing in this list, and maybe other types of insurance (like life, health insurance etc.), though they are not strictly investments:

  1. Stocks (BSE/NSE)
  2. Mutual Funds and ETFs
  3. Unit-Linked Insurance Plans (ULIPs)
  4. Fixed Income
     + FD and RD (bank & corporate)
     + PPF
     + NSC and Vikas Patrika
     + RBI and Corporate Bonds
  5. Other Assets (real estate, gold, savings account i.e. cash)
  6. Loans (with fixed & floating interest rates)
    
#### 1. Stocks

ET Portfolio allows all listed stock transactions to be entered. Live tracking of the stock price with gains/losses and IRR is available. The overview page gives the overall sector allocation for stocks and even lists various IPOs running currently and allows you to record applications and stocks allotted.

{{< img src="/outsidein.tech/img/ETPortfolio_Stocks.png" caption="Stocks" >}}

If I had to pick a missing feature, I would say that unlisted/foreign securities should be allowed by manually entering the details. This is useful when you have are invested in private equity or more commonly, have stock benefits granted for stocks listed in other countries. Addition of this in the capital gains computation would really complete the feature set.

#### 2. Mutual Funds and ETFs

Mutual funds can be added here and the NAV and profit/loss is updated daily. {{% footnote id="2" %}}The funds added here are just to create a dummy portfolio, please don't take it seriously.{{% /footnote %}}

{{< img src="/outsidein.tech/img/ETPortfolio_MutualFund_overview.png" caption="Mutual Funds" >}}

The personal IRR for your sequence of transactions for a mutual fund is shown here. Quite useful.
{{< img src="/outsidein.tech/img/ETPortfolio_MutualFund_IRR.png" caption="Mutual Funds IRR" >}}

Detailed transaction history is also available:
{{< img src="/outsidein.tech/img/ETPortfolio_MutualFund_TransHistory.png" caption="Mutual Fund Transaction History" >}}

ETFs are a separate category, though for accounting purposes, they can be treated like stocks.

#### 3. ULIPs

I haven't investigated this fully, but we can add all our ULIP transactions here and it will be reflected as part of the portfolio.

#### 4. Fixed Income

This category contains a lot of different fixed income instruments. The interest amounts are automatically calculated in PPF accounts and other accounts.

{{< img src="/outsidein.tech/img/ETPortfolio_FixedIncome.png" caption="Various Fixed Income instruments supported" >}}

The only missing instrument here is EPF. That is quite bad since EPF usually forms a decent portion of your portfolio, and is usually tagged to your retirement goal. Having EPF here would have made ET Portfolio have complete coverage of most of the asset classes.

#### 5. Other Assets

Assets like real estate and gold/silver can be added here. For real estate, you need to keep updating the market price to correctly reflect the value of the property. Gold and silver values are updated with current prices automatically.

{{< img src="/outsidein.tech/img/ETPortfolio_OtherAssets.png" caption="Real Estate, Gold and Other assets" >}}

#### 6. Loans

Loans for Home/Car/Personal etc. can be added and the EMI can be calculated automatically.

{{< img src="/outsidein.tech/img/ETPortfolio_Loans.png" caption="Add different types of loans" >}}
{{< img src="/outsidein.tech/img/ETPortfolio_Loan_EMI.png" caption="Computed EMI for a loan" >}}

### Adding Transactions

Transactions can be added manually or by uploading an excel in a specific format. Pasting transactions in an online excel-like table is supported, but only for stocks. Overall, the ease of use can be improved. Uploading CAMS summaries are not supported. Transactions from your [Savings Ledger]({{< ref "Savings-Ledger.md" >}}) can be uploading by cutting few of the extra columns.

{{< img src="/outsidein.tech/img/ETPortfolio_AddTransaction.png" caption="Add different types of transactions" >}}

SIPs and SWPs are also supported.

### Reports and Graphs

As mentioned in my post - [requirements of a portfolio management tool]({{< ref "portfolio-management-tool.md" >}}), IRR and capital gains tax computations are the most useful to have. ETPortfolio supports a variety of reports including these.
{{< img src="/outsidein.tech/img/ETPortfolio_Reports_CapGain.png" caption="Capital Gains Report" >}}

Internal Rate of Return (IRR) for the complete portfolio:
{{< img src="/outsidein.tech/img/ETPortfolio_Reports_IRR.png" caption="Internal Rate of Return Report" >}}

Profit/Loss statement:
{{< img src="/outsidein.tech/img/ETPortfolio_Reports_ProfitLoss.png" caption="Profit/Loss Report" >}}

There are some bugs with the exporting of data, but it is never wise to solely rely on these tools for your data. You should save your transaction history locally in the [Savings Ledger]({{< ref "Savings-Ledger.md" >}}) excel sheet for safekeeping.

### Other Features

ET Portfolio supports a watchlist feature where you can keep an eye on various stocks/mutual funds/indices and see their gains & losses. ET portfolio also has a mobile [app](https://play.google.com/store/apps/details?id=com.et.reader.activities) for viewing your portfolio on the go. It is a part of the Economic Times app.

{{< img src="/outsidein.tech/img/ETPortfolio_Watchlist.png" caption="Watchlist" >}}

### Caveats

Here are the some problems & missing features:

  - No support for entering/tracking EPF transactions.
  - No separate debt portion. Cannot see an overview of equity:debt ratio of the portfolio.
  - No fund components and overlap. Cannot view the holdings of a mutual fund and find if there is any overlap between funds. Although this is an advanced requirement.
  - No Large-Mid-Small cap exposure details. Cannot review if the exposures are within individual risk levels.
  - No debt details and credit quality. Cannot review if the overall debt credit quality is within our risk level.
  - Issues with reports for ETFs. ETFs are treated separately from Shares and Mutual Funds, and have bugs with report generation.
  - No unlisted/foreign stocks. Although now I am asking for a bit much.
- Makes for a jittery investor since portfolio gain/loss/XIRR is easily available every day.

In all, I found ET Portfolio to be quite useful, especially its reports and its support for a large variety of asset classes. Since it supports all asset classes, it gives you a good overview of your networth and listing of your financial assets. I use it for tracking my portfolios along with [Value Research Portfolio](https://www.valueresearchonline.com/port/) for mutual fund insights and [Savings Ledger]({{< ref "Savings-Ledger.md" >}}) to store my list of transactions locally.

If you have any questions, shoot a comment below.