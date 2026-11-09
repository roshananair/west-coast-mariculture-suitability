# west-coast-mariculture-suitability
Repository for EDS 233 Homework 3: Prioritizing Potential Aquaculture

## Assessing Suitability for Mariculture on the West (Pacific) Coast of the United States
This repository contains Assignment 3 for EDS 223 Geospatial Analysis & Remote Sensing. This assignment uses suitable growing conditions (sea surface temperature and depth) to create maps of species-specific suitable areas for aquaculture. Sea surface temperature (SST) data is from [NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php) and Bathymetric data is from the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data-products/gridded-bathymetry-data#area), as well as boundaries of US West Coast Exclusive Economic Zone (EEZ) from [marineregions.org](https://www.marineregions.org/eez.php). A map of oyster cultivation suitability is produced, followed by a function to produce an equivalent map for another West Coast US species, given temperature and depth ranges, and then an example using the Pacific Geoduck [Panopea generosa (Gould, 1850)] is shown.

## Repository Contents
 - **data/** Contains all .tiff files containing annual sea surface temperature (SST) from 2008-2012, .tiff for ocean depth, and the West Coast EEZ shapefile.
     - data/average_annual_sst_2008.tif
     - data/average_annual_sst_2009.tif
     - data/average_annual_sst_2010.tif
     - data/average_annual_sst_2011.tif
     - data/average_annual_sst_2012.tif
     - data/depth.tif
     - data/wc_regions_clean.shp
 - **mariculture-suitability.qmd** contains code to create a map of oyster haabitat suitability, a function to create the same map for any other species given min and max temperature and depth requirements, and an example using the Pacific Geoduck (Panopea generosa (Gould, 1850))

## Contributors 
[Roshan Andres Nair](https://github.com/roshananair)

## References
1. NOAA Coral Reef Watch. 2018, updated daily. [NOAA 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1.](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php) College Park, Maryland, USA: NOAA Coral Reef Watch. Data set accessed 2026-11-02

2. GEBCO Bathymetric Compilation Group 2026. [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data-products/gridded-bathymetry-data#area) 2026. The GEBCO_2026 Grid - a continuous terrain model for oceans and land at 15 arc-second intervals. [doi:10.5285/4f68d5c7-45eb-f999-e063-7086abc036fa](https://www.bodc.ac.uk/data/published_data_library/catalogue/10.5285/4f68d5c7-45eb-f999-e063-7086abc036fa)

3. Flanders Marine Institute (2026): [MarineRegions.org](https://www.marineregions.org/eez.php). Available online at www.marineregions.org. Consulted on 2026-11-02.

4. Palomares, M.L.D. and D. Pauly. Editors. 2026. [SeaLifeBase](https://www.sealifebase.ca/search.php). World Wide Web electronic publication. www.sealifebase.org, version (06/2026)

5. [Geoduck Aquaculture: Estimated Costs and Returns for Sub-tidal Culture in B.C.](https://web.archive.org/web/20111217220815/http://www.agf.gov.bc.ca/fisheries/cabinet/GeoduckFactsheet05_01.pdf) British Columbia Ministry of Agriculture and Lands. June 2005.