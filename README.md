#  Lead Scoring Model for Online Education Platform

This project helps an online education provider (X Education) identify the most promising leads, enabling its sales team to focus on high-conversion opportunities and reduce wasted effort. The objective is to score leads using historical interaction data and rank them based on conversion probability.

##  Project by
Shawn Wilson

##  My Contributions
- Cleaned and processed a dataset with 9,000+ rows and 30+ features
- Engineered features, handled missing data, and applied scaling/dummy encoding
- Built a logistic regression model with RFE and VIF filtering to improve interpretability
- Evaluated model using ROC curve, precision/recall, and optimal cutoff selection
- Provided actionable insights and business strategies based on model outputs

## Tools & Technologies
- Python, Pandas, NumPy, Scikit-learn
- Logistic Regression, Feature Selection (RFE), Model Evaluation
- Excel (for data dictionary and source dataset)

##  Key Business Insights
- Hot leads are best identified by:  
  - **TotalVisits**  
  - **Total Time Spent on Website**  
  - **Page Views Per Visit**
- Best categorical signals: Lead source from **Google**, **Direct Traffic**, and **Organic Search**
- Engagement (repeated visits, chat interaction, SMS activity) correlates with higher conversion probability



## Outcome
Achieved ~78% model accuracy with a recall-optimized threshold of 0.42. Helped prioritize leads, reduce unnecessary phone calls, and focus sales efforts on higher probability conversions.

