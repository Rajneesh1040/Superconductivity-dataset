
# Superconductivity Dataset - Prediction of Critical Temperature

## Project Overview
This project involves predicting the critical temperature of superconductors using various regression techniques. The dataset contains features extracted from superconductors and the critical temperature for each.

## Dataset Information
### Files
- **train.csv**: Contains 81 features extracted from 21,263 superconductors. The 82nd column represents the critical temperature.
- **unique_m.csv**: Contains the chemical formulas of all 21,263 superconductors from train.csv. The last two columns include the critical temperature and the chemical formula.

### 🔗Source
The data is available at the [UCI Machine Learning Repository on Superconducting Data](https://archive.ics.uci.edu/ml/datasets/Superconductivty+Data).

## Objective
To predict the critical temperature of superconductors based on the features provided in train.csv.

## Requirements
Ensure you have the following Python libraries installed:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- opendatasets

You can install these libraries using pip:
```
pip install numpy pandas matplotlib seaborn scikit-learn opendatasets
```



# Regression Model Comparison

## Conclusion: Comparative Analysis of Regression Models

Based on the R2 scores achieved by different regression models, we can draw the following conclusions:

- **Polynomial Regression:** Achieved an **R2 score of 0.719**. This model tends to capture some of the non-linear relationships in the data, but its performance is moderate compared to other models evaluated.

- **Decision Tree Regressor:** Achieved a higher **R2 score of 0.871**. With optimal parameters **(Max Depth: 50, Min Samples Leaf: 5)**, this model shows improved predictive capability by creating deeper splits and reducing overfitting.

- **Random Forest Regressor:** Achieved the highest **R2 score of 0.915**. Utilizing **400 estimators**, this ensemble method aggregates predictions from multiple decision trees, resulting in robust performance and capturing complex relationships in the data.

In summary, while Polynomial Regression and Decision Tree Regressor provide reasonable predictive performance, the **Random Forest Regressor outperforms** both with the **highest R2 score of 0.915**, indicating it is the most effective model for the dataset considered.

## License
[MIT License](LICENSE)
