R code for manuscript of mVOCs co-exposure and RA

This repository provides R code and documentation for reproducing the analysis presented in the manuscript:
"Association between volatile organic compound co-exposure and the prevalence of rheumatoid arthritis: A nationwide cross-sectional study"

1. Data Access:

NHANES data portal: https://wwwn.cdc.gov/nchs/nhanes/Default.aspx
This analysis uses data from the 2005–2020 cycles.

2. Data Download:

Please download the necessary datasets and place them in the /data folder.
The specific data files can be accessed by selecting the survey cycles (2005-2006, 2011-2012, 2013-2014, 2015-2016, 2017-2020) and downloading the corresponding files for Demographics, Examination (Body Measures), Questionnaires (e.g., Smoking, Arthritis, Diabetes), and Laboratory (e.g., Volatile Organic Compounds, Complete Blood Count) data.

3. How to Run:

Open analysis.Rmd in RStudio.
Ensure all required packages included in the R scripts are installed.
Click "Run" or "Enter + Ctrl" to execute the full analysis and generate figures/tables.

4. Notes:
Given the large size of the NHANES database, it may be necessary to download datasets to a local hard drive for analysis as needed.
