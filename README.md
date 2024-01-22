# Inside Candle EA ReadMe

## Description
The Inside Candle EA is a trading robot developed by the Forex Robot Easy Team. It is designed to identify and trade the breakout of an inside candle pattern in the forex market. This expert advisor (EA) can be used on the MetaTrader 5 platform.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Inside Candle EA Review](https://forexroboteasy.com/forex-robot-review/inside-candle-ea-review-forex-software-for-breakout-trading/). Kindly note that ForexRobotEasy is not the official developer of this product. We only provide the sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Installation
To use the Inside Candle EA, follow the steps below:

1. Download and install the MetaTrader 5 platform from [MetaQuotes](https://www.metatrader5.com/en/download).
2. Open the MetaTrader 5 platform and navigate to the 'File' menu.
3. Select 'Open Data Folder' to open the data folder.
4. In the data folder, locate the 'MQL5' folder and open it.
5. Inside the 'MQL5' folder, locate the 'Experts' folder and open it.
6. Copy the Inside Candle EA code provided in this ReadMe file.
7. Create a new file in the 'Experts' folder and paste the copied code.
8. Save the file with a suitable name, such as 'InsideCandleEA.mq5'.
9. Restart the MetaTrader 5 platform.

## Usage
To use the Inside Candle EA, follow the steps below:

1. Open the MetaTrader 5 platform and select the desired currency pair.
2. Drag and drop the Inside Candle EA from the Navigator window onto the chart of the selected currency pair.
3. In the 'Inputs' tab of the Expert Advisor properties, you can adjust the take profit and stop loss levels.
4. Click the 'OK' button to apply the settings.

The Inside Candle EA will now automatically monitor the selected currency pair and place trades based on the breakout of an inside candle pattern.

## Functionality
The Inside Candle EA performs the following functions:

- **OnInit**: This function is called during the initialization of the EA. It checks if trading is allowed on the account and sets the take profit and stop loss levels.

- **OnDeinit**: This function is called during the deinitialization of the EA. It performs any necessary cleanup.

- **OnTick**: This function is called on every tick of the selected currency pair. It checks if an inside candle pattern exists and places a trade based on the breakout direction.

- **IsInsideCandle**: This function checks if an inside candle pattern exists. It returns true if an inside candle pattern is found, otherwise false.

- **GetBreakoutDirection**: This function determines the breakout direction. It returns the breakout direction (up, down, or none).

- **BuyOrder**: This function is called to place a buy order. It implements the necessary logic to execute a buy trade.

- **SellOrder**: This function is called to place a sell order. It implements the necessary logic to execute a sell trade.

## Customization
To customize the Inside Candle EA, you can modify the following constants:

- **TAKE_PROFIT**: The take profit level in pips.
- **STOP_LOSS**: The stop loss level in pips.

You can adjust these constants according to your trading strategy and risk tolerance.

## Disclaimer
Kindly note that ForexRobotEasy is not the official developer of the Inside Candle EA. We provide the sample code as a demonstration of how this product can potentially work. To find the official developer of this product, please refer to MQL5. Trading the forex market involves risk, and it is important to thoroughly test any trading robot before using it with real money. ForexRobotEasy is not responsible for any losses incurred from using this code.

For detailed reviews and trading results of the Inside Candle EA, please visit [Forex Robot Easy - Inside Candle EA Review](https://forexroboteasy.com/forex-robot-review/inside-candle-ea-review-forex-software-for-breakout-trading/).
