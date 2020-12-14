# Puerto Rico Election Shapefile
This shapefile was obtained from the [Comisión Estatal de Elecciones](https://ww2.ceepur.org/Home/Estadisticas), the State Election Commission website. It was processed by students working with MGGG during and after the 2020 Geodata Bootcamp. This effort was included Kat Henneberger, Benjamin Carman, Antonio Onwu, Claudia Aranda, Jorge Lopez-Nava, and Quinn Molloy. Some additional processing was done by MGGG staff.

## Sources
The Puerto Rico precinct shapefile and election results were obtained from the [Comisión Estatal de Elecciones](https://ww2.ceepur.org/Home/Estadisticas), the State Election Commission website. 2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2010 census block shapefile for Puerto Rico was downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).


## Processing
Precincts were built from digitizing PDF maps. Demographic data were aggregated from the block level using MGGG’s proration software. Congressional and state legislative district IDs were also assigned to precincts using this package.

## Metadata
* `State`: State
* `STATEFP`: State FIPS code
* `Municipio`: Municipality (county-level jurisdiction) name
* `MUNIFP`: Municipality FIPS code
* `Precinct`: Precinct name
* `CODE`: Precinct code
* `GOV16PPD`: Number of votes for 2016 Partido Nuevo Progresista (New Progressive Party) gubernatorial candidate
* `GOV16PNP`: Number of votes for 2016 Partido Popular Democrático (Popular Democratic Party) gubernatorial candidate
* `GOV16I`: Number of votes for 2016 independent gubernatorial candidates
* `RC16PPD`: Number of votes for 2016 Partido Popular Democrático (Popular Democratic Party) resident commissioner candidate
* `RC16PNP`: Number of votes for 2016 Partido Nuevo Progresista (New Progressive Party) resident commissioner candidate
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
* `HDIST`: State House district number
* `SEND`: State Senate district number
* `SEND-name`: State Senate district name

## Projection
This shapefile uses a UTM Zone 20N projection (ESPG:3920).

## Rating
We give this shapefile an A rating. All data were obtained from the Puerto Rican government and processing was conducted by a group trained by and working closely with MGGG.
