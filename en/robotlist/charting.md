# Charting

## Function:

Pushes prices up or down to develop the desired trend. Pending orders will be placed according to the frequency and price of orders.

## Operations:

**Upper Limit:** Highest price allowed for charting.\
\
**Lower Limit:** Lowest price allowed for charting.\
\
**Spread Size:** Percentage difference between best bid and best ask.\
\
**Spread per Level:** Percentage change in price between each tranche.\
\
**Quantity of Buy Orders:** Number of buy orders to be maintained at each tranche. Actual size will be randomized within a 30% range from quantity indicated.\
\
**Quantity of Sell Orders:** Number of sell orders to be maintained at each tranche. Actual size will be randomized within a 30% range from quantity indicated.\
\
**Max Quantity per Order:** Maximum quantity each order will fulfill.\
\
**Price Precision:** Decimal precision of price.\
\
**Total Daily Number of Orders:** Maximum number of orders allowed in a day.\
\
**Index Follow:** When this function is enabled, the charting robot will work with reference to the trends of the main market (like BTC, ETH, etc).

## Start/Stop:

Click the start button and the robot will start working immediately. Click the stop button and the robot will stop immediately.

## Risk control:

If other users participate in the transaction, causing the price to break out of the set range, the robot will automatically stop working.

## Notice:

When the robot encounters a large order from the user account during running, The robot will identify it as a resistance zone set by the user and will not trade with these orders. Definition of large order: (order amount > 5 times of set quantity of buy and sell orders)
