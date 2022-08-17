# Paired-Switchin-Trading-Model
Built a customizable pipeline for paired switching-based stock trading.

Impact: Saves computational time & is suitable for both static/dynamic datasets
# Basic Idea
1) Find 2 assets that move similarly with eachother (whether it be a negative or positive correlation)
2) Sell the 'overvalued' stock and buy the 'undervalued' stock -- A common signal to use to triger the purchase of a pair trade is to use the Price Ratio (Stock A / Stock B). If the ratio changes significantly, then you know it is time to trade. 'Significance' can be measured with standard deviation.
