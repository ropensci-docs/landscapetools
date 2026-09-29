# util_writeESRI

Export raster objects as ESRI ascii files.

## Usage

``` r
util_writeESRI(x, filepath)

# S3 method for class 'RasterLayer'
util_writeESRI(x, filepath)
```

## Arguments

- x:

  Raster\* object

- filepath:

  path where to write the raster to file

## Value

No return value, called for the side effect of writing an ESRI ASCII
raster file to `filepath`.

## Details

[`raster::writeRaster`](https://rspatial.github.io/terra/reference/writeRaster.html)
or `SDMTools::write.asc` both export files that are recognised by most
GIS software, nevertheless they both have UNIX linebreaks. Some
proprietary software (like SPIP for example) require an exact 1:1
replica of the output of ESRI's ArcMap, which as a Windows software has
no carriage returns at the end of each line. `util_writeESRI` should
therefore only be used if you need this, otherwise
[`raster::writeRaster`](https://rspatial.github.io/terra/reference/writeRaster.html)
is the better fit for exporting raster data in R.

## Examples

``` r
filepath <- tempfile(fileext = ".asc")
util_writeESRI(gradient_landscape, filepath)
unlink(filepath)
```
