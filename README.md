# Prop Genius ReadMe

Prop Genius is a trading expert advisor developed by the Forex Robot Easy Team. It is designed to provide advanced trading features and techniques for prop firms engaged in forex trading. This ReadMe file provides a brief overview of the code and its functionalities.

## Stealth Mode

The Stealth Mode function implemented in the code allows traders to prevent copy trading by opening trades at different timings compared to other accounts. By enabling Stealth Mode, traders can maintain a level of privacy and avoid being copied by other traders.

To enable Stealth Mode, add the necessary code within the `StealthMode()` function.

## Soft Martingale Loss Management

The Soft Martingale technique is used to effectively manage losses during trading. By implementing this technique, traders can minimize potential losses and safeguard their trading capital. The SoftMartingale() function in the code is responsible for managing losses using this technique.

To customize the Soft Martingale technique for your trading strategy, add the relevant code within the `SoftMartingale()` function.

## Overnight Trading

Prop Genius allows traders to keep trades open overnight and over weekends, providing the flexibility to take advantage of potential market movements during extended trading hours. The `EnableOvernightTrading()` function in the code enables this feature.

To enable overnight trading, add the necessary code within the `EnableOvernightTrading()` function.

## Trading Logic

The main trading logic is executed within the `OnTick()` function. Before executing the trading logic, the code checks if Stealth Mode is enabled. If Stealth Mode is enabled, the trading logic, including Soft Martingale and overnight trading, is executed.

To customize the trading logic based on recommended forex pairs, such as XAUUSD, EURUSD, EURCAD, and AUDCHF, add the relevant code within the `OnTick()` function.

## Product Description

Prop Genius is an expert advisor developed by the Forex Robot Easy Team for prop firms engaged in forex trading. With advanced features such as Stealth Mode, Soft Martingale loss management, and overnight trading, Prop Genius provides traders with the tools necessary to enhance their trading strategies and achieve better results.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of Prop Genius, please refer to the MQL5 website.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com/forex-robot-review/prop-genius-review-expert-advisor-for-prop-firm-forex-trading](https://forexroboteasy.com/forex-robot-review/prop-genius-review-expert-advisor-for-prop-firm-forex-trading/).

## Disclaimer

Please note that the performance of Prop Genius may vary based on market conditions and individual trading strategies. It is important to thoroughly test and validate the expert advisor before using it with real funds. The Forex Robot Easy Team and the official developer of Prop Genius cannot be held responsible for any losses incurred while using this software.
