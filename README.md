# Project: Driving Licenses, Traffic Accidents and Casualties Analysis

## Problem Statment

In the past 30 years, the number of road traffic accidents (RTAs), road traffic injuries (RTIs), and road traffic fatalities (RTFs) continuously increased in KSA  [(Dahim, 2018)](https://reader.elsevier.com/reader/sd/pii/S2352646718300553?token=C1C12D013743AB0ABB0308589D2BABA16B053AB09F43330DAE0C72355A97F0021A8C0F04351309FE99E16EE905D697BB). A few years earlier, the numbers decreased. As a Data scientist who explores and analyzes the data sets, what factors increase or decrease the numbers. Your report should include outside research to support your findings and recommendations to the government sectors to maximize the quality of life in KSA.

## Executive Summary

Some findings appeared by applying detailed data science steps from importing and cleaning data sets to descriptive and inferential statistics. From 1993 to 2017, most regions with the highest driving licenses are Riyadh, Makkah, and Eastern. Moreover, the number of driving licences issued in Makkah is more than the year average. In 2016 and 2017, Makkah has the highest mean traffic accident numbers while Northern Border has the lowest. Even though the remaining regions have the same traffic rules and regulations, Makkah, Riyadh, and the Eastern Region have high mean traffic accidents. At the same time, these regions have more driving licences issued than the year average. There is a correlation between the number of driving licences issued and the number of traffic accidents.

From the plots, Makkah has the highest number of accidents, injured, and dead. In addition to Makkah, Riyadh and Eastern Region have high numbers. In contrast, ten regions out of Saudi Arabia regions have similar numbers. Therefore, plotting shows outliers, which have high numbers of accidents, injuries, and death. In this case, removing the outliers is not appropriate because the outliers need further investigation and research to understand the reasons. The outliers should be identified to avoid any effect on the model's performance to fit a Machine Learning model.

### Datasets

#### Provided Data

- [Traffic Accidents and Casualties by Region](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-traffic-accidents-2008.csv)
- [Driving Licenses Issued By Administrative Area](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-driving-licenses-2004-2008.csv)

The source for the accident data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/), and the source for the license data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/).  

#### [](https://git.generalassemb.ly/fahdah/project-1#additional-data)Additional Data

-  [The website of the General Department of Traffic](https://www.moi.gov.sa/wps/portal/Home/sectors/publicsecurity/traffic/!ut/p/z1/04_iUlDg4tKPAFJABjKBwtGPykssy0xPLMnMz0vM0Y_Qj4wyizfwNDHxMDQx8nZ3CTQ1cAz0dvX3dDE2MnA00vfSj8KvIDg1T78gO1ARAHn-YJg!/)
- [Cleaned and merged dataframe](https://git.generalassemb.ly/fahdah/project-1/blob/master/data/combined_datasets.csv)
- [Exploratory Data Analysis Data](https://git.generalassemb.ly/fahdah/project-1/tree/master/data/EDA)

### Deliverables

-   A Jupyter notebook that describes your data with visualizations & statistical analysis, [here](https://git.generalassemb.ly/fahdah/project-1/blob/master/code/starter-code.ipynb).
-   A README markdown file the provides an introduction to and overview of your project,[here](https://git.generalassemb.ly/fahdah/project-1/blob/master/README.md).
-   A blog post in Arabic or English that showcases the problem and key findings of this project [here](https://fahdah-a15.medium.com/driving-licenses-traffic-accidents-and-casualties-analysis-in-ksa-5c5b59d420f8).


```python

```
