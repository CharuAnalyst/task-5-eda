Task 5: Titanic Dataset - Exploratory Data Analysis (EDA)

Project Overview
This project performs Exploratory Data Analysis on the famous Titanic dataset to find patterns and factors that influenced passenger survival.

Objective
To analyze the Titanic dataset using Python libraries like Pandas, Matplotlib, and Seaborn and uncover key insights about survival rates based on factors like age, gender, class, etc.

📊 Key Insights Found
1. Overall Survival Rate: Only 38.4% of passengers survived
2. Gender Impact: Females had a 74% survival rate vs 19% for males
3. Passenger Class: 1st Class: 63% survived, 3rd Class: 24% survived
4. Age Factor: Children and younger passengers had better survival chances
5. Missing Data: Age (177), Cabin (687), Embarked (2) values were missing

🛠️ Tools & Libraries Used
- Python
- Pandas - Data manipulation and analysis
- Matplotlib - Data visualization
- Seaborn - Statistical data visualization
- Jupyter Notebook - Development environment

📁 Files in Repository
- /[`task5_titanic_eda.ipynb`](./task5_titanic_eda.ipynb) - Main Jupyter notebook with complete EDA
- /[titanic.csv`](./titanic.csv.csv) - Dataset used for analysis

📈 Visualizations Included
1. Gender vs Survival Countplot
2. Passenger Class vs Survival Countplot  
3. Age Distribution Histogram
4. Correlation Heatmap of Numerical Features

How to Run
1. Clone this repository
2. Install required libraries: `pip install pandas matplotlib seaborn`
3. Open /[`task5_titanic_eda.ipynb`](./task5_titanic_eda.ipynb) in Jupyter Notebook
4. Run all cells

📝 Conclusion

The analysis shows that gender, passenger class, and age were the most significant factors determining survival on the Titanic. Females, 1st class passengers, and children had the highest chances of survival.
