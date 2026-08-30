# Converts raster data into tibble

Writes spatial raster values into tibble and adds coordinates.

## Usage

``` r
util_raster2tibble(x, format = "long")

util_raster2tibble(x, format = "long")
```

## Arguments

- x:

  Raster\* object

- format:

  Either *"long"* (default) or *"wide"* output for the resulting tibble

## Value

a tibble

## Details

You will loose any resolution, extent or reference system. The output is
raw tiles.

## Examples

``` r
maptib <- util_raster2tibble(fractal_landscape)
# \donttest{
library(ggplot2)
ggplot(maptib, aes(x,y)) +
    coord_fixed() +
    geom_raster(aes(fill = z))

# }
```
