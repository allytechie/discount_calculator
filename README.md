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

# Examples
## With Discount

Enter original price: 100
Enter discount percentage: 25
Final price after 25% discount: 75.00
Without Discount

Enter original price: 50  
Enter discount percentage: 15
No discount applied. Price: 50.00
## Requirements
Python 3

## Running the Program

python discount.py
## Notes
Simple implementation
Handles basic cases
