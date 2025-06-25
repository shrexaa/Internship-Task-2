📊 Task 2 - Exploratory Data Analysis (Titanic Dataset via Seaborn)

🔍 Objective:

To perform Exploratory Data Analysis (EDA) using Seaborn’s built-in Titanic dataset. This includes analyzing patterns, visualizing distributions, understanding relationships between variables, and drawing insights based on statistical and visual analysis.

📁 Dataset Used:

Dataset Name: Titanic (Seaborn version)

Load Command: sns.load_dataset("titanic")

No need to download external files

✨ Dataset Features:

survived: Survival (0 = No; 1 = Yes)

pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

sex, age, sibsp, parch, fare, embarked

class, who, adult_male, deck, embark_town, alive, alone

📌 Tools & Libraries Used:

Python 3.x

Pandas

Seaborn

Matplotlib

Jupyter Notebook

📚 What’s Covered:

1. Data Loading and Inspection

Loaded Seaborn’s Titanic dataset using sns.load_dataset()

Inspected shape, null values, and column types

2. Summary Statistics

Generated .describe() for numerical columns

Counted missing values using .isnull().sum()

3. Data Visualization

Histogram: Age distribution

Boxplot: Fare across different passenger classes

Countplot: Gender vs survival

Heatmap: Correlation matrix

Pairplot: Relationship between age, fare, and survived

Bar plots: Survival rate by who, embark_town, alone

4. Key Insights

Females and non-adult males had higher survival rates

First-class passengers paid higher fares and survived more

Most people boarded from Southampton

Cabin (deck) info was missing for many passengers

Task2-EDA/
├── Titanic_EDA.ipynb          # Notebook with analysis and visuals
├── train.csv                  # Dataset (if used locally)
└── README.md                  # This file
What I Learned

EDA workflow: loading → inspecting → cleaning → visualizing → inferring

How to use Seaborn & Matplotlib for effective plots

Making data-driven decisions from patterns


