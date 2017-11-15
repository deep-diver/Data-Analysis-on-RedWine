# Data Analysis on Red Wine Data Set.

## Contents
* About Project
* About the Data set
* Resources
* R libraries
* Reference

## About Project
This project has two different purposes. One is to practice EDA(Exploratory Data Analysis), and the other is to familiarize with R language and its libraries. EDA has been done with Red Wind Data set collected around 2009. The main goal of the analysis to predict wine quality with variables(features) that the wine contains.

## About the Data set
The data set contains 1,599 observations on Red Wines. There are 12 different variables to describe a wine. Each variable is 

- **Fixed Acidity**: most acids involved with wine or fixed or nonvolatile (do not evaporate readily)
- **Volatile Acidity**: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste
- **Citric Acid**: found in small quantities, citric acid can add 'freshness' and flavor to wines
- **Residual Sugar**: the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet
- **Chlorides**: the amount of salt in the wine
- **Free Sulfur Dioxide**: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine
- **Total Sulfur Dioxide**: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine
- **Density**: the density of water is close to that of water depending on the percent alcohol and sugar content
- **pH**: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale
- **Sulphates**: a wine additive which can contribute to sulfur dioxide gas (S02) levels, which acts as an antimicrobial and antioxidant 
- **Alcohol**: the percent alcohol content of the wine
- **Quality**: score between 0 and 10

## Resources
* red-wine.rmd: RMD file
* red-wine.html: knitted document from the RMD file
* wineQualityReds.csv: the red wine data set in csv format

## R libraries
* ggplot2: to draw plots of histogram, scatter, density, and etc.
* GGally: to draw scatterplot matrix
* corrplot: to draw scatterplot matrix (w/ different form)
* psych

## Reference
* for ggplot2 : http://ggplot2.tidyverse.org/index.html
* for GGally : https://www.r-bloggers.com/plot-matrix-with-the-r-package-ggally/
* for corrplot : https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html
