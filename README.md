## Beer Review Analytics

**Exploratory data analysis, statistical modelling and machine learning using the BeerAdvocate dataset**

### Overview

This project analyses approximately 1.5 million beer reviews from BeerAdvocate to investigate what drives customer ratings and how quantitative analysis can generate meaningful commercial insights.

Using Python, SQL-style data manipulation, statistical analysis and machine learning, the project explores consumer preferences, product performance and the factors most strongly associated with highly rated beers.

Although based on beer reviews, the analytical techniques are directly applicable to commercial analytics problems involving customer behaviour, product performance, recommendation systems and business intelligence.

### Objectives

The project investigates questions including:

- Which breweries consistently produce the highest-rated beers?
- Which beer styles receive the best customer reviews?
- What characteristics (taste, aroma, appearance or palate) most influence overall ratings?
- How can products be ranked fairly when some have thousands of reviews while others have only a handful?
- Can overall customer ratings be predicted from product characteristics and reviewer behaviour?

### Dataset

**Source:** BeerAdvocate

- Approximately 1.5 million reviews
- Thousands of breweries
- Thousands of beer styles
- Multiple numerical and categorical variables

Examples include:

- Beer style
- Alcohol by volume (ABV)
- Brewery
- Aroma rating
- Taste rating
- Appearance rating
- Palate rating
- Overall rating
- Reviewer information
- Review date

 ![](heatmap.png)

### Analytical Workflow

The project follows a typical data analytics pipeline:

**Data preparation**
- Data cleaning
- Missing value handling
- Feature selection
- Data validation
- Exploratory statistics

**Exploratory Data Analysis**

Investigation of:

- rating distributions
- brewery performance
- beer styles
- alcohol strength
- reviewer behaviour
- correlations between review metrics

**Statistical Analysis**

Application of:

- confidence intervals
- weighted rankings
- correlation analysis
- feature importance
- uncertainty quantification

Rather than ranking beers using simple averages, confidence intervals are used to account for differing review counts, reducing bias from products with very few reviews.

**Predictive Modelling**

Regression models were developed to investigate whether overall ratings could be predicted from:

- beer characteristics
- review sub-scores
- reviewer behaviour

### Key Findings
**Strongest brewery by ABV**

Schorschbräu produces the strongest individual beer in the dataset (57.7% ABV) and also has the highest average alcohol content across its products.

**Best-rated beers**

Products were ranked using confidence intervals rather than simple averages to provide statistically robust recommendations.

Example recommendations include:

| Beer                        | Style           |
| --------------------------- | --------------- |
| Rare D.O.S.                 | Imperial Stout  |
| Dirty Horse                 | Lambic          |
| Southampton Berliner Weisse | Berliner Weisse |

**What matters most?**

Correlation analysis shows that:

- Taste
- Palate

are the strongest predictors of overall customer ratings.

Aroma and appearance remain important but contribute less to the final score.

**Consumer Preference**

The project also allows recommendations to be tailored according to reviewer preferences.

For example:

"If a customer values aroma and appearance most, which beer styles should they try?"

### Technologies
- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- Jupyter Notebook

### Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Feature engineering
- Regression modelling
- Data visualisation
- Ranking under uncertainty
- Consumer behaviour analysis
- Product performance analysis
- Business insight generation

### Business Relevance

Although based on beer reviews, the techniques demonstrated here are directly transferable to commercial analytics roles.

The project illustrates how large datasets can be used to:

- identify high-performing products
- understand customer preferences
- evaluate product quality
- support evidence-based decision making
- quantify uncertainty
- communicate analytical findings through visualisation

These are common analytical tasks across FMCG, retail, marketing, product analytics and business intelligence.

### Future Improvements

Potential extensions include:

- Interactive Plotly Dash dashboard
- Recommendation engine
- Customer segmentation
- Sentiment analysis of review text
- Time-series analysis of changing preferences
- Classification models for beer style prediction
- Advanced explainable AI (SHAP values)


### Author

**Stephen Curran, PhD**

Data Analyst | Python | SQL | Statistics | Data Visualisation

GitHub: https://github.com/steviecurran

LinkedIn: https://www.linkedin.com/in/dr-stephen-curran