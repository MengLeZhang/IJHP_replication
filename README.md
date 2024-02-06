# IJHP replication code
Replication code and data for IJHP article.

**Context**: England suffers from a chronic undersupply of affordable housing, in particular the social rent tenure. In October 2017, the government announced it would provide additional funding for new social rented housing via Homes England but only in specific areas of the country. To target the additional capital grant in areas of assumed need, it was only available in areas of ‘high affordability pressure’, defined as LAs where weekly private rents were at least £50 more expensive than social rents (Homes England, 2018). The affordability metric is used is mentioned in [addendum of the Shared Ownership and Affordable Homes Programme 2016 to 2021 (Annex 1)](https://assets.publishing.service.gov.uk/media/5b349d1ee5274a0bbef01f89/SOAHP_Addendum_-_Social_Rent_-_Final.pdf). The metric for weekly social rents comes from Housing and Communities Agency (HCA) Standard Data Return (SDR) 2016/2017 and private market rents from Valuation Office Agency (VOA)  Private Rental Market Statistics (PRMS) 2016/2017. Providers of social housing were allowed to bid for social rent funding for developments in localities above the £50 threshold. This meant that [152 out 276 local authorities](https://www.gov.uk/government/publications/shared-ownership-and-affordable-homes-programme-soahp-evaluation-report/soahp-evaluation-final-report-accessible-version) were eligible for bid for this additional funding. 
# Requirements and installation
- R version 4.xxx 
- Rstudio (recommended)
- pacman
- tidyverse
- lubridate
- readxl (for reading excel files)
- jtools
- rddtools
- AER
- patchwork (for composing plots)

Download repository and run 00_master.R to run all the scripts required for the analysis.  The script creates the `/working` folder for temporary files and outputs. All data visualisations are saved into `/working/viz` folder. 

# Troubleshooting and FAQ

# Maintainers 

(omitted for peer review)