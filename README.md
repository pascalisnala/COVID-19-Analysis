# Temperature and Humidity Variation Impact to COVID-19 Analysis

This project is a **machine learning** project prepared to help Gugus Tugas Percepatan Penanganan COVID-19 in Indonesia to see whether a non-pharmaceutical interventions, in this case, the relationship between temperature and humidity variations possibly affect the spread of this virus.

*This project is part of Google Bangkit Program assignment #05-W05*
>**Team Member**:
[Nala Krisnanda](https://github.com/pascalisnala), 
[Emma Suryani](https://github.com/hoboroots)

## Datasets
We use public datasets to supporting this project.  Some of the datasets that we use are from Kaggle including:
 - [2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
 - [Weather/climate data for JHU's COVID19 sites](https://www.kaggle.com/eeemonts/weatherclimate-data-covid19/metadata)

## Techniques

-   We are trying to divide countries into clusters based on their temperature and humidity. afterwards, will then be analyzed how COVID-19 cases that occur in each cluster
    
-   We use 3 features to form clusters which are the median of the humidity, median of lowest temperature, and median of highest temperature. We use a median because we feel that using a median will better represent the situation in the country
    
-   Tensorflow K-Means clustering is being used to model the hypothesis to understand the impact of weather variation on the spread of COVID-19.
    
-   For visualization, we reduce the feature using principal component analysis (PCA) to make cluster results easier to see and take insights

## Slides/PPT
You can read the complete results of this analysis in presentation format at [this link](https://docs.google.com/presentation/d/1w0gt4dR3eC99KrHu0gF_EZ4s9i8UDMex8MIsImMKtnU/edit#slide=id.g82e6a5c596_0_16)