# Dataset Characteristics

**[Notebook](exploratory_data_analysis.ipynb)**

## Dataset Information

### Dataset Source
- **Dataset Link:** https://github.com/NickCH-K/causaldata/tree/main/Python/causaldata/nsw_mixtape

### Dataset Characteristics
- **Number of Observations:** 445 observations
- **Number of Features:** 8 features (including 1 ID variable)

### Target Variable/Label
- **Label Name:** Real earnings in 1978 (re78)
- **Label Type:** [Classification/Regression/Clustering/Other]
- **Label Description:** [What does this label represent? What is the prediction task?]
- **Label Values:** [For classification: list of classes and their meanings. For regression: range of values. For other tasks: describe the label structure]
- **Label Distribution:** [Brief description of class balance for classification or value distribution for regression]

### Feature Description
- ** Individual ID (data_id):** Indicates where the data is from, string, only "Dehejia-Wahba Sample"
- ** Treatment (treat):** Dummy (0/1) for being treated under the "National Supported Work Demonstration Job Training Program", string
- ** Age (age):** Age in years, string, between 17 and 55 years, mean at around 25 years
- ** Education (educ):** Years of education, string, between 3 and 16 years, mean at around 10 years
- ** Race (black):** Dummy (0/1) for being black, string
- ** Ethnicity (hisp):** Dummy (0/1) for being hispanic, string
- ** Marriage (marr):** Dummy (0/1) for being married, string
- ** Degree (nodegree):** Dummy (0/1) for having no degree, string
- ** Pre-treatment earnings (re74, re75):**  Real earnings in the years before treatment (1975), continuous, MIN/ MAX, MEANS!


## Exploratory Data Analysis

The exploratory data analysis is conducted in the [exploratory_data_analysis.ipynb](exploratory_data_analysis.ipynb) notebook, which includes:

- Data loading and initial inspection
- Statistical summaries and distributions
- Missing value analysis
- Feature correlation analysis
- Data visualization and insights
- Data quality assessment
