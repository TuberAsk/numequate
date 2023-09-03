# Numequate Math Functions Library

The `numequate` library provides basic mathematical operations for addition, subtraction, multiplication, division, and exponentiation.

## Installation

You can install the library using pip:

```bash
pip install numequate
```
## About

The `numequate` library is a collection of basic mathematical operations for Python. It's designed to simplify common mathematical tasks in your Python projects. Whether you need to perform addition, subtraction, multiplication, division, or exponentiation, `numequate` has you covered.

### Features

- **Simplicity:** The library provides straightforward functions for essential math operations.
- **Error Handling:** It includes error handling to ensure safe division and handling of edge cases.
- **Additional Functions:** In addition to basic operations, `numequate` offers extra math functions, including factorial, Fibonacci, and GCD calculations.
- **Range Manipulation:** Functions like `clamp` and `map_range` help you manage values within specific ranges.
- **Interpolation:** Perform linear interpolation with the `lerp` function.
- **Math Expressions:** Evaluate mathematical expressions with the `math` function.

## Documentation

For detailed information on how to use each function and examples, please refer to the [documentation](https://github.com/TuberAsk/numequate/wiki).


## Usage

```python
from numequate.base import add, subtract, multiply, divide, power

resultAdd = add(5, 3)       # Returns 8
#result = subtract(10, 4) # Returns 6
#result = multiply(2, 6)  # Returns 12
#result = divide(10, 2)   # Returns 5
resultPower = power(3, 4)     # Returns 81

print(resultAdd, resultPower)
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

### fibonacci(n)
Calculate the nth Fibonacci number.

### gcd(a, b)
Calculate the greatest common divisor (GCD) of two non-negative integers a and b.

## License
This library is provided under the BSD License. Feel free to use and modify it according to your needs.
