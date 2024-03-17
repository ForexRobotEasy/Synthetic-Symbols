# Synthetic Symbols

## Overview
The Synthetic Symbols program allows traders to create custom synthetic symbols by combining terminal symbols or custom symbols using mathematical operations. This code is provided as a sample implementation and should be used as a reference for understanding how synthetic symbols can be created.

## Developer Information
- Developer: Forex Robot Easy Team
- Developer's Site: [forexroboteasy.com](https://forexroboteasy.com)

## Libraries Used
- Trade.mqh
- MqlRates.mqh

## Class: CSyntheticSymbol
This class represents a synthetic symbol and contains the necessary properties and methods to calculate its value.

### Properties
- `m_symbol`: Name of the synthetic symbol
- `m_formula`: Formula for calculating the synthetic symbol
- `m_digits`: Number of digits in the synthetic symbol
- `m_scaleFactor`: Scaling factor for the synthetic symbol

### Constructor
- `CSyntheticSymbol(string symbol, string formula, int digits, double scaleFactor)`: Initializes the synthetic symbol with the given properties.

### Method: CalculateValue()
This method calculates the value of the synthetic symbol based on its formula and other properties.

### Usage Example
```cpp
CSyntheticSymbol syntheticSymbol1('SYMBOL1', 'addition', 5, 1.0);
double value1 = syntheticSymbol1.CalculateValue();
```

## Function: CreateSyntheticSymbols()
This function creates custom synthetic symbols by instantiating the CSyntheticSymbol class with different properties, calculates their values, and prints them.

## Entry Point: OnStart()
This is the entry point of the program, which calls the CreateSyntheticSymbols() function.

## Product Description
The Synthetic Symbols program, developed by the Forex Robot Easy Team, allows traders to create custom synthetic symbols by combining terminal symbols or custom symbols using mathematical operations. With this program, traders can unleash the full potential of their forex trading strategies by creating unique synthetic symbols that can be used for analysis and trading.

By using the provided code as a reference, traders can understand how synthetic symbols can be created and calculate their values based on different formulas. The program supports basic mathematical operations such as addition, subtraction, multiplication, and division.

Please note that Forex Robot Easy is not the official developer of this product. We only provide this sample code to demonstrate how synthetic symbols can be implemented. To find the official developer and obtain the full version of this product, please refer to the [MQL5 website](https://www.mql5.com). 

For detailed reviews and trading results of this product, visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/synthetic-symbols-review-unleashing-forex-trading-potential/).
