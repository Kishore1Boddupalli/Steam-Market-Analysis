# 🎮 Steam Market Analysis

## 📌 Project Overview

Steam Market Analysis is a data analytics project focused on understanding game pricing patterns, discount strategies, platform availability, and release trends on Steam.

The project uses Exploratory Data Analysis (EDA) and statistical hypothesis testing to transform raw game listing data into meaningful insights. The analysis helps understand how game prices vary, which operating systems are most supported, and how discounts relate to original and final prices.

## 🎯 Project Objectives

* Analyze the distribution of original and final game prices.
* Understand discount patterns across different price ranges.
* Identify the most widely supported gaming platforms.
* Analyze game release trends over the years.
* Explore relationships between price, discount, and platform availability.
* Apply statistical tests to validate findings and identify significant differences.

## 🛠️ Technologies Used

* **Python** – Data analysis and statistical calculations.
* **Pandas** – Data manipulation and cleaning.
* **NumPy** – Numerical computations.
* **Matplotlib** – Data visualization.
* **Seaborn** – Statistical charts and visualizations.
* **Jupyter Notebook** – Interactive analysis and documentation.
* **SciPy** – Statistical hypothesis testing.

## 📊 Dataset Description

The dataset contains information about Steam game listings and their pricing and platform characteristics.

| Column           | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| `Title`          | Name of the game                                             |
| `Original_Price` | Price before applying a discount                             |
| `Discount`       | Discount percentage offered                                  |
| `Final_Price`    | Price after applying a discount                              |
| `Platform`       | Supported operating systems, such as Windows, Mac, and Linux |
| `Released_On`    | Game release year                                            |

## 🔍 Project Workflow

### 1. Data Cleaning

* Checked the dataset for missing values and inconsistencies.
* Prepared the relevant columns for analysis.
* Ensured that pricing and discount information could be analyzed appropriately.

### 2. Exploratory Data Analysis (EDA)

Performed univariate, bivariate, and multivariate analysis to identify pricing patterns, discount behavior, platform distribution, and game release trends.

### 3. Data Visualization

Created charts to explore:

* Platform support distribution.
* Relationships between original prices and discounts.
* Game release trends over the years.
* Correlations among numerical variables.

### 4. Statistical Hypothesis Testing

**Chi-Square Test:** Used to examine whether game distribution across platforms differs significantly from an equal distribution.

**ANOVA Test:** Used to examine whether average game prices differ across platform-support groups.

A significance level of 0.05 was used to interpret the hypothesis tests.

## 💡 Key Findings

* **Platform Dominance:** Windows support appears in all games in the analyzed dataset, while Mac and Linux support are less common.
* **Pricing Patterns:** The dataset contains games across different price ranges, including low-cost and premium titles.
* **Discount Behavior:** The relationship between original price and discount percentage is weak, suggesting that higher-priced games do not necessarily receive higher discounts.
* **Price Correlation:** Original price and final price show a strong positive correlation.
* **Discount Impact:** Discount percentage has a negative correlation with final price.
* **Release Trends:** The dataset shows an increase in recorded game releases over the years, although the latest year's figures may include upcoming or preregistered listings.

## 📈 Statistical Analysis

The project applies statistical methods to support the findings:

* **Chi-Square Test:** Examines differences in platform distribution.
* **ANOVA Test:** Examines differences in average prices across platform-support groups.
* **Hypothesis Testing:** Uses a significance level of 0.05 to evaluate the null hypotheses.

These tests help distinguish observed patterns from differences that are statistically significant under the assumptions of the tests.

## 💼 Business Recommendations

* Analyze different price segments to understand how games are positioned in the market.
* Evaluate discount strategies across price ranges rather than applying the same discount approach to every game.
* Consider platform compatibility when planning game development and distribution.
* Monitor pricing and release trends to support data-driven business decisions.

## 🚀 Future Enhancements

* Build a machine learning model to predict game prices.
* Develop a game recommendation system.
* Analyze seasonal pricing and release trends.
* Investigate the business value of supporting multiple operating systems.
* Incorporate game ratings, genres, and sales data for deeper analysis.

## 🏁 Conclusion

This project demonstrates how Exploratory Data Analysis, data visualization, and statistical hypothesis testing can be used to investigate Steam game pricing and platform trends.

The findings provide a structured view of game prices, discount patterns, platform availability, and release trends. The project also demonstrates the practical application of Python-based data analytics techniques to a real-world marketplace dataset.

## 👩‍💻 Author

**Boddupally Kishore**

B.Tech Computer Science and Engineering | 2026 Batch

Data Analytics Learner
