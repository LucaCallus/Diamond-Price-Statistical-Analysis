This project based on the "diamonds" dataset with 50,000+ diamonds investigates the relationship between a diamond's physical attributes (the 4Cs: Carat, Cut, Color, Clarity; and Depth and Table) and its market price. The study moves from initial data exploration to rigorous hypothesis testing and concludes with a predictive regression model.
(Performed as part of my BSc. in Computer Science at the **University of Malta** (Year 1))

Read the full research paper [here](https://github.com/LucaCallus/Diamond-Price-Statistical-Analysis/blob/e02aa6b3c49f43758c37c0d1ad4e8db19e919a8a/Hypothesis%20Testing%20and%20Statistical%20Modelling%20on%20Diamonds.pdf)

![Histogram of Price](Media/histogram of price.png)
![Clustered Bar Chart of Price by Carat and Clarity](Media/clustered bar chart price by carat and clarity.png)
![Scatter Plot of Price by Carat](Media/scatter plot price carat.png)
![Pie Chart of Cut](Media/pie chart of cut.png)

## Key Research Phases (Key Chapters)

### 1. Exploratory Data Analysis (EDA)
* Visualisation of price distributions and feature correlations
* Identification of outliers and data cleaning

### 2. Hypothesis Testing (Parametric & Non-Parametric)
* **Normality Testing:** Used Shapiro-Wilk to determine test suitability
* **T-Tests & ANOVA:** Analysed price differences across different Cut and Carat categories
* **Non-Parametric Alternatives:** Applied Wilcoxon Signed Rank, Mann-Whitney U and Kruskal-Wallis since normality assumptions were violated

### 3. Statistical Modelling
* **Multiple Linear Regression:** Built a model to predict diamond prices based on multiple independent variables
* **ANCOVA:** Performed Analysis of Covariance to understand the interaction between categorical attributes and continuous variables (Carat)
* **Model Validation:** Checked for multicollinearity (VIF), homoscedasticity, and residual normality among others

## Tech Stack
* **Language:** R
* **Libraries:** ggplot2, FSA, Hmisc, mctest, klaR, regclass, MASS, lmtest, olsrr
* **Documentation:** Microsoft Word

## Repository Structure
* `[Hypothesis Testing and Statistical Modelling on Diamonds.pdf`](https://github.com/LucaCallus/Diamond-Price-Statistical-Analysis/blob/e02aa6b3c49f43758c37c0d1ad4e8db19e919a8a/Hypothesis%20Testing%20and%20Statistical%20Modelling%20on%20Diamonds.pdf): The full research paper.
* `Scripts/`: Raw code used for data processing and model generation.
* `Data/`: The diamonds dataset used for the study.

## Academic Context
* **Institution:** University of Malta
* **Course:** Hypothesis Testing and Statistical Analysis (Unit Code: SOR1232)
* **Examiner:** Derya Karagoz
* **Grade/Result:** 98/100
