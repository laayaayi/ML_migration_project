# 🧠 Migration Predictor



## 📁 Dataset

The dataset consists of CSV-formatted migration data, loaded and prepared using **Pandas**. It includes features like age distribution, occupation, education levels, and region-based movement.

## 🔧 Libraries Used

- `pandas` – Load and clean CSV data, handle missing values
- `numpy` – Perform numerical computations efficiently
- `sklearn.model_selection.train_test_split` – Split data into train/test sets
- `sklearn.svm` – Create and train the SVM classifier
- `sklearn.metrics.mean_squared_error` – Evaluate model performance
- `seaborn` – Generate attractive visualizations to explore feature relationships
- `matplotlib.pyplot` – Plot graphs such as scatter plots and performance charts

## 📊 Methodology

1. **Data Cleaning**: Removed missing values and transformed columns for consistency.
2. **Exploratory Data Analysis (EDA)**: Used Seaborn and Matplotlib to understand feature distributions and correlations.
3. **Modeling**: Trained an SVM classifier using the cleaned dataset and tested accuracy.
4. **Evaluation**: Applied Mean Squared Error to assess predictive performance.



## 🚀 How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
