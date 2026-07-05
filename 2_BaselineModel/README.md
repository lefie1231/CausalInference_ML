# Baseline Model

**[Notebook](baseline_model.ipynb)**

## Baseline Model Results

### Model Selection
- **Baseline Model Type:** Among multiple potential regression models and 2 structural models, I chose the linear OLS estimation as the best baseline model. 
- **Rationale:** I calculated the mean squared error (MSE) and adjusted R² for all models, and the linear OLS model had the second-best MSE and R-squared values and is unbiased by construction. 
  
### Model Performance
- **Evaluation Metric:** MSE and adj. R² 
- **Performance Score:** MSE of 13.67 and adj. R² of -0.08 

### Evaluation Methodology
- **Data Split:** Train/Test split at 80/20 
- **Evaluation Metrics:** The MSE is useful as it measures the average squared deviation of the fitted values under the model from the actual values. This is very technical and shows how good the model fits the data. However, for the analysis it is also important to know, how much of the variation in the outcome can be explained by the variation of the variables included in the model. Therefore, I additionally calculated the adj. R², which is better for interpretation and intutitive understanding.

## Next Steps
This baseline model serves as a reference point for evaluating more sophisticated models in the [Model Definition and Evaluation](../3_Model/README.md) phase.
