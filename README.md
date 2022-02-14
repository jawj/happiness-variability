# Happiness variability

This repository contains the happiness variability data analyses written up by MacKerron and Powdthavee.

All analyses were performed using Stata 16, within [Kyle Barron's Stata kernel](https://kylebarron.dev/stata_kernel/) for Jupyter Lab.

According to the terms under which Mappiness respondents participated, response-level Mappiness data can only be shared with academics and for agreed academic research purposes. Thus we cannot make the full data set public. 

We have instead shared the following:

* `variability_data_prep.ipynb` 
([HTML export](https://jawj.github.io/happiness-variability/variability_data_prep.html)): 
this short notebook prepares the response-level data used in the paper.

* `variability_from_raw_data.ipynb`
([HTML export with table of contents](https://jawj.github.io/happiness-variability/variability_from_raw_data.html)): 
this notebook loads the prepared response-level data and runs all the reported analyses. It also saves two aggregated data sets described below.

The full data set saved by `variability_data_prep.ipynb` and required to run `variability_from_raw_data.ipynb` is available to academic researchers from the authors [on request](mailto:george.mackerron@sussex.ac.uk).

* `variability_from_aggregated_data.ipynb`
([HTML export with table of contents](https://jawj.github.io/happiness-variability/variability_from_aggregated_data.html)):
this notebook uses only aggregated data to re-run most of the analyses reported in the paper. We have shared these aggregated data as `mappiness_variability_varsample.dta` (for most analyses, one row per user-week) and `mappiness_variability_row_per_user.dta` (for a robustness-check analysis, one row per user).

