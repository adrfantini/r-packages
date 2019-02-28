# A list of R packages I find useful

#### GENERIC PLOTTING
Package | Description
------- | --------
ggplot2 | The best plotting package, period
tmap | Advanced plotting generic program using both `lattice` and `ggplot`
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
multiscales | Multivariate color scales
ggridges| Ridgeline plots
ggpmisc | Adding tables, ridges and valleys, fit equations with R2, density filters
ggforce | {Zoomed and paginated} facets; {arcs, circles, gradient links, sina (violin-like)} plots, additional transformations
ggbeeswarm| better scatterplots without overlaps
ggpirate| pirate plots, a kind of advanced boxplots
ggpol | A fem geometris, some of which linked to politics (parliament plots)
ggperiodic| Periodic plots, such as 360degree and 24-h circle plots without jumps in coord_polar
ggstatsplot | Functions to provide ggplots with added very detailed statistical information

#### INTERACTIVE PLOTTING/MANIPULATION (http://www.htmlwidgets.org/showcase_leaflet.html)
Package | Description
------- | --------
rthreejs | Interactive 3D scatterplots and globe plots using three.js
plotly | Interactive plotting with D3
mapview | Visualize spatial data using `leaflet`
mapedit | Edit spatial data using `leaflet`
mapdeck
leaflet | R interface to the `leaflet` library for interactive maps
leafgl | Faster web gl rendering of features on `leaflet` maps
timevis | nteractive timeline/timeseries visualizations
r2d3| Low-level D3.js visualizations
rAmCharts | Interactive charts based on amcharts.js

#### DASHBOARDS
Package | Description
------- | --------
shiny
advanced-shiny | Not a package, but still... https://github.com/daattali/advanced-shiny
shinyjs | Set of functions to complete missing `shiny` features
shinyWidgets | Set of additional `shiny` widgets
shinydashboard
flexdashboard | Easy interactive dashboards for R

#### PLOTTING OVER TILED (WEB) MAPS
Package | Description
------- | --------
ggmap| Oldish interface to add google-like maps to ggplot
googleway
RgoogleMaps
tiler #Package to adapt background maps to a given CRS, ready to plot with leaflet

#### COLORS
Package | Description
------- | --------
RColorBrewer| Provides Cynthia Brewer color palettes, integrates with ggplot2
colorpiler| Additional color palettes, including Brewer's. ggplot integration supported
colourpicker
colourvalues
colorspace
scico | Colour palettes developed by Fabio Crameri

#### SPATIAL BOUNDARIES (maps)
Package | Description
------- | --------
rnaturalearth
rnaturalearthhires
rnaturalearthdata
rworldmap
rworldxtra
maps
mapdata
maptools

#### VECTOR DATA MANIPULATION
Package | Description
------- | --------
sf| Simple features for R
lwgeom | sf bindings to the liblwgeom library
rmapshaper| very fast and accurate polygon simplification, extraction of lines from polygons, and much more
smoothr | Smooth polygons using different methods, integrates with sf
geometa | Write, read & validate geographic metadata; extends sf

#### RASTER DATA MANIPULATION
Package | Description
------- | --------
raster
stars

#### HANDLING TABLES
Package | Description
------- | --------
dplyr
data.table| Similar in scope to dplyr, but in general quite a bit faster, albeit with less clear grammar. Also provides the best text file reader, fread
tidyr
purrr

#### DEALING WITH TIME
Package | Description
------- | --------
tibbletime
tsibble
lubridate | Tidy date handling package
timetk
zoo
xts
forecast
PCICt | 360-day calendars

#### PARALLEL COMPUTING
Package | Description
------- | --------
promises | Especially useful applied to multi-user Shiny apps or Shiny apps with long and slow tasks. Uses `future`.
future | The base for promises. Execute R code asyncronously in the background, potentially with many cores
future.batchtools | Extension for future to provide PBS, SLURM... access via `batchtools`
future.apply |  Parallel `apply` integration with `future`s
furrr | purrr... in the future
foreach | Simple parallelised for loops
batchtools | Provides tools to interact with batch schedulers such as SLURM, TORQUE, OpenPBS...
pbapply | Progress bars with `mcapply` and `parLapply` made easy. Adds a significant overhead
pbmcapply | Parallel `apply` with progress bars, uses `future`. Fastest progress bar implementation by far, but only ptovides `lapply` and `mapply`


#### LOGGING
Package | Description
------- | --------
futile.logger| Best logger there is
tryCatchLog| Wrapper to futile.logger for catching standard warnings and errors
assertr| Error controls in magrittr pipelines
logging
log4r

#### NETCDF DATA HANDLING
Package | Description
------- | --------
ncdf4
tidync
ncmeta
RNetCDF

#### UNIT HANDLING
Package | Description
------- | --------
units
udunits2

#### DEVELOPMENT
Package | Description
------- | --------
profvis | Profile your code, and visualise performance interactively

#### MISC
Package | Description
------- | --------
drake | Toll for reproducible research: define your planned workflow, rerun only what changed
styler | Style and beautify your R code
knitr | Elegant, flexible, and fast dynamic report generation
broom | Tidy and prepare for plotting the output of common model functions / fits
forcats | Tidy tools for handling factors
tidytext
glue| Handy replacement for paste()
stringr | Better string handling
readr | Tidy tools for reading data into R
skimr | Very nice package for computing and showing better summary statistics. Very, very nice.
optparse| Best package for parsing input

#### ADDITIONAL LINKS
- https://cloud.r-project.org/web/views/SpatioTemporal.html
- https://cloud.r-project.org/web/views/Spatial.html
- https://cloud.r-project.org/web/views/TimeSeries.html
- https://github.com/qinwf/awesome-R
