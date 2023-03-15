# DEX Charting

## Function:

It is used to make sideways in a set price range and create trading volume. Furthermore, increase the activity of the market and maintain the trend of the candlestick chart of the DEX.

## Operations:

**Price range:** Fill in the numbers from low to high to control the line maintenance range. When the set range is exceeded, the robot will try its best to run within the set range.\
\
**Volume per deal:** Fill in the numbers from low to high, the trading volume of each transaction will be a random range, the range can be set to a larger range to ensure that the transaction record looks like real users transaction.\
\
**Time interval:** The time interval for each transaction. Due to the high cost of dex service fees and gas fees, it is recommended to fill in at least 30 seconds.\
\
**Trend direction:** When the charting robot operates, it will defaultly refer to the price trend direction of the overall market. This parameter can further adjust the direction of the price trend.

## Start/Stop:

Click the start button and the robot will start working immediately. If transaction fails due to any reasons or the price difference between the buy and sell orders is extremely small which caused market stuck, the robot will pause work.
