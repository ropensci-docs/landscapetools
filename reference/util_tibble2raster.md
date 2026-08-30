# Converts tibble data into a raster

Writes spatial tibble values into a raster.

## Usage

``` r
util_tibble2raster(x)

util_tibble2raster(x)
```

## Arguments

- x:

  a tibble

## Value

Raster\* object

## Details

Writes tiles with coordinates from a tibble into a raster. Resolution is
set to 1 and the extent will be c(0, max(x), 0, max(y)).

You can directly convert back the result from 'util_raster2tibble()'
without problems. If you have altered the coordinates or otherwise
played with the data, be careful while using this function.

## Examples

``` r
maptib <- util_raster2tibble(random_landscape)
mapras <- util_tibble2raster(maptib)
all.equal(random_landscape, mapras)
#> [1] TRUE
```
