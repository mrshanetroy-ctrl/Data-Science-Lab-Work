🌊 Water Quality Analysis: Predicting Water Pollution
📌 Description

This project focuses on predicting water pollution levels using machine learning techniques.
The goal is to classify water as safe or polluted based on various physicochemical parameters.
Early detection of water contamination is crucial for public health, agriculture, and environmental sustainability.

This project demonstrates data preprocessing, exploratory analysis, feature selection, and classification model building.

📊 Dataset
Source: Kaggle – Water Quality Dataset
Description: The dataset includes physicochemical features such as:
pH
Temperature
Turbidity
Dissolved Oxygen
Conductivity
Nitrate
Sulphate
Total Dissolved Solids (TDS)
Target Variable: Water quality label (0 = Safe, 1 = Polluted)
🧹 Steps Performed
1. Data Cleaning
Checked for missing values
Handled missing values using mean/median imputation
Removed duplicates
Corrected inconsistent data entries
2. Exploratory Data Analysis (EDA)
Summary statistics
Distribution plots for each feature
Boxplots to detect outliers
Correlation heatmap to understand relationships
Scatter plots for visual inspection
3. Feature Engineering
Normalization/standardization of numeric features
Selection of important features based on correlation
Removal of irrelevant or low-impact features
4. Model Building

Models implemented:

Decision Tree Classifier
Random Forest Classifier

Train-test split: 80% training, 20% testing

5. Model Evaluation

Evaluation metrics used:

Accuracy
Precision
Recall
F1-score
Confusion Matrix

Random Forest performed best due to its ensemble nature.

📈 Results
Best Model: Random Forest Classifier
Achieved high accuracy and stable results across metrics
Identified most influential features:
Turbidity
Dissolved Oxygen
pH
Nitrate

The model successfully predicts whether water is safe or polluted, demonstrating potential real-world application in environmental monitoring.

🛠 Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
📝 Conclusion

This project successfully uses machine learning to classify water quality based on chemical and environmental parameters.
The developed model can assist authorities in early pollution detection and environmental safety decision-making.
Further improvements may include:

Larger dataset
Additional parameters
Deep learning models
Real-time sensor data integration
👤 Author

Shanet Parathara Roy
