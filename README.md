# Mortality-risk-prediction-for-COVID-19-patients
### Supervised Learning - Classification

## Project Statement: 
The COVID-19 pandemic has caused significant health concerns globally, with high mortality rates in patients with pre-existing medical conditions. Predicting the mortality risk for COVID-19 patients with pre-existing medical conditions is crucial for prioritizing appropriate medical intervention and allocating resources effectively. Therefore, developing a model that can accurately predict the mortality risk for COVID-19 patients with pre-existing medical conditions is critical in improving the outcome of these patients and optimizing healthcare resource utilization.

## Data: 
The data used in this project is a dataset containing features related to COVID-19 patients with pre-existing medical conditions. The dataset is unbalanced, meaning that there are more instances of one class (survivors) than the other (deceased). The data is preprocessed to handle missing values and categorical features.

## Methods:
•	Decision Tree and Random Forest Algorithms: These algorithms are used for classification tasks. Decision tree algorithm is a decision-making tool that uses a tree-like model of decisions and their possible consequences. Random forest algorithm combines multiple decision trees to improve accuracy and reduce overfitting.

•	Hyperparameter Tuning: Hyperparameters are the parameters that are not learned by the model during training. Hyperparameter tuning is the process of finding the best values for these parameters to optimize the model's performance.

•	Feature Selection: Feature selection is the process of selecting relevant features from the dataset. In this project, chi2 and mutual information methods are used to select important features.

•	SMOTE Technique: SMOTE (Synthetic Minority Over-sampling Technique) is a technique used to balance imbalanced data. It generates synthetic samples of the minority class to increase its representation in the dataset.

## Results: 
The model's performance will be evaluated using accuracy, precision, recall, and F1 score on the test set. The results will be compared to a baseline model and other models in the literature. The resulting model will aid healthcare professionals in identifying COVID-19 patients with pre-existing medical conditions who are at a higher risk of mortality, allowing them to provide more intensive care and support.

## Conclusion: 
The implementation of decision tree and random forest algorithms with hyperparameter tuning, feature selection, and SMOTE technique is expected to result in an accurate model for predicting the mortality risk for COVID-19 patients with pre-existing medical conditions. This model can aid healthcare professionals in identifying high-risk patients and provide them with more intensive care and support, potentially reducing mortality rates.

