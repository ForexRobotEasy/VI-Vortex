# VI Vortex

VI Vortex is an advanced Forex tool designed to identify trend reversals and spot potential trading opportunities. It calculates the VI Trend and VI- Line indicators based on the high and low prices of the financial instrument.

## Indicator Parameters

- PeriodVI: The period used for calculating the VI indicators. Default value is 14.

## Indicator Buffers

- VITrendBuffer: Stores the values of the VI Trend indicator.
- VILineBuffer: Stores the values of the VI- Line indicator.

## Indicator Initialization

The indicator buffers are mapped and labeled in the OnInit() function. The short name of the indicator is set to 'VI Vortex'.

## Indicator Calculation

The OnCalculate() function is responsible for calculating the VI Trend and VI- Line indicators. The calculation is performed for each bar of the chart.

1. Check if there are enough bars to perform the calculation.
2. Loop through the bars from prev_calculated to rates_total.
3. Calculate the VI Trend by subtracting the moving average of the low prices from the moving average of the high prices.
4. Calculate the VI- Line by taking the moving average of the VI Trend values.
5. Store the calculated values in the respective indicator buffers.
6. Return the value of rates_total to indicate the number of calculated bars for the next call.

## Product Description

VI Vortex is an advanced Forex tool developed by the Forex Robot Easy Team. It is designed to assist traders in identifying trend reversals and potential trading opportunities. The indicator calculates two indicators, namely the VI Trend and VI- Line, based on the high and low prices of the financial instrument.

The VI Trend indicator represents the difference between the moving averages of the high and low prices. It helps to identify the strength and direction of the current trend.

The VI- Line indicator is derived from the VI Trend values. It represents the smoothed moving average of the VI Trend. It helps to filter out noise and provide a clearer view of the trend.

This product is not developed by ForexRobotEasy. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/vi-vortex-review-advanced-forex-tool-for-trend-spotting/).
