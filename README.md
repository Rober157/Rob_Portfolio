# Data Science portfolio by Roberto Rey
This portfolio is composed by a compilation of data science projects regarding machine learning and data analysis. Datasets that are not public can be found [here](https://github.com/RoberRey/RoberRey.github.io/tree/main/Datasets).
## Time Series.
### [ARIMA for Time Series Analysis](https://github.com/RoberRey/RoberRey.github.io/blob/main/Notebooks/ARIMA.md)
ARIMA model acronym for "Autoregressive Integrated Moving Average" is a generalization of an autoregressive moving average model. These models are fitted to time series data to analyse it or to forecast future points in the series. In this notebook we analyze two datasets, the first dataset is the 'milk' dataset, it is about monthly milk production in pounds per cow in 20th century. The second dataset is composed by the price (dolars) of the Apple stocks starting in 1980 with a monthly update of the price.

## Non-parametric statistics.
### [KDA in Ovals](https://github.com/RoberRey/RoberRey.github.io/blob/main/Notebooks/KDA.md)
Kernel Discriminant Analysis (KDA) is a nonlinear version of Linear Discriminant Analysis (LDA), both of them are well-known and widely used techniques for supervised feature extraction and dimensionality reduction. The Ovals dataset contains 3000 observations, it has 3 columns which are the X and Y coordinates and a label, the Ovals' name comes from the shape that these dots form. In this notebook we perform both approaches (including also QDA) and we compare their accuracy.
### [Kernel mean shift clustering in MNIST dataset](https://github.com/RoberRey/RoberRey.github.io/blob/main/Notebooks/KMS.md)
Kernel mean shift clustering is a strong nonparametric technique that does not require prior knowledge of the number of clusters. It's a centroid-based algorithm that works by updating centroids candidates to be the mean of the points in a given region. The MNIST dataset contains images of handwritten 0−9 digits used in mailing. Each observation is a grayscale image made of 28 × 28 pixels that is recorded as a vector of length 28x28=784 by concatenating the pixel columns. In this notebook we are using KMSC techinque to investigate different ways of writing the digit “3”.
## Biostatistics.
### [Cox Proportional Hazards Model with Time-Dependent Covariates](https://github.com/RoberRey/RoberRey.github.io/blob/main/Notebooks/Cox_Model.md)
Proportional hazards models are a class of survival models in statistics. Survival models relate the time that passes, before some event occurs, to one or more covariates that may be associated with that quantity of time. In a proportional hazards model, the unique effect of a unit increase in a covariate is multiplicative with respect to the hazard rate. The dataset used is [mgus2](https://stat.ethz.ch/R-manual/R-devel/library/survival/html/mgus.html) from the survival package in R and it contains the natural history of 1341 subjects with monoclonal gammopathy of undetermined significance. Our goal is to fit a proportionals hazards model in order toobtain the effect of a unit increase in a covariate to conclude which of the covariates may lead to death.
## Network Analysis.
### Science communication in Twitter [(pdf)](https://github.com/RoberRey/RoberRey.github.io/blob/main/Notebooks/TFM.pdf) [(code)](https://github.com/RoberRey/TFM)
The aim of this project was to study the connections between the Science and Pseudo-science of the Spanish speaking community on Twitter and find out if there are any echo chambers. Misinformation is a dangerous tool commonly used in social networks, especially when this misinformation is related to health issues. The project was carried out with a data set that has 55 million Twitter user profiles. To approach this issue, data filtering techniques were applied to obtain the user profiles of interest in order to build the network. The network was analysed through different network analysis techniques, such as centrality measures, which will help us to detect the main user profiles of the network and clustering that enables us to discover hidden communities belonging to the network. There were no echo chambers found according to the Science and Pseudoscience communities, although several sociolinguistic and political communities were found.
