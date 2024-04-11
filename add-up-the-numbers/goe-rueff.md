# [Joe Rueff](https://edabit.com/user/ecEjnmMiKM85wd8SF)

```js
function calcAge(age) {
  return age * 365;
}
```

## Strategy

This involves recognizing the goal of calculating the approximate number of days
lived based on the given age

## Implementation

This function takes an age as input and calculates the approximate number of
days lived by multiplying the age by 365, representing the number of days in a
year. The result is then returned.

**Math.floor(`number`)**: This function rounds a floating point number down to
the nearest integer

**parenthesis**: As the normal order of operations would not work, ldq used
parenthesis to group the mathematical operators differently.

**+, /, %, +**: these operators combine the argument with hard-coded values to
calculate the correct solution.

## Possible Refactors

Refactoring options for the calcAge function include using a named constant for
the number of days in a year and adding parameter validation to ensure the input
is a valid number. These enhancements aim to improve the function's readability,
robustness, and maintainability.
