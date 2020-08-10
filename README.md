# heat_stress
Heat stress illness and climate research

This repository contains early-stage project code.
RMarkdown outputs can be viewed at: https://sal2222.github.io/heat_stress/index.html; however, this site is no longer updated or maintained.


## Data Preparation

### NLDAS-2 Weather Data Preparation
- Examine location shapefiles and NLDAS-2 grid overlays [[here]](shapefiles.Rmd)  

- Instructions to download NLDAS-2 files using `wget` command [[here]](nldas_wget.Rmd)  

- Extract locations (cells) and variables from NLDAS-2 .nc4 files with conversion to raster brick [[here]](extract_cells.Rmd)  

- Link NLDAS estimates assembled in `extract_cells`to specific locations and summarizes the data [[here]](installation_nldas.Rmd)

- Add unit conversions, calculate new variables, and add Heat Index and WBGT indices [[here]](nldas_indices.Rmd)

### Heat Stress Illness Data Preparation
- Functions to read and compile Defense Medical Epidemiology Database (DMED) queries [[here]](dmed_read.Rmd)

## Climate 

- Aggregate over calendar periods [[here]](nldas_averaged.Rmd) 

- Climatologies (1990-2018) [[here]](climatology.Rmd) 

- Annual temperature and heat indices [[here]](annual_tables.Rmd)

- Air Force weather station data (U.S. Army installations, 2008-2018) - sensitivity analysis [[here]](af_weather.Rmd)

## Land Cover

- Tree canopy statistics [[here]](land_cover.Rmd)

## Heat Stress Outcomes

- DMED HSI Summary (annual) [[here]](dmed_summary.Rmd) 

- DMED encounters (all diseases and injuries) [[here]](dmed_full_icd.Rmd)

## Exploratory models
(not linked)

- see *annual_hsi* repository for annual models
