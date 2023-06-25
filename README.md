# Multivariate-Data-Classification
Multivariate Data Analysis course, CentraleSupélec x Henri Mondor hospital, Spring 2023

### Goal
Analysing a dataset provided by an oncologist at a Paris hospital on the imaging analysis of liver cancer.

### Language
```Python```

### Contents
1. Data exploration
2. 2D method: PCA
3. Multivariate method: PARAFAC

### Librairies
* ```tensorly```
* ```scikit-learn```
* ```pandas```
* ```numpy```
* ```seaborn```
* ```matplotlib```

### Conclusion
This project was carried out to analyse data from cancer patients in order to understand the most influential factors and implement the most effective classification models. To do this, I carried out an exploratory analysis of the data, looking for the most explanatory measures. I then implemented two multivariate analysis methods, PCA and PARAFAC, to extract as much information as possible from the data.

The results of this project are very promising. I've managed to create high-performance classification models with 95% accuracy for the two main types of cancer studied. What's more, I've been able to establish links between mixed cancers and the other two types of cancer, which is very interesting from the point of view of medical research. However, these results obviously have to be weighed against the fact that I had very little data, and that the modelling would have to be repeated with more data in order to obtain truly reliable and usable models.
