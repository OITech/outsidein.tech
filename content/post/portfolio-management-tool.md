+++
date = "2017-04-06T19:35:01+05:30"
title = "Portfolio Management Tools"
tags = [ "personal-finance" ]
draft = false
+++

In this post, we will talk about some of the tools/apps/websites available to manage your financial portfolio. The [list]({{< relref "#list-of-portfolio-tools" >}}) below contains multiple tools, and I will review each one in further posts. But first, let us evaluate why we need such a tool and what the requirements of such a tool are.

<!--more-->

### Why do we need portfolio management?

A portfolio management tool allows us to keep track of our investments and do common portfolio operations like:

  * Consolidating asset lists in one place to get overall view of net worth.
  * Computing the capital gains tax to be paid for the financial year.
  * Rebalancing the portfolio so that the asset allocation (equity-debt ratio) remains the same as what was initially planned.
{{% footnote id="2" %}} **e.g.** 

  * Initial asset allocation = 60:40 (equity:debt)
  * After a year - ratio of equity:debt was now 70:30 (because equity grew more)
  * Move some amount from equity to debt → ratio becomes 60:40 once again.
    
 This serves to move some of the gains from equity to a less volatile instrument like debt and reduce risk exposure.
{{% /footnote %}}
  * Finding out the exposure to Large-Cap, Mid-Cap and Small-Cap companies and checking that it is within personally acceptable risk levels. Similarly, finding out whether the credit quality of debt instruments is within acceptable levels.
{{% footnote id="3" %}} **e.g.** I prefer atleast 60% largecap exposure, and not more that 10% AA or lower debt. {{% /footnote %}}
  * Giving the portfolio rate of return and personal IRR for each fund for our sequence of investments. This helps in deciding if a fund is performing as per expectations and whether we should continue investing or switch to a different fund.

Ironically the feature that most tools offer - i.e. live update of NAV and net worth is actually not required. In fact, it is a bad feature, since it makes the investor jittery and likely to make impulsive decisions. Portfolio review usually happens only once a year, and the NAV on that day is sufficient for this calculation.

### Basic portfolio tool requirements

So, the following are the requirements for a portfolio tool. Having these features will make the periodic portfolio review easy, and give a clear picture of asset allocation and goal progress.

  - Gives Internal Rate of Return (IRR) for tracking a funds performance
  - Gives equity/debt ratio for rebalancing
  - Capital gains calculation for taxation
  - Tagging funds to goals & tracking goal progress
  - Import/Export of data

### Advanced requirements

  - Large-Cap/Mid-Cap/Small-Cap exposure
  - Debt credit quality
  - Portfolio overlap - show funds holding overlapping stocks, so that one can be dropped

### List of portfolio management tools {#list-of-portfolio-tools}

  * [ET Portfolio](https://etportfolio.indiatimes.com) - read my full [review]({{< ref "ETPortfolio-Review-of-financial-portfolio-management-tool.md" >}}).
  * [Value Research Portfolio](https://www.valueresearchonline.com/port/)
  * Freefincal's Excel-based [tracker](https://freefincal.com/features-freefincal-mutual-fund-financial-goal-tracker/)
  * [Mprofit Investor](http://www.mprofit.in/) (desktop app - free upto Rs. 50 lakhs portfolio value)
  * [Perfios](https://www.perfios.com/)
  * [Morningstar](http://morningstar.in/pm/default.aspx)
  * [Moneycontrol](http://www.moneycontrol.com/india/bestportfoliomanager/investment-tool)

I haven't mentioned the excellent consolidated account statement (CAS) that NSDL sends out each month. If you have a simple portfolio containing 1 or 2 funds (see [minimalist portfolio](https://freefincal.com/minimalist-portfolio-ideas-for-young-earners/)), then it might be sufficient. One point to note is that these tools may go down any time, so it is always good to have a local copy of your data. Check out [Savings Ledger]({{< ref "Savings-Ledger.md" >}}) - an excel tracker for your investment transactions containing all asset classes. You can use it to list all transactions and then upload them to these sites.

If I have missed out any portfolio tool which you use, please mention it in the comments below.