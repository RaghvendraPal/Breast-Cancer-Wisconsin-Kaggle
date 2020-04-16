# Breast Cancer Wisconsin (Diagnostic) Data Set

DataSet has the following features :

1. radius (mean of distances from the center to points on the perimeter)
2. texture (standard deviation of gray-scale values)
3. perimeter
4. area
5. smoothness (local variation in radius lengths)
6. compactness (perimeter^2 / area - 1.0)
7. concavity (severity of concave portions of the contour)
8. concave points (number of concave portions of the contour)
9. symmetry
10. fractal dimension ("coastline approximation" - 1)

All the features in this dataset are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They have described each cell nuclei present in image.

An image can have various nuclei of Cancer, 
**So each feature od dataset has 3 different category :**

1. mean
2. standard error 
3. worst or largest

At the end DataSet having total features, from this data we need to classify whether a person have **Benign** or **Malignant** cancer.

Repositary have 2 ipynb for the same dataset.
1. Cancer.ipynb has all the analysis of data, data Vizualization, data cleaning, Model Creation step.
Check the following blog :
[BENIGN and MALIGNANT Breast Cancer Wisconsin Prediction](https://medium.com/@raghvendrapal/benign-and-malignant-breast-cancer-wisconsin-prediction-c88bd1ed898d)

2. Cancer_pca.ipynb, i have used [PCA Dimentionality Reduction](https://en.wikipedia.org/wiki/Dimensionality_reduction) step to reduce the dimention of data, so that we will only process important data for cancer prediction.
Check the following blog :
[BENIGN and MALIGNANT Breast Cancer Wisconsin Prediction using PCA](https://medium.com/@raghvendrapal/benign-and-malignant-breast-cancer-wisconsin-prediction-using-pca-a6d4941fafb1?sk=b0a57912788766c36ce9835e755d7304)


