# Puerto Rico Election Shapefile
This shapefile was obtained from the Maine Geolibrary website and processed by students working with MGGG during and after the 2020 Geodata Bootcamp. This effort was led by Jorge Lopez-Nava and Katie Knox and included Nathaniel Cox, Angus Lam, Jennifer Paige, Nathan Pitock, Powell Sheagren, and Victoria Song. Some additional processing was done by MGGG staff.

## Sources
The Maine precinct shapefile was obtained from the [Maine Geolibrary](https://www.maine.gov/geolib/catalog.html), a GIS service of the State of Maine. Election data come from the [Maine Bureau of Corporations, Elections, & Commissions](https://www.maine.gov/sos/cec/elec/results/index.html). 2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2010 census block shapefile for Maine was downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).


## Processing
Some very limited merging of precincts in the tabular election data and precinct shapefile were necessary to join election results to precinct boundaries. Demographic data were aggregated from the block level using MGGG’s proration software. Congressional and state legislative district IDs were also assigned to precincts using this package.


## Metadata
* `STATE`: State
* `STATEFP`: State FIPS code
* `COUNTY`: County name
* `COUNTYFP`: County FIPS code
* `Precinct`: Precinct name
* `CODE`: Precinct code
*	`PRES16D`: Number of votes for 2016 Democratic presidential candidate, without absentee votes
*	`PRES16R`: Number of votes for 2016 Republican presidential candidate, without absentee votes
*	`USH16D`: Number of votes for 2016 Democratic US House candidate, without absentee votes
*	`USH16R`: Number of votes for 2016 Republican US House candidate, without absentee votes
* `GOV16PPD`: Number of votes for 2016 Partido Nuevo Progresista (New Progressive Party) gubernatorial candidate
* `GOV16PNP`: Number of votes for 2016 Partido Popular Democrático (Popular Democratic Party) gubernatorial candidate
* `GOV16I`: Number of votes for 2016 independent gubernatorial candidates
* `RC16PPD`: Number of votes for 2016 Partido Popular Democrático (Popular Democratic Party)
* `RC16PNP`: Number of votes for 2016 Partido Nuevo Progresista (New Progressive Party)  candidate
* `MAY16PPD`: Number of votes for 2016 Partido Popular Democrático (Popular Democratic Party) mayoral candidate
* `MAY16PNP`: Number of votes for 2016 Partido Nuevo Progresista (New Progressive Party) mayoral candidate
* `TOTPOP`: Total population from 2010 Decennial Census
* `NH_WHITE`: White, non-hispanic, population from 2010 Decennial Census
* `NH_BLACK`: Black, non-hispanic, population from 2010 Decennial Census
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population from 2010 Decennial Census
* `NH_ASIAN`: Asian, non-hispanic, population from 2010 Decennial Census
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population from 2010 Decennial Census
* `NH_OTHER`: Other race, non-hispanic, population from 2010 Decennial Census
* `NH_2MORE`: Two or more races, non-hispanic, population from 2010 Decennial Census
* `HISP`: Hispanic population from 2010 Decennial Census
* `H_WHITE`: White, hispanic, population from 2010 Decennial Census
* `H_BLACK`: Black, hispanic, population from 2010 Decennial Census
* `H_AMIN`: American Indian and Alaska Native, hispanic, population from 2010 Decennial Census
* `H_ASIAN`: Asian, hispanic, population from 2010 Decennial Census
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population from 2010 Decennial Census
* `H_OTHER`: Other race, hispanic, population from 2010 Decennial Census
* `H_2MORE`: Two or more races, hispanic, population from 2010 Decennial Census
* `VAP`: Total voting age population from 2010 Decennial Census
* `HVAP`: Hispanic voting age population from 2010 Decennial Census
* `WVAP`: White, non-hispanic, voting age population from 2010 Decennial Census
* `BVAP`: Black, non-hispanic, voting age population from 2010 Decennial Census
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population from 2010 Decennial Census
* `ASIANVAP`: Asian, non-hispanic, voting age population from 2010 Decennial Census
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population from 2010 Decennial Census
* `OTHERVAP`: Other race, non-hispanic, voting age population from 2010 Decennial Census
* `2MOREVAP`: Two or more races, non-hispanic, voting age population from 2010 Decennial Census
* `CD`: Congressional district
* `HDIST`: State House district number
* `SEND`: State Senate district number
* `SENDNAME`: State Senate district name

## Projection
This shapefile uses a UTM Zone 19 projection (ESPG:6348).

## Rating
We give this shapefile an A rating. All data were obtained from the state government and processing was conducted by a group trained by and working closely with MGGG.
