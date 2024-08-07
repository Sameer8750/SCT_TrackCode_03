# SCT_TrackCode_3

## BANK MARKETING ANALYSIS

## Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository. 🏦📊

![Picture200](https://github.com/user-attachments/assets/64be1518-38ba-4015-8e1a-75515cf0fdf6)


## 📊 Dataset Overview:
The banking dataset includes detailed information about clients of a bank, including their personal attributes, financial status, and results of various marketing campaigns.

**Key Features of the Dataset:**
- age: Age of the client.
- job: Type of job (e.g., management, technician, entrepreneur).
- marital: Marital status (married, single, divorced).
- education: Level of education (secondary, tertiary, primary, unknown).
- default: Has credit in default? (yes, no).
- balance: Average yearly balance in euros.
- housing: Has a housing loan? (yes, no).
- loan: Has a personal loan? (yes, no).
- contact: Contact communication type (cellular, telephone, unknown).
- day: Last contact day of the month.
- month: Last contact month of the year.
- duration: Last contact duration in seconds.
- campaign: Number of contacts performed during this campaign.
- pdays: Number of days since the client was last contacted from a previous campaign.
- previous: Number of contacts performed before this campaign.
- poutcome: Outcome of the previous marketing campaign (unknown, success, failure, other).
- deposit: Has the client subscribed to a term deposit? (yes, no).

## 🔍 Data Cleaning and Preprocessing
To prepare the dataset for analysis, several cleaning and preprocessing steps were performed:

- Handling missing values in relevant columns.
- Converting categorical variables such as 'job', 'marital', and 'education' into numerical formats.
- Creating new features such as 'balance_category' to categorize clients based on their average yearly balance.

## 🧪 Exploratory Data Analysis (EDA)

EDA was conducted to uncover patterns and insights within the dataset:

- Subscription Rates: Analyzed overall term deposit subscription rates and compared them across different job types, marital statuses, and education levels.
- Balance Distribution: Examined the distribution of clients' yearly balances.
- Loan Analysis: Investigated the subscription rates among clients with housing and personal loans.
- Age Distribution: Explored the age distribution and its relation to term deposit subscription.
- Contact Duration Impact: Studied the effect of contact duration on subscription rates.
- Previous Campaigns: Analyzed subscription rates based on the outcome of previous marketing campaigns.

## 🚀 Key Features

- Python Analysis: Delve into the Python code to discover the transformations and manipulations applied to the banking dataset.
- Comprehensive Dataset: Access the complete dataset for your exploration and analysis.

## 🧰 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 💡 Insights

The subscription rate among clients was approximately 47%.
The majority of clients had secondary education.
Clients without loans had a higher subscription rate compared to those with loans.
Clients with higher average yearly balances had better subscription chances.
The age group 30-50 had the highest number of clients.

🛠️ Setup and Usage
<br>

**1. Clone the repository :**
<br>
```bash
    https://github.com/Sameer8750/SCT_TrackCode_Task3.git
```

**2. Analyze with Python:** 

Dive into the Python analysis by opening Bank_Marketing.ipynb.

**Dependencies:**
<br>
To run the Python notebook, install the necessary packages :
```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
```

**Running the Analysis:**

- Open the Jupyter notebook Bank_Marketing.ipynb.
- Run the cells step-by-step to perform data cleaning, EDA, feature engineering, and machine learning modeling.
- Explore the visualizations and insights generated throughout the analysis.

## 🤝 Contributing:

Contributions are welcome! Whether you want to enhance the analysis or add new features:

- Open issues to discuss potential changes.
- Submit pull requests to collaborate on improvements.

## 📬 Contact

Reach out to me:

Sameer Shinde
Email: sameershinde1621@gmail.com

Explore the banking data, analyze trends, and uncover the stories within the dataset! 🏦📊






