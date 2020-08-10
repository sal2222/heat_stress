# heat_stress
Heat stress illness and climate research

This repository contains code used for:

## Data Preparation

### NLDAS-2 Weather Data Preparation
- Examine location shapefiles and NLDAS-2 grid overlays [[here]](shapefiles.html)  

- Instructions to download NLDAS-2 files using `wget` command [[here]](nldas_wget.html)  

- Extract locations (cells) and variables from NLDAS-2 .nc4 files with conversion to raster brick [[here]](extract_cells.html)  

- Link NLDAS estimates assembled in `extract_cells`to specific locations and summarizes the data [[here]](installation_nldas.html)

- Add unit conversions, calculate new variables, and add Heat Index and WBGT indices [[here]](nldas_indices.html)

### Heat Stress Illness Data Preparation
- Functions to read and compile Defense Medical Epidemiology Database (DMED) queries [[here]](dmed_read.html)

## Climate 

- Aggregate over calendar periods [[here]](nldas_averaged.html) 

- Climatologies (1990-2018) [[here]](climatology.html) 

- Annual temperature and heat indices [[here]](annual_tables.html)

- Air Force weather station data (U.S. Army installations, 2008-2018) - sensitivity analysis [[here]](af_weather.html)

## Land Cover

- Tree canopy statistics [[here]](land_cover.html)

## Heat Stress Outcomes

- DMED HSI Summary (annual) [[here]](dmed_summary.html) 

- DMED encounters (all diseases and injuries) [[here]](dmed_full_icd.html)

## Exploratory models
(not linked)

- see *annual_hsi* repository for annual models
