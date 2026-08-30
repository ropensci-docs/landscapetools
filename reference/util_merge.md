# util_merge

Merge a primary raster with other rasters weighted by scaling factors.

## Usage

``` r
util_merge(primary_nlm, secondary_nlm, scalingfactor = 1, rescale)

# S3 method for class 'RasterLayer'
util_merge(primary_nlm, secondary_nlm, scalingfactor = 1, rescale = TRUE)
```

## Arguments

- primary_nlm:

  Primary `Raster* object`

- secondary_nlm:

  A list or stack of `Raster* object`s that are merged with the primary
  `Raster* object`

- scalingfactor:

  Weight for the secondary `Raster* objects`

- rescale:

  If `TRUE` (default), the values are rescaled between 0-1.

## Value

Rectangular matrix with values ranging from 0-1

## Examples

``` r
x <- util_merge(gradient_landscape, random_landscape)
show_landscape(x)

```
