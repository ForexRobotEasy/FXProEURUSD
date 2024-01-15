# Forex Robot Easy Team
[forexroboteasy.com](https://forexroboteasy.com)

This is a simple Expert Advisor (EA) code that is designed to execute trades on the EURUSD currency pair based on a basic strategy. The strategy involves comparing the current price of EURUSD to its average price over the last 10 bars. If the current price is higher than the average price, a buy trade is executed. If the current price is lower than the average price, a sell trade is executed.

## Input Parameters
- RiskLevel: This parameter determines the risk level for each trade. The default value is 0.01, which means 1% of the account balance will be risked for each trade.
- MaxDrawdownCautious: This parameter sets the maximum drawdown for the cautious strategy. If the current risk is within this drawdown limit, a buy trade will be executed.
- MaxDrawdownAdventurous: This parameter sets the maximum drawdown for the adventurous strategy. If the current risk is within this drawdown limit, a sell trade will be executed.

## How it Works
1. The EA first retrieves the current high and low prices of the EURUSD currency pair.
2. It then calculates the average price of EURUSD over the last 10 bars by summing up the closing prices and dividing by 10.
3. If the current high price is higher than the average price, the EA calculates the risk for the current trade based on the RiskLevel parameter and the account balance.
4. If the calculated risk is within the maximum drawdown limit for the cautious strategy, a buy trade is executed with the calculated risk.
5. If the current low price is lower than the average price, the EA calculates the risk for the current trade based on the RiskLevel parameter and the account balance.
6. If the calculated risk is within the maximum drawdown limit for the adventurous strategy, a sell trade is executed with the calculated risk.

## Product Description
This code serves as a sample implementation of a basic trading strategy for the EURUSD currency pair. It is not the official product developed by Forex Robot Easy Team, but it demonstrates how a trading strategy can be coded using the MQL4 language.

The code can be used as a starting point for developing a more sophisticated EA by adding additional trading functions and refining the strategy. It is important to note that the performance and profitability of this code may vary depending on market conditions and other factors.

For detailed reviews and trading results of a similar product, you can visit [this link](https://forexroboteasy.com/forex-robot-review/fxproeurusd-review-simple-setup-ideal-for-expert-advisors/). Please note that Forex Robot Easy is not the official developer of that specific product. To find the official developer, it is recommended to use the MQL5 platform.
