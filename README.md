SIRI and Mortality in RA Patients (NHANES 1999–2018)
This repository provides R code and documentation for reproducing the analysis presented in the manuscript:
"Association between systemic inflammation response index and long-term mortality in rheumatoid arthritis: a population-based cohort study"

1. Data Access
NHANES data portal: https://wwwn.cdc.gov/nchs/nhanes/Default.aspx
NHANES-NDI linked mortality data: https://ftp.cdc.gov/pub/Health_Statistics/NCHS/datalinkage/linked_mortality/
This analysis uses data from the 1999–2018 cycles.
Please download the necessary datasets and place them in the /data folder.

2. How to Run
Open analysis.Rmd in RStudio.
Ensure all required packages are installed.
Click "Run" or "Enter + Ctrl" to execute the full analysis and generate figures/tables.
3. R Session Information
The R version and package dependencies are shown at the end of analysis.Rmd via sessionInfo().

4. Notes
All file paths are relative. No hard-coded local paths are used.
External files such as NHANES mortality linkages must be requested separately from the CDC.
However, given the large size of the NHANES database, it may be necessary to download datasets to a local hard drive for analysis as needed.
