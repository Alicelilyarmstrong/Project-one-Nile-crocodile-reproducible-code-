# 🐊Project One-Nile crocodile reproducible code🐊 #
This is all the code for my paper, **‘Exploring the impacts of anthropogenic change on Nile crocodile (*Crocodylus niloticus*) distributions over the last 150 years’**. This project was completed as part of my masters course (Ecology, Evolution and Conservation Research) at Imperial College London.



# Raw data #

All wrangled data for analysis has been provided in this repository as csv. files.in the **'data'** folder


**References for original sources of data:**

**NHM specimen data-**
provided in data folder as 'croc_neat.csv' 

**GBIF specimen data-**
provided in this repository as 'GBIF_final.csv' but you must site:
Global Biodiversity Information Facility. (2023). Occurrence Download. https://doi.org/10.15468/dl.2fn763 [Accessed 8th January 2023].

**IUCN range polygons-**
The IUCN Red List of Threatened Species (IUCN)., (2022). Spatial Data Download. [Accessed 4th December 2022]. https://www.iucnredlist.org/resources/spatial-data-download

**Land cover data-**
Hurtt, G. C., et al. (2019). Harmonization of Global Land Use Change and Management for the Period 850-2015. Version 20190529. Earth System Grid Federation. https://doi.org/10.22033/ESGF/input4MIPs.10454

**Human population size and density data-**
Klein Goldewijk, K., A. Beusen, J.Doelman and E. Stehfest (2017), Anthropogenic land use estimates for the Holocene; HYDE 3.2, Earth System Science Data, 9, 927-953.


# Analyses #

Some code has been adapted from Cooper et al (2020):
Natalie Cooper, Jake Curry and Emily Buckingham. 2020. GitHub: nhcooper123/protecting-pangolins: Code for the paper. Zenodo. DOI: 10.5281/zenodo.4266580. 


All the code used for plots and analysis is given in this repository. Below is a brief description of each script.


**01 Wrangling specimen occurrence data.Rmd-** This script takes georeferenced  Nile crcodile data and wrangles it.

**02 Plotting specimen occurrence data.Rmd-** This script allows you to visualize georeferenced Nile crocodile specimens from GBIF and the NHM (London).

**03 Modelling historical Nile crocodile occurrence with Maxent.Rmd**- This script runs a Maxent species distribution model on the historical Nile crocodile specimen data from GBIF and the NHM.

**04 Functions anthropocene data.R-** custom functions needed to run scripts 05 and 06.

**05 Land use extractions.Rmd-** This script gets land cover data  from specimen error polygons.

**06 Population extractions.Rmd-** This script gets human population data from specimen error polygons.

**07 Areas of overlap between historic and current ranges.Rmd-** This script runs code to explore the level of overlap between historic and current *C.niloticus*  ranges using a convex hull.

**08 Logistic general linear model.Rmd-** This script performs a general linear model with quasi binomial errors to measure the effects of human population size, density and land cover type on overlap between historic (museum specimen data) and present-day (IUCN data) *C.niloticus* distributions.


# Figures #
Some of the plots a figures from my thesis are given here in the **figures** folder
