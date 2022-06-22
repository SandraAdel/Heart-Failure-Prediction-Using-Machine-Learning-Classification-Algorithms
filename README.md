# Heart-Failure-Prediction-Using-Machine-Learning-Classification-Algorithms
## Dataset
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

# Preprocessing Pipeline
1) Numerical features statistics.
2) Missing values detection.
3) Duplicates detection.
4) Target balance detection.

![Target Imbalance](https://user-images.githubusercontent.com/81769303/174997461-4f8fc775-c064-4cd2-b02a-8db1715acd7d.png)

5) Outliers detection and handling.

A) Before handling:
![Outliers before handling](https://user-images.githubusercontent.com/81769303/174998464-f3394c53-bd06-4e82-ae34-64b6fc725199.png)

B) After handling:
![Outliers after handling](https://user-images.githubusercontent.com/81769303/174998525-f5ace8e2-c638-4297-b27a-2915ef3748c3.png)

6) Distribution of numerical and categorical features.

A) Numerical features:
![Numerical features](https://user-images.githubusercontent.com/81769303/174999702-c3e30706-0df8-4e7a-a924-45742ad421c0.png)

B) Categorical features:
![Categorical features](https://user-images.githubusercontent.com/81769303/174999794-1b7ae026-c708-4770-9768-e35cafb45f5d.png)

# Data Visualization Pipeline
1) Histogram of features between classes.

A) Numerical features:

![Distribution of features between classes - numerical](https://user-images.githubusercontent.com/81769303/175001415-37aae5bb-410d-476c-b737-0a4e3e8a785c.png)

B) Categorical features:

![Distribution of features between classes - categorical](https://user-images.githubusercontent.com/81769303/175001497-07afb017-d31e-41be-8a86-60793e6cbd57.png)

2) Pairplot of features.

![Pairplot of features](https://user-images.githubusercontent.com/81769303/175001704-0eff2066-f671-45ad-a1aa-b31a42ea21d5.png)

3) Correlation between features.

![correlation between features](https://user-images.githubusercontent.com/81769303/175001884-0e6e1c8e-9406-468b-93e0-4d889f128b26.png)

# Feature Scaling Pipeline
1) Quantization of categorical features.

![Quantization of features](https://user-images.githubusercontent.com/81769303/175004749-f063e65c-6c20-428e-9134-e6cf4b813c43.png)

2) Dataset splitting into training, validation and testing.
3) Feature scaling step.

# Feature Extraction Pipeline
## Backward Sequential Feature Selection
1) Performing backward SFS.
2) GridSearchCV for finding best hyperparameters.
3) Validating models.

![SFS matrix](https://user-images.githubusercontent.com/81769303/175005593-18badad4-8922-4a09-b24b-54076e6d7422.png)

![SFS boxplot](https://user-images.githubusercontent.com/81769303/175005626-8e9eaea6-d2bc-4ce1-8a5c-f058ad4093e9.png)

## Principal Component Analysis
1) Choosing best number of principal components.

![number of pcs](https://user-images.githubusercontent.com/81769303/175005913-8a0f50d5-137d-46b6-aece-5823b24df496.png)

2) Data Transformation.
3) GridSearchCV for finding best hyperparameters.
4) Validating models.

![PCA matrix](https://user-images.githubusercontent.com/81769303/175006412-9e72a7b1-02df-458f-9170-7760a937989d.png)

![PCA boxplot](https://user-images.githubusercontent.com/81769303/175006435-8aec072d-687a-42d2-906e-4002687eb8f6.png)

# Training and Testing Pipeline
1) Training and testing chosen models.
2) Plotting testing results.

![Testing matrix](https://user-images.githubusercontent.com/81769303/175006845-4cf68422-534a-415e-aa1e-cce3ac58d080.png)

![Testing boxplot](https://user-images.githubusercontent.com/81769303/175006859-b1a83962-77e8-44bd-bc27-f96902ea14d4.png)

3) Visualization of predictions.

A) RF predictions using PCA:

![PCA predictions](https://user-images.githubusercontent.com/81769303/175007216-460dde23-bed6-4e1f-84f7-728f02dd9221.png)

B) RF predictions using SFS:

![SFS predictions](https://user-images.githubusercontent.com/81769303/175007285-1b5bf7f6-0a04-4e69-b0c1-d0539d642138.png)

4) Confusion matrix.

![confusion matrix](https://user-images.githubusercontent.com/81769303/175007543-0dbc0d73-32f0-488f-89ca-bdac8cba876d.png)


