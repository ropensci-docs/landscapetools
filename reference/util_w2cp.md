# util_w2cp

Convert a list of category weighting into a 1D array of cumulative
proportions.

## Usage

``` r
util_w2cp(weighting)
```

## Arguments

- weighting:

  A list of numeric values

## Value

Rectangular matrix with values ranging from 0-1

## Examples

``` r
util_w2cp(c(0.2, 0.4, 0.6, 0.9))
#> [1] 0.0952381 0.2857143 0.5714286 1.0000000

```
