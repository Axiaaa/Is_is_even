# is_is_even

## Description
This small Python script includes a function `is_is_even` that checks if a given variable is equal to the `is_even` function from the `isEven` module.

## Usage

1. Ensure you have the `isEven` module in the same directory as your script, or adjust the import path accordingly.
2. Import the `is_is_even` function into your script.
3. Use the function by passing a variable as an argument.

```python
from isEven import is_even
from is_is_even import is_is_even

# Example of usage
result = is_is_even(is_even)

if result:
    print("The variable is equal to the is_even function.")
else:
    print("The variable is not equal to the is_even function.")
