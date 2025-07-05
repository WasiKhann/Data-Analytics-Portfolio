# Sales Data Analysis: Python-driven Data Preparation & Statistical Inference

This project showcases my ability to perform a comprehensive data analysis workflow in Python, focusing on sales data. It covers essential steps from initial data loading and preparation to applying advanced statistical tests, demonstrating proficiency in data wrangling, exploratory data analysis, and statistical inference.

## 📊 Business Problem & Objectives

In data analysis, understanding the underlying patterns and validating assumptions are crucial for reliable insights. This project serves as a demonstration of applying foundational and advanced analytical techniques to a sales dataset to:

1.  **Ensure Data Quality:** Implement robust data preparation and wrangling techniques to handle real-world data imperfections.
2.  **Uncover Data Characteristics:** Perform exploratory data analysis (EDA) and normality testing to understand data distributions and prepare for statistical modeling.
3.  **Draw Valid Inferences:** Apply appropriate hypothesis tests (ANOVA, T-tests) to analyze relationships between variables and validate assumptions, laying the groundwork for data-driven decisions.
4.  **Showcase Python Proficiency:** Demonstrate a strong command of Python and its key data science libraries for analytical tasks.

## 💡 My Analytical Approach & Methodology

My approach for this project follows a structured analytical pipeline, ensuring data integrity and statistically sound conclusions.

### 1. Data Loading & Initial Inspection

* **Objective:** To load the raw sales dataset and perform initial checks to understand its structure, data types, and identify any immediate issues.
* **Methodology:** Used Pandas to load the data, followed by `.info()`, `.describe()`, and `.head()` to get an overview.

### 2. Data Preparation & Wrangling

* **Objective:** To clean and transform the raw data into a reliable format suitable for rigorous analysis. This addresses common challenges found in real-world datasets.
* **Methodology:** Applied techniques to:
    * Handle missing values (e.g., imputation or deletion, as appropriate).
    * Correct data types (e.g., converting strings to numerical, ensuring date formats).
    * Ensure consistency across various columns.
    * Standardize or normalize data if required for certain statistical tests or modeling.
* **Key Skill Demonstrated:** Practical application of robust data cleaning principles.

### 3. Exploratory Data Analysis (EDA) & Normality Testing

* **Objective:** To understand the distribution and characteristics of key variables, particularly sales data, and to assess whether they meet the assumptions for parametric statistical tests.
* **Methodology:**
    * Utilized visualizations (e.g., histograms, box plots, QQ plots) to visually inspect data distributions.
    * Applied formal normality tests such as the **Shapiro-Wilk test**, **D'Agostino's K-squared test (normaltest)**, and **Anderson-Darling test** to statistically confirm or reject the assumption of normality.
* **Key Skill Demonstrated:** Thorough data exploration and prerequisite validation for advanced analysis.

### 4. Hypothesis Testing (Statistical Inference)

* **Objective:** To investigate relationships between different variables within the sales dataset and draw statistically significant conclusions.
* **Methodology:**
    * **ANOVA (Analysis of Variance) Tests:** Used to determine if there are statistically significant differences between the means of three or more independent (categorical) groups on a continuous outcome variable (e.g., `Sales` across different `Order Priority` levels or `Ship Mode`).
    * **T-Tests:** Employed to compare the means of two groups on a continuous variable (e.g., comparing sales performance between two specific categories within a variable, if applicable to the dataset).
* **Key Skill Demonstrated:** Ability to formulate hypotheses, apply appropriate statistical tests, and interpret p-values to make data-driven inferences.

## 📈 Key Learnings & Insights

This project highlights the critical importance of a structured analytical approach. Through this process, I gained insights into:

* The practical challenges of data wrangling and how Python efficiently addresses them.
* The necessity of normality testing before applying parametric tests to ensure valid results.
* How ANOVA and T-tests can reveal significant differences and relationships within sales data, enabling targeted business strategies (e.g., identifying if `Order Priority` significantly impacts `Sales`).

## 🛠️ Tools & Libraries Used

* **Programming Language:** Python
* **Core Libraries:**
    * `Pandas` (for data manipulation and cleaning)
    * `NumPy` (for numerical operations)
    * `Matplotlib` (for data visualization)
    * `Seaborn` (for enhanced data visualization)
    * `SciPy.stats` (for statistical tests like Shapiro-Wilk, normaltest, Anderson-Darling, t-test)
    * `Statsmodels` (for OLS models and ANOVA)
