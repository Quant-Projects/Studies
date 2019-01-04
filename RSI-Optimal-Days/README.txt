Study Notes:
  This is a study (made by request) to showcase the optimal number of days to use when calculating RSI.
  In order to get optimal results, we used days from 20 to 50 with RSI to attempt to predict the Adjusted Close Price 10 trading days in the future.
  We used 3 different stocks with data spanning 5 years.  The stocks were $AAPL, $FB, and $TSLA.
  In order to determine the best number of days, we used basic Linear Regression with different RSI's as features, and measures their mean error.

Results:
  RSI is not a very good indicator of future price, as it is greatly overused in trading.  We determined this due to the very high error on all data using different models.
  In general, it the stock doesn't have a high voltality, then the number of days used in RSI doesn't carry very much importance.
  If the stock has a medium or high voltality, then the fewer the days used (starting at 20), the less the error (the better the indicator is).
DISCLAIMER:
  We do not recommend using RSI to trade in any way.
  This study does not mean high returns are guaranteed.
  
THANK YOU FOR READING!
