# super-doodle

A series of demo using different data visualization for biodiversity data.

## [Visualizing time dimension of occurrence records with gif](occurrence-time-lapse/)

This is a demo to produce a time lapse of threatened antarctic/subantarctic species using occurrence data from [OBIS](iobis.org) retrieved using their R package [robis](https://github.com/iobis/robis), [IUCN redlist](http://www.iucnredlist.org/) classification and [gganimate](https://github.com/dgrtwo/gganimate) library.

Shown below is the `.gif` produced from the R notebook [here](./occurrence-time-lapse/occurrence_time_lapse.Rmd).

![Time lapse gif made from occurrence data for year 2003.](occurrence-time-lapse/occ_by_month.gif)


## [Visualizing taxa with sunburst](taxa-sunburst/)

A demo to visualise taxa using interactive sunburst. Checkout the awesome library [sunburstR](https://github.com/timelyportfolio/sunburstR)

![Taxa information from [SOMBASE PYCNOGONIDS](https://doi.org/10.15468/qtm508) dataset.](taxa-sunburst/taxa-sunburst.png)


## [Bin occurrence records](bin-occurrences/)

How to plot binned occurrence records in mercator projection and polar projection (South Pole).

### [rbokeh](http://hafen.github.io/rbokeh/)
![Binned occurrences + mercator projection](bin-occurrences/rbokeh_log.png)


### [ggplot](http://ggplot2.tidyverse.org/)

![Binned occurrences + polar projection](bin-occurrences/ggplot-polar.png)
