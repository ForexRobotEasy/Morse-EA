# Morse EA

Morse EA is a powerful forex tool developed by the Forex Robot Easy Team. It is designed for both scalpers and trend traders. This code provides the implementation of the Morse algorithm to filter entry points and includes predefined rules for trade exit conditions.

## Input Parameters
1. `mode` - Select the trading mode (0: scalping, 1: trend trading)
2. `ema1Period` - Period for the first exponential moving average (EMA)
3. `ema2Period` - Period for the second exponential moving average (EMA)
4. `riskPercentage` - Percentage of account balance to risk per trade
5. `stopLossPips` - Stop loss in pips
6. `takeProfitPips` - Take profit in pips

## Global Variables
1. `lotSize` - Stores the calculated lot size based on the risk percentage
2. `currentMode` - Stores the current trading mode
3. `prevMode` - Stores the previous trading mode
4. `ema1Handle` - Stores the handle of the first EMA indicator
5. `ema2Handle` - Stores the handle of the second EMA indicator

## Indicator Initialization Function
The `OnInit` function is called during the initialization of the custom indicator. It sets initial values for the global variables, calculates the lot size based on the risk percentage, and initializes the EMA indicators.

## Indicator Deinitialization Function
The `OnDeinit` function is called when the custom indicator is being deinitialized. It clears the EMA indicators.

## Indicator Iteration Function
The `OnTick` function is called on each tick and performs the main trading logic. It checks for a change in the trading mode and recalculates the lot size if necessary. It then calculates the values of the EMAs, checks for the entry condition based on the Morse algorithm, and checks for the exit condition based on the predefined rules. Finally, it executes trades or closes existing trades accordingly.

## Calculate Lot Size
The `CalculateLotSize` function calculates the lot size based on the risk percentage. It uses the account balance, risk amount, tick value, and stop loss price to calculate the lot size.

## Morse Algorithm
The `MorseAlgorithm` function is a placeholder and needs to be replaced with the actual implementation of the Morse algorithm. It filters entry points based on the Morse algorithm.

## Check Exit Rules
The `CheckExitRules` function is a placeholder and needs to be replaced with the actual implementation of the exit rules. It checks for predefined rules to determine if trades should be closed.

## Execute Scalping Trade
The `ExecuteScalpingTrade` function is a placeholder and needs to be replaced with the actual implementation of the scalping trade execution. It executes a scalping trade based on the entry conditions.

## Execute Trend Trading Trade
The `ExecuteTrendTrade` function is a placeholder and needs to be replaced with the actual implementation of the trend trading trade execution. It executes a trend trading trade based on the entry conditions.

## Close All Trades
The `CloseAllTrades` function is a placeholder and needs to be replaced with the actual implementation of closing all existing trades.

---

For detailed reviews and trading results of this product, visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/morse-ea-review-powerful-forex-tool-for-scalpers-trend-lovers/). Please note that ForexRobotEasy is not the official developer of this product. They only provide sample code that can work as described in this product. To find the official developer of this product, use MQL5.
