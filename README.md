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
while the winners continued to win in the intermediate time frames. We have included this in more depth in our report
