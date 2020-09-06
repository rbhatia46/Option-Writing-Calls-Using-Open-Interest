# Option-Writing-Calls-Using-Open-Interest
Deciding the strike pries for writing options, based on the Open Interest from the option chain data from NSE(National Stock Exchange)

**Disclaimer - This is purely for educational and research purposes, I am in no way responsible for any monetary loss/gain you make using this, I highly encourage you to view this as a learning resource and not as an investment/trading advice.**

Trading Options can be tricky, choosing a strike price randomly can be a risky decision, and can even cause a huge loss of capital, if things don't go as expected, using the Open interest to look at the total number of contracts at a given strike price could be one of the factors to decide a strike price before writing a CALL/PUT, this is just one of the factors and there are lot many we can use.

A high open interest at a given strike price gives a good enough about about the support/resistance for a given index/stock.

In this notebook, we explore how we can scrape the option chain for a given index/stock from the NSE Website and then use the open interest to decide strike prices.

