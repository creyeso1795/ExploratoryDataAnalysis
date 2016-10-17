# Getting and Cleaning Data - Course Project

This repository hosts the R code and documentation files for the Data Science's track course "Getting and Cleaning data", available in coursera.

# Files

The R script "run_analyis.r" written for the Geting and Cleaning Data final project does the following:

Sets working directory to a folder in your current directory called "RunAnalyis". The zip folder containing the project data is downloaded and extracted here.

All files in the extracted folder are read into R and assigned a name in the environment.

Column names are defined.

All training data files are merged together and all test files are merged together. These consolidated dataframes are then merged.

Mean and Standard Deviation columns are extracted and a subset of data is created.

Column names are standardized and unnecessary symbols removed.

Means are calculated and a tidy data set is exported.

The result of this script should be a file called "tidy.txt" that is saved in the "RunAnalysis" folder.
