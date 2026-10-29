# Binarize continuous raster values

Classify continuous raster values into binary map cells based upon given
break(`s`).

## Usage

``` r
util_binarize(x, breaks)

# S3 method for class 'RasterLayer'
util_binarize(x, breaks)
```

## Arguments

- x:

  Raster\* object

- breaks:

  Vector with one or more break percentages

## Value

RasterLayer / RasterBrick

## Details

Breaks are considered to be habitat percentages (`p`). If more than one
percentage is given multiple layers are written in the same brick.

## Examples

``` r
breaks <- c(0.3, 0.5)
binary_maps <- util_binarize(gradient_landscape, breaks)
```
