# Coupon Collector Calculator

This repository hosts a web-based Coupon Collector Calculator that helps users estimate the expected number of tries required to collect a full set of coupons under various probabilities. It includes functionality to handle both equal and unequal coupon probabilities.

## Features

- **Equal Probabilities**:  
  Given a drop rate, a number of coupons, and the number of rolls per attempt, this tool calculates the expected number of tries to collect all coupons.

- **Unequal Probabilities**:  
  For more complex scenarios where each coupon does not have the same drop probability, simply enter the number of distinct coupons (N) and their respective probabilities. The tool will then calculate the expected number of tries to collect them all.

## How to Use

1. **Equal Probabilities**:
   - Enter the drop rate (as a decimal or fraction, e.g. `0.1` or `1/15`).
   - Enter the number of coupons to collect.
   - Enter the number of rolls per attempt (e.g. `1`).
   - Click "Calculate" to see the expected number of tries.

2. **Unequal Probabilities**:
   - Enter the number of distinct coupons (N).
   - For each coupon, enter its probability (decimal or fraction form).
   - Ensure probabilities sum to 1.
   - Click "Calculate (Unequal)" to see the result.

## License

This project is available under the [MIT License](LICENSE).