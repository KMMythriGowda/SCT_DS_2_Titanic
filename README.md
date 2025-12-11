**Titanic Dataset Analysis — Task 2**

This repository contains my analysis of the Titanic dataset (Task 2). The goal is to explore, clean, and visualize the dataset to understand key factors influencing passenger survival.

**📌 Objectives**
- Load and explore the Titanic dataset
- Handle missing data (Age, Cabin, Embarked)
- Preprocess and clean the dataset
- Perform exploratory data analysis (EDA)
- Identify survival patterns based on:
   - Gender
   - Passenger class
   - Age
   - Fare
   - Embarked port
- Visualize insights using Matplotlib and Seaborn

**📊 Key Visualizations**
- Survival count plot (Survived vs Not Survived)
- Survival by Gender
- Survival by Passenger Class (Pclass)
- Age distribution
- Fare distribution
- Correlation heatmap
- Survival by Embarked Port
- Survival by Age Groups

**🧹 Data Cleaning Steps**
- Imputed missing Age values using median
- Filled missing Embarked values using mode
- Dropped Cabin column due to high missing values
- Converted categorical variables into numeric formats where required

**📈 Key Findings**

- **Gender:** Females had higher survival rates than males
- **Passenger Class (Pclass):** Higher-class passengers had better chances of survival
- **Fare:** Higher fare correlated with higher survival probability
- **Age:** Children and young adults had slightly higher survival rates
- **Embarked Port:** Passengers from certain ports had higher survival
- These insights align with historical accounts of the Titanic disaster.

**🛠️ Tools and Libraries Used**

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

**📁 Files Included**

`SCT_DS_2_Titanic.ipynb` — Complete code, analysis, and visualizations

**📦 Requirements**
Install dependencies using:
`pip install -r requirements.txt`
Recommended versions (for reproducibility):
- pandas >= 1.5.0
- numpy >= 1.25.0 
- seaborn >= 0.12.0 
- matplotlib >= 3.7.0

**📥 Dataset**

- [Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data)
- Ensure train.csv and test.csv are placed in the notebook folder before running the analysis

**📝 How to Run**
1. Clone the repository:
    `git clone https://github.com/KMMythriGowda/SCT_DS_2_Titanic.git`
2. Open `SCT_DS_2_Titanic.ipynb` in Jupyter Notebook or Google Colab
3. Install dependencies:
     `pip install -r requirements.txt`
5. Run each notebook cell sequentially

**📧 Contact**

Feel free to reach out if you'd like to discuss this project or collaborate!
