## Sport Activity Classification using Time Series Analysis

Approximate running times of the file
- With test section (includes everything): **60-120 min**
- Data preparation/tranformation and classification: **45-60 min**

**Multivariate data with features**
- Heart Rate
- Speed
- Altitude

**SKTime Models applied:**
* Time Series Forest Classifier
* Supervised Time Series Forest
* Random Interval Spectral Ensemble
* Random Interval Classifier
* Shapelet Transform Classifier
* K-Neighbors Time Series Classifier
* Composable Time Series Forest Classifier

**For comparison also sklearn models applied:**
* Random Forest Classifier
* Decision Tree Classifier
* Ridge Classifier CV
* Support Vector Classifier
* K-Neighbors Classifier
* Gradient Boosting Classifier
* Stochastic Gradient Descent Classifier


### Results
* X: (232, 424)  y: (232,)
* Train: (185, 424) (185,) Test: (47, 424) (47,)
* Execution time: ~80 min (Lenovo Yoga 920-13IKB)

![results_a](https://raw.githubusercontent.com/JABE22/Image/main/Random/results_datasetup_a.png)

* X: (1160, 207)  y: (1160,)
* Train: (928, 207) (928,) Test: (232, 207) (232,)
* Execution time: ~240 min (Lenovo Yoga 920-13IKB)

![results_b](https://raw.githubusercontent.com/JABE22/Image/main/Random/results_datasetup_b.png)
