# 🚢 Titanic - Exploratory Data Analysis (EDA)

This repository contains an in-depth exploratory data analysis (EDA) of the famous [Titanic dataset](https://www.kaggle.com/c/titanic) using Python and popular data science libraries. The objective is to uncover meaningful insights, explore relationships between variables, and lay the foundation for future predictive modeling.

---

## 📁 Project Structure

Titanic-EDA/
│
├── data/
│ └── Titanic-Dataset-csv.csv # Raw dataset used for analysis
│
├── TitanicEda.ipynb # Jupyter notebook for EDA
├── sweetviz_report.html # Auto-generated visual EDA report
├── README.md # Project overview and documentation
└── requirements.txt # List of Python dependencies


---

## 📌 Dataset Description

The Titanic dataset contains information on the passengers aboard the RMS Titanic, with features including:

- `PassengerId`: Unique identifier
- `Survived`: 0 = No, 1 = Yes
- `Pclass`: Ticket class (1 = upper, 2 = middle, 3 = lower)
- `Name`, `Sex`, `Age`
- `SibSp`, `Parch`: Family aboard
- `Ticket`, `Fare`, `Cabin`, `Embarked`: Ticket info and boarding port

---

## 🔍 Exploratory Data Analysis

The EDA notebook includes:

- ✅ **Data Cleaning**: Handling missing values, data types, and duplicates
- 📊 **Univariate Analysis**: Distribution of key variables (age, fare, class)
- 🔗 **Bivariate/Multivariate Analysis**: Relationships between features and survival
- 📈 **Visualizations**: Count plots, histograms, heatmaps, bar charts using `matplotlib`, `seaborn`, and `plotly`
- 🧠 **Statistical Insights**: Gender and class survival rates, fare trends, age distributions
- ⚙️ **Sweetviz Report**: Auto-generated EDA dashboard in HTML format

---

## 📦 Requirements

Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt

Main libraries used:

pandas

numpy

matplotlib

seaborn

plotly

sweetviz

scipy

📁 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/Titanic-EDA.git
cd Titanic-EDA
Open the notebook in Jupyter/Colab:

Local: jupyter notebook TitanicEda.ipynb

Colab: Upload and run in Google Colab

(Optional) View the Sweetviz report:

Open sweetviz_report.html in your browser.

🎯 Insights Summary
Females had a higher survival rate than males.

First-class passengers were more likely to survive.

Children (age < 10) had a noticeably higher chance of survival.

The port of embarkation and fare also showed correlation with survival.

📌 License
This project is licensed under the MIT License.

✍️ Author
Yusuf Olatayo Kareem
MSc Sociology | Data Scientist | Computational Social Researcher
GitHub • LinkedIn

🌐 Acknowledgements
Kaggle Titanic Competition

Sweetviz team for automated data exploration