Description:

The focus of this project is on predicting the quality of wine based on its chemical characteristics, providing a real-world application of machine learning in viticulture.
The dataset includes several chemical attributes such as acidity, density, and alcohol, which are used as predictors for wine quality.
Three different classification models are implemented and compared to identify the best-performing one.

📊 Dataset Used:

Wine Quality Dataset (UCI Machine Learning Repository)

Path: /content/winequality.csv

Separator: ;

Target Column: quality

Features include:

Fixed acidity

Volatile acidity

Citric acid

Residual sugar

Chlorides

Free sulfur dioxide

Total sulfur dioxide

Density

pH

Sulphates

Alcohol

Quality (Target variable)

🧰 Libraries Used:

Pandas – Data handling and analysis

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Scikit-learn (sklearn) – Machine learning models and evaluation

⚙️ Step-by-Step Process:
1️⃣ Data Loading and Cleaning

Loaded the dataset using pandas.read_csv()

Removed duplicate entries

Checked and handled missing values

Standardized column names

2️⃣ Exploratory Data Analysis (EDA)

Analyzed relationships between variables

Created a correlation heatmap to visualize feature importance

Studied distribution of wine quality

Visualized fixed acidity vs quality using boxplots

3️⃣ Feature Scaling

Used StandardScaler() to normalize all numerical features for better model performance.

4️⃣ Model Building

Implemented three machine learning models:

Random Forest Classifier

Stochastic Gradient Descent (SGD) Classifier

Support Vector Classifier (SVC)

Each model was trained and tested using an 80-20 train/test split.

5️⃣ Model Evaluation

Evaluated models using accuracy score, classification report, and confusion matrix.

Compared performance visually using a bar chart of accuracy scores.

6️⃣ Insights and Recommendations

Most wines have quality ratings between 5 and 7.

Alcohol has a positive correlation with quality, while volatile acidity is negative.

Random Forest Classifier achieved the highest accuracy among the three models.

Model performance can be further improved by hyperparameter tuning and feature selection.

📈 Results:
Model	Accuracy
Random Forest	~85%
SGD Classifier	~72%
Support Vector Classifier	~78%

🏆 Best Model: Random Forest Classifier

🎯 Learning Outcomes:

Learned to apply machine learning classifiers on real-world datasets.

Gained hands-on experience in EDA, data preprocessing, and feature scaling.

Understood the importance of comparing models and visualizing performance metrics.

💡 Conclusion:

This project demonstrates how machine learning can predict wine quality using chemical data.
By analyzing and comparing multiple models, valuable insights into the relationship between chemical composition and quality were discovered.
