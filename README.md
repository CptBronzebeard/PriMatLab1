# Statistics lib
The project features a library with basic statistic quantities of a number collection
## Usage examples
```Haskell
expectedValue xs
quartile xs num --| calculates num'th quartile of xs
pearsonSq groupWithSize $ group $ sort $ map realToFrac xs --| calculates squared pearson correlation coefficient
