# theme_nlm

Opinionated ggplot2 theme to visualize NLM raster.

## Usage

``` r
theme_nlm(
  base_family = NULL,
  base_size = 11.5,
  plot_title_family = base_family,
  plot_title_size = 18,
  plot_title_face = "bold",
  plot_title_margin = 10,
  subtitle_family = NULL,
  subtitle_size = 13,
  subtitle_face = "plain",
  subtitle_margin = 15,
  strip_text_family = base_family,
  strip_text_size = 12,
  strip_text_face = "plain",
  strip.background = "grey80",
  caption_family = NULL,
  caption_size = 9,
  caption_face = "plain",
  caption_margin = 10,
  axis_text_size = base_size,
  axis_title_family = base_family,
  axis_title_size = 9,
  axis_title_face = "plain",
  axis_title_just = "rt",
  plot_margin = ggplot2::unit(c(0, 0, 0, 0), "lines"),
  grid_col = "#cccccc",
  grid = TRUE,
  axis_col = "#cccccc",
  axis = FALSE,
  ticks = FALSE,
  legend_title = "Z",
  legend_labels = NULL,
  legend_text_size = 8,
  legend_title_size = 10,
  ratio = 1,
  viridis_scale = "D",
  ...
)

theme_nlm_discrete(
  base_family = NULL,
  base_size = 11.5,
  plot_title_family = base_family,
  plot_title_size = 18,
  plot_title_face = "bold",
  plot_title_margin = 10,
  subtitle_family = NULL,
  subtitle_size = 13,
  subtitle_face = "plain",
  subtitle_margin = 15,
  strip_text_family = base_family,
  strip_text_size = 12,
  strip_text_face = "plain",
  strip.background = "grey80",
  caption_family = NULL,
  caption_size = 9,
  caption_face = "plain",
  caption_margin = 10,
  axis_text_size = base_size,
  axis_title_family = base_family,
  axis_title_size = 9,
  axis_title_face = "plain",
  axis_title_just = "rt",
  plot_margin = ggplot2::unit(c(0, 0, 0, 0), "lines"),
  grid_col = "#cccccc",
  grid = TRUE,
  axis_col = "#cccccc",
  axis = FALSE,
  ticks = FALSE,
  legend_title = "Z",
  legend_labels = NULL,
  legend_text_size = 8,
  legend_title_size = 10,
  ratio = 1,
  viridis_scale = "D",
  ...
)

theme_nlm_grey(
  base_family = NULL,
  base_size = 11.5,
  plot_title_family = base_family,
  plot_title_size = 18,
  plot_title_face = "bold",
  plot_title_margin = 10,
  subtitle_family = NULL,
  subtitle_size = 13,
  subtitle_face = "plain",
  subtitle_margin = 15,
  strip_text_family = base_family,
  strip_text_size = 12,
  strip_text_face = "plain",
  strip.background = "grey80",
  caption_family = NULL,
  caption_size = 9,
  caption_face = "plain",
  caption_margin = 10,
  axis_text_size = base_size,
  axis_title_family = base_family,
  axis_title_size = 9,
  axis_title_face = "plain",
  axis_title_just = "rt",
  plot_margin = ggplot2::unit(c(0, 0, 0, 0), "lines"),
  grid_col = "#cccccc",
  grid = TRUE,
  axis_col = "#cccccc",
  axis = FALSE,
  ticks = FALSE,
  legend_title = "Z",
  legend_labels = NULL,
  legend_text_size = 8,
  legend_title_size = 10,
  ratio = 1,
  ...
)

theme_nlm_grey_discrete(
  base_family = NULL,
  base_size = 11.5,
  plot_title_family = base_family,
  plot_title_size = 18,
  plot_title_face = "bold",
  plot_title_margin = 10,
  subtitle_family = NULL,
  subtitle_size = 13,
  subtitle_face = "plain",
  subtitle_margin = 15,
  strip_text_family = base_family,
  strip_text_size = 12,
  strip_text_face = "plain",
  strip.background = "grey80",
  caption_family = NULL,
  caption_size = 9,
  caption_face = "plain",
  caption_margin = 10,
  axis_text_size = base_size,
  axis_title_family = base_family,
  axis_title_size = 9,
  axis_title_face = "plain",
  axis_title_just = "rt",
  plot_margin = ggplot2::unit(c(0, 0, 0, 0), "lines"),
  grid_col = "#cccccc",
  grid = TRUE,
  axis_col = "#cccccc",
  axis = FALSE,
  ticks = FALSE,
  legend_title = "Z",
  legend_labels = NULL,
  legend_text_size = 8,
  legend_title_size = 10,
  ratio = 1,
  ...
)

theme_facetplot(
  base_family = NULL,
  base_size = 11.5,
  plot_title_family = base_family,
  plot_title_size = 18,
  plot_title_face = "bold",
  plot_title_margin = 10,
  subtitle_family = NULL,
  subtitle_size = 13,
  subtitle_face = "plain",
  subtitle_margin = 15,
  strip.background = "grey80",
  caption_family = NULL,
  caption_size = 9,
  caption_face = "plain",
  caption_margin = 10,
  ratio = 1,
  viridis_scale = "D",
  ...
)

theme_facetplot_discrete(
  base_family = NULL,
  base_size = 11.5,
  plot_title_family = base_family,
  plot_title_size = 18,
  plot_title_face = "bold",
  plot_title_margin = 10,
  subtitle_family = NULL,
  subtitle_size = 13,
  subtitle_face = "plain",
  subtitle_margin = 15,
  strip.background = "grey80",
  caption_family = NULL,
  caption_size = 9,
  caption_face = "plain",
  caption_margin = 10,
  ratio = 1,
  viridis_scale = "D",
  ...
)
```

## Arguments

- base_family:

  base font family size

- base_size:

  base font size

- plot_title_family:

  plot title family

- plot_title_size:

  plot title size

- plot_title_face:

  plot title face

- plot_title_margin:

  plot title ggplot2::margin

- subtitle_family:

  plot subtitle family

- subtitle_size:

  plot subtitle size

- subtitle_face:

  plot subtitle face

- subtitle_margin:

  plot subtitle ggplot2::margin bottom (single numeric value)

- strip_text_family:

  facet facet label font family

- strip_text_size:

  facet label font family, face and size

- strip_text_face:

  facet facet label font face

- strip.background:

  strip background

- caption_family:

  plot caption family

- caption_size:

  plot caption size

- caption_face:

  plot caption face

- caption_margin:

  plot caption ggplot2::margin

- axis_text_size:

  axis text size

- axis_title_family:

  axis title family

- axis_title_size:

  axis title size

- axis_title_face:

  axis title face

- axis_title_just:

  axis title justification

- plot_margin:

  plot ggplot2::margin (specify with \`ggplot2::margin“)

- grid_col:

  grid color

- grid:

  grid TRUE/FALSE

- axis_col:

  axis color

- axis:

  axis TRUE/FALSE

- ticks:

  ticks TRUE/FALSE

- legend_title:

  Title of the legend (default `"Z"`)

- legend_labels:

  Labels for the legend ticks, if used with
  [`show_landscape`](https://docs.ropensci.org/landscapetools/reference/show_landscape.md)
  they are automatically derived.

- legend_text_size:

  legend text size, default 8

- legend_title_size:

  legend text size, default 10

- ratio:

  ratio for tiles (default 1, if your raster is not a square the ratio
  should be `raster::nrow(x) / raster::ncol(x)`)

- viridis_scale:

  Five options are available: "viridis - magma" (= "A"), "viridis -
  inferno" (= "B"), "viridis - plasma" (= "C"), "viridis - viridis" (=
  "D", the default option), "viridis - cividis" (= "E")

- ...:

  optional arguments to ggplot2::theme

## Value

A list of ggplot2 components. The list contains a ggplot2 theme object
and a fill scale object that can be added to a ggplot with `+` to style
raster visualizations.

## Details

A focused theme to visualize raster data that sets a lot of defaults for
the
[`ggplot2::theme`](https://ggplot2.tidyverse.org/reference/theme.html).

The functions are setup in such a way that you can customize your own
one by just wrapping the call and changing the parameters. The theme
itself is heavily influenced by hrbrmstr and his package hrbrthemes
(<https://github.com/hrbrmstr/hrbrthemes/>).
