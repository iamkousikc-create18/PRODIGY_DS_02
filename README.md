Prodigy InfoTech Data Science Internship

Task 02: Data Cleaning and Exploratory Data Analysis (EDA)

📌 Objective
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

📂 Dataset Information
The dataset used for this task is the Titanic Survival Dataset (train.csv), which provides details on the passengers aboard the Titanic. 
- Source: Kaggle Titanic Dataset
- Format: CSV (train.csv)
- Data Shape: 891 rows × 12 columns 
- Key Columns:
     - Survived: Binary indicator (0 = No, 1 = Yes).
     - Pclass: Socio-economic status (1st, 2nd, 3rd class).
     - Sex: Gender of the passenger.
     - Age: Age in years.
     - Fare: Passenger fare.
     - Embarked: Port of embarkation.
       
🛠️ Tech Stack
- Language: Python 3.x
- Libraries:
    - Pandas: For data cleaning and handling missing values. 
    - Matplotlib & Seaborn: For generating count plots, histograms, and heatmaps. 
    - NumPy: For numerical operations. (p. 1)
    - IDE: Jupyter Notebook
      
📈 Key Insights (from Analysis)
Based on the EDA conducted in the notebook:

- Missing Data: The Age and Embarked columns had missing values that were filled using median and mode, respectively. 
- Gender Factor: Females had significantly higher survival rates than males. 
- Socio-Economic Status: First-class passengers had better survival chances compared to other classes.
- Fare Correlation: Passenger fare shows a positive correlation with survival.
- Age Distribution: Most passengers were aged between 20 and 40 years.
  
🚀 How to Run
1. Ensure the dataset file (train.csv) is in the same folder as the notebook.
2. Install dependencies: pip install pandas matplotlib seaborn numpy.
3. Open the .ipynb file and run all cells to see the cleaning steps and visualizations. 
