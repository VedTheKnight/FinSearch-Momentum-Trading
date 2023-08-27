# FinSearch---Momentum-Portfolio-D1

"Overlapping Portfolios.ipynb" contains code for a momentum trading strategy with a rebalance period of 1 month. We varied the holding periods and the lookback periods from 3 to 12 
in steps of 3. Also we considered two cases one with a standard lookback period and one excluding the most recent month of the lookback period. This was to analyse the effects 
of Return Reversal on our strategies. We have included the findings of this strategy in the report since the findings agreed most with what is theoretically known.

"Non Overlapping Portfolios.ipynb" contains code for a momentum trading strategy where we take the holding period same as the rebalance period. We vary lookback period as 12,6,3
and holding period as 1,3,6,12. Further we once againg considered two cases one with a standard lookback period and one excluding the most recent month of the lookback period to 
analyse Return Reversal. We obained unexpected variation with holding period which contradicted known theoretical trends. We left these results out of the report for the time
being.

"Momentum_Calculation.ipynb" contains an attempt similar to the one above.

"Return Reversal.ipynb" contains code which aims to demonstrate the phenomenon of return reversal over a range of holding periods. We plot the returns of the top decile-"winners"
and bottom decile-"losers" ranging holding period from 1 month to 60 months. We obtained a very interesting trend where return reversal dominated for short and long time-frames 
while the winners continued to win in the intermediate time frames. We have included this in more depth in our report.

"Return Reversal Testing on Large Sample.ipynb" was a test with short lookback period and holding period of 3,6 and 9 months with varying sample sizes of N = 10,20,25 and 50. We plotted graphs for various cases. This gave us an indication as to what the optimal momentum strategy would be for week 6 Nifty-100 stocks.

"6-week Nifty-100 Analysis.ipynb" determines the 10 worst and 10 best performing stocks over a lookback period of 6 weeks. We conclude that the 10 worst performing stocks should be a part of our portfolio for the next 3,6 and 9 months.

"Mean_Reversion.ipynb" Analyses the opening and closing prices for the last 6 weeks of the Nifty-100 stocks and determines whether or not we should buy or sell using the  RSI and the Bellinger Bands. We use this knowledge to filter our picked stocks which we determined in "6-week Nifty-100 Analysis.ipynb".
