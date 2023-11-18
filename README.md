# Catacombo MT4 - Expert Advisor for Algo Trading on any Currency Pairs

This is a sample code for the Catacombo MT4 Expert Advisor, developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/catacombo-mt4-review-expert-advisor-for-algo-trading-on-any-currency-pairs/).

## Overview

Catacombo MT4 is an Expert Advisor designed for algorithmic trading on any currency pairs. It uses a combination of technical indicators and predefined parameters to execute buy trades. The Expert Advisor sets a take profit and stop loss level for each trade, allowing for potential profit and risk management.

## Expert Advisor Input Parameters

- TakeProfit: Defines the take profit level in pips.
- StopLoss: Defines the stop loss level in pips.
- IndicatorPeriod: Defines the period for indicator calculation.

## Expert Advisor Initialization Function

The OnInit() function is called during the Expert Advisor initialization process. It is used for any necessary initialization code. In this sample code, no specific initialization is required.

## Expert Advisor Start Function

The OnTick() function is the main function that is called for each tick. It contains the trading logic for placing buy trades. Here's a breakdown of the code:

1. The current bid and ask prices are retrieved using the SymbolInfoDouble() function.
2. The stop loss and take profit prices are calculated based on the defined parameters and the current prices.
3. The OrderSend() function is used to place a buy trade with the specified parameters.
4. If the trade is successfully placed, a message is printed to the terminal. Otherwise, an error message with the error code is printed.

## Expert Advisor Deinitialization Function

The OnDeinit() function is called when the Expert Advisor is being deinitialized. It can be used for any necessary deinitialization code. In this sample code, no specific deinitialization is required.

## Expert Advisor Error Handling Function

The OnTradeError() function is called when there is an error in a trade operation. It can be used to handle trade errors and perform any necessary actions. In this sample code, the error message and result are printed to the terminal.

## Expert Advisor Stop Function

The OnStop() function is called when the Expert Advisor is stopped. It can be used for any necessary stop code. In this sample code, no specific stop code is required.

Please note that this is a sample code and may require modifications or additional code to fully function as intended.
