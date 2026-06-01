# Customer Satisfaction & Response Time Analysis (Hypothesis Testing)

This project investigates whether faster customer support response times lead to higher customer satisfaction (CSAT) scores. A real-world support ticket dataset was analyzed using statistical hypothesis testing and predictive modeling techniques to evaluate the relationship between service speed and customer satisfaction.

# Objective
To determine whether response time has a statistically significant impact on customer satisfaction and quantify the strength of this relationship using statistical and machine learning methods.

# Tools & Technologies
Python
Pandas & NumPy
SciPy (Statistical Testing)
Scikit-learn
Statsmodels
Matplotlib / Seaborn

# Methodology
1. Descriptive Analysis
Analyzed distribution of CSAT scores and response times
Grouped data into response-time quartiles
Identified patterns across channels and categories
2. Hypothesis Testing (Inferential Statistics)

Spearman’s Rank Correlation → relationship strength between variables
Mann-Whitney U Test → compare two independent groups
Kruskal-Wallis H Test → compare multiple groups

Hypotheses:

H₀: Response time has no effect on CSAT
H₁: Response time significantly affects CSAT

3. Predictive Modeling
Ordinal Logistic Regression to model CSAT outcomes
Random Forest Classifier to evaluate feature importance
Model comparison to assess predictive power of response time

# Key Findings
CSAT scores decreased as response time increased
Statistical tests showed significant results (p < 0.05), rejecting the null hypothesis
Response time was a strong predictor of CSAT in machine learning models
However, effect size was moderate, indicating other factors also influence satisfaction
