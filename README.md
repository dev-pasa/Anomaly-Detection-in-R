## Anomaly-Detection-in-R
- Anomaly is defined as something unusual and deviates from the norm or from the general data distribution. 
- The goal is to analyze a time series data and find data points that do not behave normally. This is different from dealing with outliers which can be defined as anything that deviates from a given quartile range. 

- `The script is published in Rpubs.` 
- `Rpubs is a free publishing site for r-markdowns and can be implemented from within R-Studio, after generating Knitr file. `

https://rpubs.com/devshrestha/AnomalyDetection

### AnomalyDetection R package
- Source:  

https://github.com/twitter/AnomalyDetection
- AnomalyDetection is an open-source R package to detect anomalies which is robust, from a statistical standpoint, in the presence of seasonality and an underlying trend. The AnomalyDetection package can be used in wide variety of contexts. For example, detecting anomalies in system metrics after a new software release, user engagement post an A/B test, or for problems in econometrics, financial engineering, political and social sciences.

### Installation guide 
- Install the R package using the following commands on the R console:

` -install.packages("devtools")
- devtools::install_github("twitter/AnomalyDetection")
- library(AnomalyDetection)`


## API
Built a basic model that usese in-built packages in R and used to test it on the Cereals dataset. 

## Steps to run the script
- Download and install R-server and R-Studio. 
- Clone the repo 
- Set the path of the cereals file in the read.CSV
- Run the applicaton on R-Studio
