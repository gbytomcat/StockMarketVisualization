StockMarketVisualization
========================

*What is the topic you'd like to explore?*
Study the co-fluctuation of stocks and visualize the the stock market structure
 
*Why is this topic personally important to you? What is it about the topic that most fascinates you?*
Over the past few years, I have developed an interest in Quantitative Finance and would like to
explore the gazillion byte of financial data available. It will be interesting to apply ML techniques
to this data set.
 
p.s: This has been done many many times already. But I would like this to be a first step.
A sample implementation can be found at this [link](http://scikit-learn.org/stable/auto_examples/applications/plot_stock_market.html)
 
*What is the question, or what are the main questions, that you'd like to answer about this topic?*
+ What stocks have historically moved together
+ Do certain stocks have a delayed window of moving together
+ Do stock co-fluctuate differently in good times (market peaks) as opposed to bad times (market crashes)
 
*What are the types of available data relevant to your questions?*
+ Stock market data - Historical data for companies' trading prices
+ Company fundamentals
+ Market Index data
 
*Beyond the community of this classroom, whom are the other audiences that you might like to reach with the results of this project?*
This is an exploratory project.
 
Brief
-----
Plot a relevance network of the Stock market variations. Identify market movers based on
factors other than just the historical prices. Understand what factors act as triggers for a
large scale stock price changes and measure the co-fluctuation of other stocks.
Study the historical co-fluctuation of stocks, specificall for certain time periods
heading in to a Financial crisis and Recovery from said crisis.
 
Sample implementation from Scikit-Learn
---------------------------------------
In this case, the plot is generated for a given set of stock symbols according to the
daily variations in quote prices. The unsupervised learning model clusters the symbols as
represented in the relevance graph.
