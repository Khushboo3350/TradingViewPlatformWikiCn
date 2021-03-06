# Point and Figure (PnF) Charts

## 目录

-   [DEFINITION](#DEFINITION)
-   [BOX TYPES](#BOX_TYPES)
-   [BOX CALCULATION METHODS](#BOX_CALCULATION_METHODS)
-   [USES OF POINT AND FIGURE CHARTS](#USES_OF_POINT_AND_FIGURE_CHARTS)
-   [POINT AND FIGURE CHARTS SPECIFIC OPTIONS IN TRADINGVIEW](#POINT_AND_FIGURE_CHARTS_SPECIFIC_OPTIONS_IN_TRADINGVIEW)

# DEFINITION

Point and Figure Charts (PnF) are another example of a chart type that relies solely on price movements and not time intervals during the creation of the chart. In this way, PnF Charts are similar to  [Renko](https://www.tradingview.com/wiki/Renko_Charts "Renko Charts"),  [Kagi](https://www.tradingview.com/wiki/Kagi_Charts "Kagi Charts")  and  [Line Break Charts](https://www.tradingview.com/wiki/Line_Break_Charts "Line Break Charts"). A basic understanding of PnF Charts is that they are comprised of a series of columns made from either X's or O's. X columns represent rising prices, while columns consisting of O's denote falling prices. Point and Figure Charts were originally popular in the early 1900's before the prominence of computer based charting. They were a way for  [technical analysts](https://www.tradingview.com/wiki/Technical_Analysis "Technical Analysis")  to chart large amounts of data in a short period of time. With the rise of computers, PnF Charts fell out of favor for quite a while. However recently, PnF Charts are once again gaining in popularity. Overall, there is a renewed interest in "[noise](https://www.tradingview.com/wiki/Noise "Noise")  filtering" charts which focus on price movements alone.

<iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_c45af&symbol=AA&interval=D&hidetoptoolbar=1&hidesidetoolbar=1&symboledit=1&saveimage=0&toolbarbg=000000&studies=&hideideas=1&theme=White&style=6&timezone=Etc%2FUTC&hidevolume=1&padding=0&studies_overrides=%7B%7D&overrides=%7B%7D&enabled_features=%5B%5D&disabled_features=%5B%5D&locale=en&utm_source=www.tradingview.com&utm_medium=widget&utm_campaign=chart&utm_term=AA" frameborder="0" width="750" height="500"></iframe>
  
The X's and O's that make up each column occupy a space called the "Box Size". The box size is a user determined value. When price moves enough in the same direction as the current column, a new X or O is added to that column. When price closes far enough away in the opposite direction, a new column begins with either an X or an O (The opposite of the previous column). The amount that price must move is determined by the reversal distance. This value is created by multiplying the box size by another user defined value, the "Reversal Amount". The reversal amount is the number of bricks price must move in order for a new letter to be drawn or a new column to be created. Therefore if the box size is set to 1 ($1) and the reversal amount is set to 3, then price must move $3 in order for a new letter to be added to the chart.

**There are two rules regarding the letters and columns.**

1.  Each column has to be either X's or O's. There can never be two different letters in the same column.
2.  X columns and O columns will always alternate. You will never see two X columns side by side and vice versa.

# BOX TYPES

**There are four different types of lines that can be drawn within a PnF Chart.**

1.  **Up Bars**  - Form during an  [uptrend](https://www.tradingview.com/wiki/Market_Trend#Bullish "Market Trend").
2.  **Down Bars**  - Form during a  [downtrend](https://www.tradingview.com/wiki/Market_Trend#Bearish "Market Trend").
3.  **Projected Up Bars**  - During an intraday timeframe, a potential up line that would form based on current price (before actual closing price is set).
4.  **Projected Down Bars**  - During an intraday timeframe, a potential down line that would form based on current price (before actual closing price is set).

# BOX CALCULATION METHODS

There are two different method for reversal distance to be calculated:

1.	Average True Range (ATR) – Uses the values generated by the Average True Range (ATR) indicator. The ATR is used to filter out the normal noise or 
        volatility of a financial instrument. The ATR method “automatically” determines a good reversal distance. 
        It calculates what the ATR value would be in a regular candlestick chart and then makes this value the reversal distance.
 
2.	Traditional – Uses a user-pre-defined absolute value for the box size and reversal amount. New boxes are only created when price movement 
        is larger than the pre-determined reversal amount. The upside to this method is that it is very straightforward and 
        it is easy to anticipate when and where new boxes will form. The downside is that selecting the correct box size for 
        a specific instrument will take some experimentation.

  

# USES OF POINT AND FIGURE CHARTS

As with the other, previously mentioned "noise filtering" charts, Point and Figure Charts are gaining in popularity because they do not factor in time or minor, naturally occurring price movements. Propenents of these types of charts believe that this characteristic makes it easier to spot trends and anticipate future price movements. For example, Point and Figure charts are great for visualizing  [trend lines](https://www.tradingview.com/wiki/Trend_Line "Trend Line"),  [support and resistance](https://www.tradingview.com/wiki/Support_and_Resistance "Support and Resistance")  levels and  [breakouts](https://www.tradingview.com/wiki/Breakout "Breakout").

**Trend Lines - Point and Figure Charts were originally drawn by hand on graph paper. Because of their nature, 45 degree(ish) trend lines can form naturally. These are a good way to identify the overall trend which can be beneficial on its own as well as with additional tools or indicators.**

<iframe src="https://www.tradingview.com/embed/5uVzmYrV/" frameborder="0" width="750" height="500"></iframe>
  
**Support and Resistance Levels – Frequently, when using Point and Figure Charts, trading ranges appear when bars are generated between levels of support and resistance.**

<iframe src="https://www.tradingview.com/embed/vcvGcTah/" frameborder="0" width="750" height="500"></iframe>
  
**Breakouts – Breakouts occur when boxes begin to generate in a defined direction after a period of trading within a support and resistance bound trading range.**

<iframe src="https://www.tradingview.com/embed/AeVZw70I/" frameborder="0" width="750" height="500"></iframe>

# POINT AND FIGURE CHARTS SPECIFIC OPTIONS IN TRADINGVIEW

[![PnFNew.jpg](https://wiki-pics.tradingview.com/tv/public/6/62/PnFNew.jpg)](https://www.tradingview.com/wiki/File:PnFNew.jpg)

**Up Bars**  – Change the Color and Outline of Up Bars

**Down Bars**  - Change the Color and Outline of Down Bars

**Projected Up Bars**  - Change the Color and Outline of Projected Up Bars

**Projected Down Bars**  - Change the Color and Outline of Projected Down Bars

**Source**  - Determines what data from each period will be used in calculations. Close is the default.

**Style**  – Can choose between ATR reversal distance calculation method and Traditional reversal distance calculation method

**ATR Length**  – If ATR is the selected calculation method, this value will set the ATR look-back period. 14 is the default.

**Reversal Amount**  – If Traditional is the selected calculation method, this value is the user defined reversal amount.