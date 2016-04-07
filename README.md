# Exploratory-data-analysis-project-3
## Script Name: plot01.R
## Version: 1.0_14

## Libraries needed: no special libraries needed for this part

## Pre-Step One: Set working directory
setwd("~/Google Drive/Coursera_R_studio/exploratory_data/project2")

## Step 1: read in the data
NEI <- readRDS("expdata_prj2/summarySCC_PM25.rds")
SCC <- readRDS("expdata_prj2/Source_Classification_Code.rds")

length(NEI$Emissions)
