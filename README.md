# Discount Calculator

## Description
A Python program that calculates the final price after applying a discount (if eligible). Only applies discounts of 20% or higher.

## Features
- Calculates discounted prices
- Simple user input/output
- Clear conditional logic

### Function Definition
```python
def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        return price - (discount_percent / 100 * price)
    return price

