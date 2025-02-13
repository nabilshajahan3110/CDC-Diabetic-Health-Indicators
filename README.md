## CDC-Diabetic-Health-Indicators

### First Phase

A machine learning project on the BRFSS2015 CDC dataset. In this dataset, I have implemented classification model algorithms to predict outcomes of responders as diabetic or non-diabetic/prediabetic.

As the first step, I have imported all the necessary libraries, loaded the dataset, and executed preliminary codes to understand all the properties of the dataset such as shape, statistics summary, feature details, etc.

I continued on my work from the first step and performed univariate, bivariate, and multivariate analysis. These analyses and visualizations helped me to understand the dataset in depth and provide vital information regarding the subject matter. As part of outlier detection, I performed IQR and Z-Score methods. The former method reduced my dataset to 80k instances while the later method reduced it to 160k instances. Since many columns still displayed varied skewness and high kurtosis, I performed Log Transformation and Sqrt Transformation on both sets of datasets. I was able to reduce the skewness and kurtosis further.

In the second phase, I intend to create classification model algorithms and implement all four sets of datasets and make predictions. Subsequently, I will run extensive model evaluation metrices to determine the best dataset and model.

### Second Phase

After referring to similar projects and study materials on Outlier Detection, I learned that datasets with binary columns does not require outlier detection. Hence, after removing duplicates, I have gone to feature selection.

Using K-Means Clustering, I performed feature selection and was provided with 6 features.

After performing train-test split and scaling, to handle dataset imbalance, I performed NearMiss method.

Finally I performed model initialization and evaluation metrices. The best performing model was k-NN with 82.98% accuracy.

In the third phase, I will perform Hyperparameter tuning and Pipeline Building.
