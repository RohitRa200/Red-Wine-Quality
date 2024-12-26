# Red Wine Quality Analysis

This repository contains an Exploratory Data Analysis (EDA) and feature engineering project on the Red Wine dataset. The objective is to analyze the physicochemical properties of red wine and their relationship with quality scores, as well as prepare the dataset for further modeling tasks such as classification or regression.

---

## Project Overview

The Red Wine dataset includes physicochemical measurements (inputs) and sensory-based quality scores (outputs). This project focuses on uncovering insights from the data, handling potential data issues, and identifying key features that influence wine quality.

---

## Dataset Information

### Source

The dataset is sourced from the UCI Machine Learning Repository. It contains data on red variants of Portuguese "Vinho Verde" wine.

### Attributes

1. **Fixed Acidity**: Non-volatile acids (tartaric, etc.)
2. **Volatile Acidity**: Acetic acid (vinegar-like taste)
3. **Citric Acid**: Adds freshness and flavor
4. **Residual Sugar**: Sugar left after fermentation
5. **Chlorides**: Salt content
6. **Free Sulfur Dioxide**: SO2 not bound to other molecules
7. **Total Sulfur Dioxide**: Bound + free SO2
8. **Density**: Water content approximation
9. **pH**: Acidity/alkalinity level
10. **Sulphates**: Antioxidant and microbial stabilizer
11. **Alcohol**: Alcohol content percentage
12. **Quality**: Sensory score (0-10)

---

## Project Objectives

1. Perform comprehensive data cleaning and preprocessing.
2. Conduct exploratory data analysis (EDA) to derive insights and visualize patterns.
3. Apply feature engineering to identify and transform key attributes.
4. Prepare the data for potential machine learning tasks.

---

## Steps Performed

### 1. Data Cleaning

- Handled missing values by imputation.
- Removed duplicate records to avoid redundancy.
- Detected and treated outliers to ensure data quality.

### 2. Exploratory Data Analysis (EDA)

- Analyzed the distribution of each feature.
- Investigated correlations between physicochemical properties and quality.
- Visualized relationships using bar graphs, histograms, scatter plots, and heatmaps.

### 3. Feature Engineering

- Normalized/standardized numeric features.
- Created interaction terms where necessary.
- Selected key features using correlation analysis and feature importance techniques.

### 4. Key Insights

- Alcohol and volatile acidity are highly correlated with quality.
- Sulphates and citric acid also contribute significantly to wine quality.
- Density and chlorides show weak correlations with quality.

---

## Tools and Technologies Used

- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn
- **Visualization**: Matplotlib and Seaborn for high-quality data visualizations

---

## Repository Structure

```
red-wine-quality-analysis/
|-- data/
|   |-- winequality-red.csv          # Dataset
|
|-- notebooks/
|   |-- eda_red_wine.ipynb           # EDA and feature engineering notebook
|
|-- images/
|   |-- correlation_heatmap.png      # Example visualization
|   |-- feature_distributions.png    # Example visualization
|
|-- README.md                        # Project documentation
```

---

## Results

- EDA uncovered key relationships and distributions in the data.
- Feature engineering prepared the data for predictive modeling tasks.
- Insights are ready for actionable decision-making or model training.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/red-wine-quality-analysis.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd red-wine-quality-analysis
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/eda_red_wine.ipynb
   ```
4. Explore the EDA and feature engineering steps in the notebook.

---

## Future Work

- Apply classification and regression models to predict wine quality.
- Implement advanced feature selection methods to optimize model performance.
- Explore hyperparameter tuning and cross-validation for improved accuracy.

---

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements or suggestions.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact

For questions or suggestions, feel free to reach out:

- **Name**: [Rohit Raj]
- **Email**: [rohitrajrajrohit60@gmail.com](mailto\:Rohitrajrajrohit60@gmail.com)
- **LinkedIn**: [Rohit Raj](https://www.linkedin.com/in/rohitrajanalyticsmind/)

---

Thank you for exploring the Red Wine Quality Analysis project! 🍇

