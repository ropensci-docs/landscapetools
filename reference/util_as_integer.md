# util_as_integer

Coerces raster values to integers

## Usage

``` r
util_as_integer(x)

# S3 method for class 'RasterLayer'
util_as_integer(x)
```

## Arguments

- x:

  raster

## Value

RasterLayer

## Details

Coerces raster values to integers, which is sometimes needed if you want
further methods that rely on integer values.

## Examples

``` r
# Mode 1
util_as_integer(fractal_landscape)
#> class      : RasterLayer 
#> dimensions : 150, 150, 22500  (nrow, ncol, ncell)
#> resolution : 1, 1  (x, y)
#> extent     : 0, 150, 0, 150  (xmin, xmax, ymin, ymax)
#> crs        : NA 
#> source     : memory
#> names      : layer 
#> values     : 1, 22500  (min, max)
#> 

```
