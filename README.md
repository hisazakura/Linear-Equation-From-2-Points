# Linear-Equation-From-2-Points
A simple program to create linear equation from 2 points.
## Features
- This program is designed to work for most graphing calculators (ex. Desmos, GeoGebra)
- This program supports most number types
- This program works by arranging the numbers, NOT calculating them therefore this is not suitable for on-paper calculation as the result might be confusing for humans.
### Supported Number Types
- Natural Numbers
- Whole Numbers
- Integer (-Z for negative numbers)
- Rational numbers (a/b for fractions and use dot (.) for decimals
- Real numbers (use corresponding symbols for constants (ex. π for pi), a^(b) for powers[^1])

[^1]: View [known errors](https://github.com/hisazakura/Linear-Equation-From-2-Points/blob/master/README.md#known-errors).
### Unsupported Number Types
- Powers (only supports one digit power (ex. 2^2) but no more (ex. 2^(1/2) does not work))
## Preview
![alt text](https://github.com/hisazakura/Linear-Equation-From-2-Points/blob/master/Line%20From%20Two%20Points/preview.png?raw=true)
## Known Errors
- Problems if x1 = x2 or y1 = y2 since it will result in division by zeros
- Powers with more than one digit does not work. This is due to some graphing calculators' notation.
