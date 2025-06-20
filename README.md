🚢 Task 2: Data Cleaning and Exploratory Data Analysis (EDA)
📝 Objective
Perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset to explore relationships between variables, identify patterns, and gain insights into passenger survival and characteristics.

📂 Dataset
Source: Titanic Dataset - Kaggle

Files Used: train.csv (main dataset with labels)

Variables:

Categorical: Sex, Embarked, Pclass, Survived

Numerical: Age, Fare, SibSp, Parch

🛠️ Tools & Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🔧 Steps Performed
1. Data Loading
Imported dataset using pandas.read_csv().

2. Data Cleaning
Checked for missing values using .isnull().sum().

Imputed missing Age with median, and Embarked with mode.

Dropped Cabin due to too many missing values.

3. Exploratory Data Analysis (EDA)
Univariate Analysis: Distribution plots of Age, Fare, Pclass, etc.

Bivariate Analysis:

Survival rate by gender

Survival rate by class (Pclass)

Age distribution among survivors vs. non-survivors

Correlation Heatmap: Identified relationships between numerical variables.

4. Visualizations
Bar plots, histograms, boxplots, pie charts, and heatmaps.

📊 Sample Insights
Females had a much higher survival rate than males.

Passengers in 1st class had better chances of survival.

Younger passengers were more likely to survive than older ones.

Traveling with family (via SibSp or Parch) showed moderate influence on survival.

📈 Sample Output Visuals
(Include screenshots or links to images if you're uploading this to GitHub)
Example:

🎯 Learning Outcomes
Improved understanding of real-world data preprocessing.

Gained experience in visualizing data distributions and relationships.

Learned how to interpret data patterns to inform predictive modeling.

