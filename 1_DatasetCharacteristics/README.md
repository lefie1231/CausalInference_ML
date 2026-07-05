# Dataset Characteristics

**[Notebook](exploratory_data_analysis.ipynb)**

## Dataset Information

### Dataset Source
- **Dataset Link:** https://github.com/NickCH-K/causaldata/tree/main/Python/causaldata/nsw_mixtape

### Dataset Characteristics
- **Number of Observations:** 445 observations
- **Number of Features:** 8 features (including 1 ID variable)

### Target Variable/Label
- **Label Name:** re78
- **Label Description:** Real earnings from 1978, which is the outcome I will use to measure the impact of job training participation.
- **Label Values:** It contains values between 0 USD and 60.307,93 USD. 
- **Label Distribution:** The distribution of re78 is very skewed to the right, with the mean being at 5.300,76 USD.

### Feature Description
- ** Individual ID (data_id):** Indicates where the data is from, string, only "Dehejia-Wahba Sample"
- ** Treatment (treat):** Dummy (0/1) for being treated under the "National Supported Work Demonstration Job Training Program", string
- ** Age (age):** Age in years, string, between 17 and 55 years, mean at around 25 years
- ** Education (educ):** Years of education, string, between 3 and 16 years, mean at around 10 years
- ** Race (black):** Dummy (0/1) for being black, string, probability of being black is 0.83
- ** Ethnicity (hisp):** Dummy (0/1) for being hispanic, string, probability of being hispanic is 0.09
- ** Marriage (marr):** Dummy (0/1) for being married, string, probability of being married 0.09
- ** Degree (nodegree):** Dummy (0/1) for having no degree, string
- ** Pre-treatment earnings (re74, re75):**  Real earnings in the years before treatment (1975), continuous, between 0 USD and 39.570,68 USD (for re74, mean 2.102,27 USD); between 0 USD and 25.142,24 USD (for re75, mean 1.377,14 USD)


## Exploratory Data Analysis

The exploratory data analysis is conducted in the [exploratory_data_analysis.ipynb](exploratory_data_analysis.ipynb) notebook, which includes:

- Data loading and initial inspection
- Statistical summaries and distributions
- Missing value analysis
- Feature correlation analysis
- Data visualization and insights
- Causal discovery and the construction of a DAG without colliders
