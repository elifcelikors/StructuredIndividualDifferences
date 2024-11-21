# SharedIndividualDifferences (SID)

This project contains the following files:

1) SID_rawData.csv: Includes the raw data from all individuals, including the ones that were excluded from the final analyses and contains untransformed variables. 

2) SID_dataCeaning.Rmd: This is the script that is used to clean the raw data file (SID_rawData). The output of this script (SID_selfRatings.csv) is a data frame that is used in the main analyses. 

3) SID_selfRatings.csv: This is the cleaned data frame that we used in all our analyses in the published paper. If you would like to use our data to perform new analyses, we recommend that you use this file.

4) SID_mainAnalysis.Rmd: This is the main analysis script.
   
5) rmse.neigh.mean.csv, rmse.other.mean.csv, opt_cohort_size.csv, min_point_mean.csv: These four files are outputs of the mainAnalysis script. Running this analysis can take a while, so we are providing the output.
