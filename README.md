# A list of R packages I find useful
Feel free to suggest a package by [opening an issue](https://github.com/adrfantini/r-packages/issues/new)!

#### GENERIC PLOTTING
Package | Description
------- | --------
ggplot2 | The best plotting package, period
tmap | Advanced plotting generic program using both `lattice` and `ggplot`
[tmaptools](https://github.com/mtennekes/tmaptools) | Extension to the `tmap` package
marmap | Import, analyse and plot bathymetries
cartography | Thematic cartography

#### GGPLOT2 EXTENSIONS (www.ggplot2-exts.org)
Package | Description
------- | --------
patchwork | Combining different plots on a grid
cowplot | Combining different plots on a grid, annotations, subplots,
ggally| Plot matrixes, glyphs, combining plots
ggiraph | Interactive gg plots
ggsn| North and scale symbols for ggplot
ggspatial | Spatial helpers, north and scale symbols, backgrounds
gganimate | Animate gg graphics
tweenr| Interpolate animation of gg graphics
transformr| As tweenr, for polygons
ggalt | Several nice scales and geoms, horizon charts, lollipop charts, densities, encircling lines, splines
ggradar | Radar charts with ggplot
ggrepel | Repelling labels
ggextra | Marginal plots
ggquiver| Add arrows and vectors on top of plots
multiscales | Multivariate color scales. Similar in scope to `tricolore`
ggridges| Ridgeline plots
ggpmisc | Adding tables, ridges and valleys, fit equations with R2, density filters
ggforce | {Zoomed and paginated} facets; {arcs, circles, gradient links, sina (violin-like)} plots, additional transformations
ggbeeswarm| better scatterplots without overlaps
ggpirate| pirate plots, a kind of advanced boxplots
ggpol | A fem geometris, some of which linked to politics (parliament plots)
ggperiodic| Periodic plots, such as 360degree and 24-h circle plots without jumps in coord_polar
ggstatsplot | Functions to provide ggplots with added very detailed statistical information
a[metR](https://github.com/eliocamp/metR) | Awesome package for easier analysis of metereological fields. Provides, other than EOF functions and the like, some amazing `ggplot2` extensions for contouring, highlighting areas, subsetting, better scales nd more

#### COLORS AND SCALES
Package | Description
------- | --------
RColorBrewer| Provides Cynthia Brewer color palettes, integrates with ggplot2
[scales](https://scales.r-lib.org/) | Create color scales, integrates some missing features in `ggplot2`
colorpiler| Additional color palettes, including Brewer's. ggplot integration supported
colourpicker
colourvalues
colorspace
[colormap](https://github.com/bhaskarvk/colormap) | Generate colors from color palettes defined in Node.js's colormap module; integrates with `ggplot2`
scico | Colour palettes developed by Fabio Crameri
[tricolore](https://cran.r-project.org/web/packages/tricolore/index.html) | tricolor multivariate color scales, integrated with `ggplot2`. Similar in scope to `multiscales`

#### INTERACTIVE PLOTTING/MANIPULATION (http://www.htmlwidgets.org/showcase_leaflet.html)
Package | Description
------- | --------
plotly | Interactive plotting with D3, can also import `ggplot` plots
mapview | Visualize spatial data using `leaflet`, works with `sf` and `raster`
[plainview](https://github.com/r-spatial/plainview) | Previously provided with `mapview`, provides interactive (raster) images rendered as plain unprojected canvas
[cubeview](https://github.com/r-spatial/cubeview) | Previously provided with `mapview`, inteactive 3D visualization of raster data
[leafpm](https://github.com/r-spatial/leafpm) | Edit spatial data using `mapedit`, using a different editor
[mapdeck](https://github.com/SymbolixAU/mapdeck) | R interface to Deck.gl and Mapbox, interactive 2d/3d maps
leaflet | R interface to the `leaflet` JS library for interactive maps
[leafgl](https://github.com/r-spatial/leafgl) | Faster web gl rendering of features on `leaflet` maps - currently pre-alpha
[rthreejs](https://github.com/bwlewis/rthreejs) | Interactive 3D scatterplots and globe plots using three.js
timevis | nteractive timeline/timeseries visualizations
r2d3| Low-level D3.js visualizations
rAmCharts | Interactive charts based on amcharts.js
dygraphs | Yet another graphical timeseries plotter
[vegalite](https://github.com/hrbrmstr/vegalite) | `ggplot2`-like "bindings" for [Vega-Lite](https://vega.github.io/vega-lite/)
[vegawidget](https://vegawidget.github.io/vegawidget/) | Low level access to the [Vega-Lite](https://vega.github.io/vega-lite/) API, to render as `htmlwidgets` for `shiny` integration 

#### DASHBOARDS
Package | Description
------- | --------
shiny | The go-to R package for interactive web interfaces, dashboards
[advanced-shiny](https://github.com/daattali/advanced-shiny) | Not a package, but helpful resource for shiny hints
shinyjs | Set of functions to complete missing `shiny` features
[shinyBS](https://ebailey78.github.io/shinyBS/) | Add additional functionality and interactivity to your `shiny` applications (last commit 2016)
shinyWidgets | Set of additional `shiny` widgets
shinydashboard
flexdashboard | Easy interactive dashboards for R. Also integrates with `rmarkdown`

#### PLOTTING OVER TILED (WEB) MAPS
Package | Description
------- | --------
ggmap| Oldish interface to add google-like maps to ggplot
googleway
RgoogleMaps
tiler | Package to adapt background maps to a given CRS, ready to plot with `leaflet`

#### SPATIAL BOUNDARIES AND DATA (maps, DEMs)
Package | Description
------- | --------
rnaturalearth | Go-to package for boundaries and other spatial features data from [naturalearthdata](http://www.naturalearthdata.com/)
rnaturalearthhires | High resolution data for `rnaturalearth`
rnaturalearthdata | Additional resolution data for `rnaturalearth`
rworldmap
rworldxtra
maps
mapdata
maptools
[rmapzen](https://tarakc02.github.io/rmapzen/) | A Mapzen API client for R
[mapsap](https://github.com/michaeldorman/mapsapi/) | An interface to some Google Maps APIs, returning `sf` objects
[elevatr](https://cran.r-project.org/web/packages/elevatr/index.html) | Access elevation data from several web services

#### VECTOR DATA MANIPULATION
Package | Description
------- | --------
sf| Simple features for R
lwgeom | sf bindings to the liblwgeom library
rmapshaper| very fast and accurate polygon simplification, extraction of lines from polygons, and much more
smoothr | Smooth polygons using different methods, integrates with sf
geometa | Write, read & validate geographic metadata; extends sf
[areal](https://slu-opengis.github.io/areal/) | Facilitate areal interpolation (with weights) between `sf` polygons and objects
[concaveman](https://github.com/joelgombin/concaveman) | A very fast 2D concave hull algorithm

#### RASTER DATA MANIPULATION
Package | Description
------- | --------
raster | The de-facto standard raster data manipulation tool in R. Has TONS of features but its desing is somewhat old, and new features are not added frequently
stars | A new package which integrates extremely well with `sf` and provides some advantages over `raster`, at the cost of features
gdalcubes_R | New pacakge to deal with GDALcubes, which are collections of Earth Observation images as on demand data cubes (or multidimensional arrays)
[velox](http://philipphunziker.com/velox/) | Fast raster extraction and manipulation. Very fast. Integrates with `raster` and `sf`

#### NETCDF DATA HANDLING
Package | Description
------- | --------
ncdf4 | The main low level package for dealing with netCDF data. Has some drawbacks
RNetCDF | alternative package to `ncdf4`. Works better, but the syntax and usability are terrible
tidync | modern, `tidyverse`-like way to access netcdf data
ncmeta | Easy metadata retrieval from netCDF files
netcdfgeom | Reads and writes geometry data (points, lines and polygons) to/from netCDF files

#### UNIT HANDLING
Package | Description
------- | --------
units | Deal with units in a clear and automatic way, using `udunits2`
udunits2 | R bindings to the Unidata `udunits2` library

#### HANDLING TABLES
Package | Description
------- | --------
dplyr
data.table| Similar in scope to dplyr, but in general quite a bit faster, albeit with less clear grammar. Also provides the best text file reader, fread
tidyr | Set of functions to help tidy data
purrr | Enhanced functional programming with R, via `map*` functions

#### DEALING WITH TIME
Package | Description
------- | --------
lubridate | Tidy date handling package
[tsibble](https://github.com/tidyverts/tsibble) | Tools to integrate `tibble`s with tidy time manipualtion (aggregation, etc.). Also provides rolling means and integrates with `future`s!
[feasts](https://github.com/tidyverts/feasts) | Extend `tsibble` with additional functions, compositions, and visualisations; used by `fable`
[fable](https://github.com/tidyverts/fable) | Methods and tools for displaying and analysing univariate time series forecasts; uses `feasts`
zoo
xts
forecast
PCICt | 360-day calendars

#### DATABASES
Package | Description
------- | --------
[dbplyr](https://github.com/tidyverse/dbplyr) | `dplyr` interface for (also online) databasesl; uses `DBI`
RSQLite | R interface to SQL
[DBI](https://dbi.r-dbi.org/) | Common interface between R and Database Management Systems

#### PARALLEL COMPUTING
Package | Description
------- | --------
future | modern parallel execution API supporting several backends. Execute R code asyncronously in the background, potentially with many cores
[promises](https://rstudio.github.io/promises/) | Asyncronous programming. Especially useful applied to multi-user Shiny apps or Shiny apps with long and slow tasks. Uses `future`.
future.batchtools | `future` extension to provide PBS, SLURM... access via `batchtools`
future.apply |  Parallel `apply` integration with `future`s
furrr | `purrr`... in the `future`
foreach | Simple parallelised for loops
batchtools | Provides tools to interact with batch schedulers such as SLURM, TORQUE, OpenPBS...
[rslurm](https://github.com/SESYNC-ci/rslurm) | Yet another tool to submit and manage SLURM jobs
pbapply | Progress bars with `mcapply` and `parLapply` made easy. Adds a significant overhead
pbmcapply | Parallel `apply` with progress bars, uses `future`. Fastest progress bar implementation by far, but only ptovides `lapply` and `mapply`
clustermq | Very low overhead multiprocessing via `ZeroMQ`. Has live load balancing

#### LOGGING
Package | Description
------- | --------
futile.logger| Best logger there is
tryCatchLog| Wrapper to futile.logger for catching standard warnings and errors
assertr| Error controls in magrittr pipelines
logging
log4r

#### DEVELOPMENT
Package | Description
------- | --------
profvis | Profile your code, and visualise performance interactively
styler | Style and beautify your R code
optparse | Best package for parsing input
[reprex](https://github.com/tidyverse/reprex) | Easily create reproducible examples for SO, GitHub, etc.
testthat | de facto standard R package for testing packages and functions
[usethis](https://usethis.r-lib.org/) | Invaluable tools to automate tasks related primarily to the creation of R pacakges
[pkgdown](https://pkgdown.r-lib.org) | Build website (static html documentation) for your package
[remotes](https://remotes.r-lib.org/) | Install R packages from GitHub, GitLab, Bitbucket, git, svn repositories, URLs
[fs](https://fs.r-lib.org/) | Provide cross platform filesystem operations, combines well with `dplyr` and `purrr`
rcpp | R interface to C++


#### RSTUDIO
Package | Description
------- | --------
[addinslist](https://github.com/daattali/addinslist) | List of useful R studio addins

#### MISC
Package | Description
------- | --------
drake | Toll for reproducible research: define your planned workflow, rerun only what changed
knitr | Elegant, flexible, and fast dynamic report generation
[rmarkdown](https://rmarkdown.rstudio.com/) | Generate documents including code and plots
broom | Tidy and prepare for plotting the output of common model functions / fits
forcats | Tidy tools for handling factors
[nml](https://github.com/jsta/nml) | R interface to Fortran namelists
reticulate | use Python via R
tidytext
[colorout](https://github.com/jalvesaq/colorout) | colorize your R terminal
glue| Handy replacement for paste()
stringr | Better string handling
readr | Fast and friendly tidy way to read rectangular data (like csv, tsv, and fwf)
skimr | Very nice package for computing and showing better summary statistics. Very, very nice.
[eurostat](https://cran.r-project.org/web/packages/eurostat/index.html) | Access, search and download the Eurostat database

#### TASK VIEWS
- https://cloud.r-project.org/web/views/SpatioTemporal.html
- https://cloud.r-project.org/web/views/Spatial.html
- https://cloud.r-project.org/web/views/TimeSeries.html

#### ADDITIONAL LINKS
- https://github.com/qinwf/awesome-R ; https://awesome-r.com/
- http://r-pkgs.had.co.nz/ (how to write R pkgs)
- https://support.rstudio.com/hc/en-us/articles/201057987-Quick-list-of-useful-R-packages
- https://geocompr.robinlovelace.net/index.html
