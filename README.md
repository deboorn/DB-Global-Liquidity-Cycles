# DB-Global-Liquidity-Cycles

CC BY-SA 4.0 DEED
Attribution-ShareAlike 4.0 International
License: https://creativecommons.org/licenses/by-sa/4.0/

TradingView DB Global Liquidity Cycles Indicator

ndicator designed to show global liquidity cycles and is designed specifically for the weekly timeframe. Special attention should be paid from 2008+ timeframe as that's when quantitative tightening (QT) was implemented.

Global liquidity cycles may be useful as it describes the amount of resources available for investments on a global scale. This indicator is designed to allow the easy visualization of global liquidity cycles from a post 2008 (QT) timeframe which is of tremendous help to long term investors.

**How the Core Global Liquidity (GL) is Obtained?**

China Government Bonds 10 YR Yield
/ U.S. Dollar Index
/ CE BofA US High Yield Index Option-Adjusted Spread

Multiplied By

United States Central Bank Balance Sheet
+ Bank of Japan: Total Assets for Japan
+ China Central Bank Balance Sheet
+ Central Bank Assets for Euro Area (11-19 Countries)

Global liquidity formula above discovered by Twitter TechDev_52

**How is the percentage plot (P) then calculated from the the Global Liquidity (GL) above?**

The indicator then takes the combined global liquidity level calculated above (GL) and reduces it by a factor of 1,000,000,000 for performance reasons.

An internal top band (TB) is then calculated by taking the cumulative moving average (CMA) of the global liquidity (GL) and multiplying that by a factor of 2.6. The latter simply moves the internal band up to the top level of the trend. The top band (TB) is important as it allows us to know the cycle trends and then reformat the display to a percentage range.

The global liquidity (GL) level is then divided by the top band (TB) level to obtain a percentage (P) of the GL against the TB. The percentage (P) is then plotted which presents the GL within a range against the TB. The percentage (P) is the blue line plotted by the indicator.

The indicator then plots a few levels for oversold and overbought visualizations. Any P value on the weekly timeframe with a value of 90+ is considered overbought. Any P value on the weekly timeframe with a value of 30 or less is considered oversold.

Additionally, there are two settings to enable simple projections which simply take P and offset by the supplied number of weeks. By default these are set to 4 years (in weeks) for offset 1 and 8 years (in weeks) for offset 2. The purpose of the optional projections is simply to project into the future the past cycles with a user defined offset which can be helpful for visualizing future periods.

