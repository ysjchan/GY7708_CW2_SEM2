# GY7708-Assignment-2
GY7708 Assignment 2: Geospatial Information Processing Project

## Introduction <a name="introduction"></a>
This assignment entails developing skills in wikipedia textual and spatial data analysis. With the data focused in the Wikipedia articles with assigned geo-tags in Greater London for the assigned borough and this document was created in RMarkdown.

This assignment was created using [R](https://www.r-project.org/), [Rstudio](https://rstudio.com/), [RMarkdown](https://rmarkdown.rstudio.com/) and [GitHub](https://github.com/).  

## Table of contents 
* [General info](#introduction)
* [Prerequisites](#prerequisites)
* [Datasets](#datasets)
* [References](#references)

## Prerequisites <a name="prerequisites"></a>
The dependencies for the assignment are:
* [tidyverse](https://www.tidyverse.org/)
* [magrittr](https://magrittr.tidyverse.org/)
* [stopwords](https://cran.r-project.org/web/packages/stopwords/stopwords.pdf)
* [WikipediR](https://cran.r-project.org/web/packages/WikipediR/WikipediR.pdf)
* [tidytext](https://cran.r-project.org/web/packages/tidytext/vignettes/tidytext.html)
* [jsonlite](https://cran.r-project.org/web/packages/jsonlite/index.html)
* [httr](https://cran.r-project.org/web/packages/httr/index.html)
* [ggspatial](https://paleolimbot.github.io/ggspatial/)
* [wordcloud2](https://cran.r-project.org/web/packages/wordcloud2/vignettes/wordcloud.html)
* [scales](https://scales.r-lib.org/)
* [webshot](https://wch.github.io/webshot/articles/intro.html)
* [htmlwidgets](https://cran.r-project.org/web/packages/htmlwidgets/index.html)
* [sf](https://r-spatial.github.io/sf/)
* [ggplot2](https://ggplot2.tidyverse.org/)

## Main Datasets <a name="datasets"></a>

* wikipedia_geotags_in_GreaterLondon.csv: a dataset containing Wikipedia articles focused in Greater London. The articles are also geo-tagged.

* London_Ward.shp: a shapefile containing boundary information within the city of london. Shapefile includes county and town name data. See also [**Statistical GIS Boundary Files for London**](https://data.london.gov.uk/dataset/statistical-gis-boundary-files-london)


## References <a name="references"></a>

This assignment would like to acknowledge that this document includes teaching materials from Dr Stefano De Sabbata for the module [GY7708 Geospatial Databases and Information Retrieval](https://le.ac.uk/modules/2020/gy7708). And the associated teaching materials can be found [here](https://sdesabbata.github.io/UoL-GY7708-2020-21/practicals/index).

This repository / document contains public sector information with Office for National Statistics (https://geoportal.statistics.gov.uk/) licensed under the [Open Government Licence v3.0](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/): wikipedia_geotags_in_GreaterLondon.csv and London_Ward.shp. And regarding the data derived from Wikimedia Downloads (https://dumps.wikimedia.org/legal.html) licensed under the GNU Free Documentation License (GFDL, https://www.wikipedia.org/wiki/Wikipedia:Copyrights) and the Creative Commons Attribution-Share-Alike 3.0 License (https://creativecommons.org/licenses/by-sa/3.0/), and text from Wikipedia available under the Creative Commons Attribution-ShareAlike License (https://creativecommons.org/licenses/by-sa/3.0/, additional terms may apply). See also [**Statistical GIS Boundary Files for London**](https://data.london.gov.uk/dataset/statistical-gis-boundary-files-london).

