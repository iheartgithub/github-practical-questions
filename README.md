# github-practical-questions

This repository contains an analysis of the monthly average rainfall from 1855-2015, for the cities of Oxford and Melbourne 

To run this analysis firstly use the command:

```
Rscript source-code/combine-data.R
```

To generate a data frame that contains the data for these two cities, and then use the command: 

```
Rscript source-code/make-plot.R
```

To create a visualisation of the data. 

The input data is in `data` and the results are in `output`.


The data for Melbourne was sourced from http://www.bom.gov.au/climate/averages/tables/cw_086071.shtml.

The data for Oxford was sourced from https://www.metoffice.gov.uk/pub/data/weather/uk/climate/stationdata/oxforddata.txt.
