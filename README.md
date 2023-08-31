# numequate
A Python Mathematics Library.

# Numequate Math Functions Library

The `numequate` library provides basic mathematical operations for addition, subtraction, multiplication, division, and exponentiation.

## Installation

You can install the library using pip:

```bash
pip install numequate
```

## Usage

```python
from numequate.base import add, subtract, multiply, divide, power

result = add(5, 3)       # Returns 8
result = subtract(10, 4) # Returns 6
result = multiply(2, 6)  # Returns 12
result = divide(10, 2)   # Returns 5
result = power(3, 4)     # Returns 81
```

## Functions

### add(a, b)
Adds two numbers a and b and returns the result.

### subtract(a, b)
Subtracts the number b from a and returns the result.

### multiply(a, b)
Multiplies two numbers a and b and returns the result.

### divide(a, b)
Divides the number a by b and returns the result. Raises a ValueError if b is 0.

### power(base, exponent)
Calculates the result of raising the base to the power of exponent.

### clamp(value, min_value, max_value)
Clamps a value within the specified range.

### map_range(value, in_min, in_max, out_min, out_max)
Maps a value from one range to another.

### lerp(start, end, alpha)
Performs linear interpolation between two values.

### math(expression)
Calculates the provided numbers and content.

### factorial(n)
Finds the factorial of a chosen number.

## License
This library is provided under the MIT License. Feel free to use and modify it according to your needs.
