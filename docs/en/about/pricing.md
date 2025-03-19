---
title: ExinOne Pricing Rules
layout: article
---

# ExinOne Pricing Rules

ExinOne adopts an efficient One-Step service model, directly connecting to APIs of exchanges with the best depth and liquidity across the network, ensuring your transactions are executed quickly.

## Fee Details

### Stablecoin Version Exchange
- **Rate**: 0.05%
- **EPC Deduction**: ✅ Supported
- **Example**: Exchange between different versions of USDT, only 0.05% handling fee is charged

### Crypto Trading & Limit orderss
- **Standard Rate**: 0.2%
- **EPC Deduction**: ✅ Supported
- **Market/Limit Orders**: Same rate of 0.2% for both
- **Example**: For ETH/USDT trading, the fee is 0.2% of the transaction amount

### Special Trading Pairs
- **USDC/USDT**: 0.1% fee, EPC deduction supported

### BOX Trading Rules
- **Swap Buy BOX**: 0.2% fee, ✅ EPC deduction supported
- **Swap Sell BOX**: 1% fee, ❌ EPC deduction not supported
  - Note: Selling fees are dynamically adjusted between 0.2%-1% based on market conditions
- **Spot & Limit Orders for BOX**: 0.2% fee across the board, ✅ EPC deduction supported

### Multi-Step Transaction Rules
- **Charging Principle**: Only charged once, with the highest handling fee prevailing
- **EPC Deduction Rule**: If any step doesn't support EPC deduction, the entire path won't support it
- **Example**: BOX → USDT → USDC path
  - BOX → USDT: 1% fee, EPC deduction not supported
  - USDT → USDC: 0.1% fee, EPC deduction supported
  - Final charge: 1% fee, EPC deduction not supported

### Other Services
- **Auto Invest Plan**: The feature itself is free. Transactions are completed through Swap and charged according to Swap rules. This means buying tokens through Auto Invest Plan costs the same as buying directly through Swap - Auto Invest simply automates the process without additional fees.

## EPC Fee Point Card

- **Exchange Ratio**: 100 EPC = $1 fee deduction
- **Usage Method**: Must be deposited to your ExinOne EPC account to be used (located in the EPC account in the upper left corner profile). If EPC balance is insufficient to cover the transaction fee, EPC deduction cannot be applied
- **Detailed Introduction**: See [EPC Introduction](/features/epc)

---

Thank you for your support of ExinOne! If you have any questions, feel free to contact the ExinOne bot at any time.

*Note: ExinOne reserves the right to adjust services and rates according to market conditions. Please refer to the platform's real-time display for the most current information.*
