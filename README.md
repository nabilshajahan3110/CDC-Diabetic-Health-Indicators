## CDC-Diabetic-Health-Indicators
A machine learning project on the BRFSS2015 CDC dataset. In this dataset, I have implemented classification model algorithms to predict outcomes of responders as diabetic or non-diabetic/prediabetic.

As the first step, I have imported all the necessary libraries, loaded the dataset, and executed preliminary codes to understand all the properties of the dataset such as shape, statistics summary, feature details, etc.

I continued on my work from the first step and performed univariate, bivariate, and multivariate analysis. These analyses and visualizations helped me to understand the dataset in depth and provide vital information regarding the subject matter. As part of outlier detection, I performed IQR and Z-Score methods. The former method reduced my dataset to 80k instances while the later method reduced it to 160k instances. Since many columns still displayed varied skewness and high kurtosis, I performed Log Transformation and Sqrt Transformation on both sets of datasets. I was able to reduce the skewness and kurtosis further.

 In the next phase, I intend to create classification model algorithms and implement all four sets of datasets and make predictions. Subsequently, I will run extensive model evaluation metrices to determine the best dataset and model.
