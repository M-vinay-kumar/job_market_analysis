# Machine Learning Project: Supervised vs Unsupervised Learning

## Overview
This project explores both supervised and unsupervised learning techniques to analyze a given dataset. The main objective is to compare their performance and determine which approach provides better accuracy. The results indicate that unsupervised clustering algorithms performed better in this case.

## Dataset & Preprocessing
- The dataset was preprocessed using standard techniques such as handling missing values, scaling, and encoding categorical variables.
- Feature engineering techniques were applied to enhance model performance.

## Exploratory Data Analysis (EDA)
- Visualizations were created using Matplotlib and Seaborn to understand the data distribution and relationships between variables.
- PCA was applied for dimensionality reduction.

## Supervised Learning
Various supervised learning models were implemented, including:
- **Linear Regression**
- **Logistic Regression**
- **Decision Trees**
- **Random Forests**
- **Support Vector Machines (SVM)**
- **K-Nearest Neighbors (KNN)**

## Unsupervised Learning
- **K-Means Clustering** and **Hierarchical Clustering** were applied to the dataset.
- PCA was used to visualize clusters in a reduced dimension space.
- The performance of clustering was evaluated using metrics like silhouette score.

## Results & Conclusion
- After testing both supervised and unsupervised learning methods, **unsupervised clustering algorithms provided better accuracy** in identifying patterns in the dataset.
- PCA was effective in reducing dimensionality and improving clustering.

## Libraries Used
The following Python libraries were used in this project:
- `numpy`
- `pandas`
- `matplotlib.pyplot`
- `seaborn`
- `sklearn.preprocessing`
- `sklearn.model_selection`
- `sklearn.metrics`
- `sklearn.decomposition`
- `sklearn.cluster`
- `sklearn.linear_model`
- `sklearn.svm`
- `sklearn.tree`
- `sklearn.ensemble`
- `sklearn.neighbors`
- `warnings`

## How to Run
1. Install dependencies using:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Open the Jupyter Notebook and run the cells step by step.
3. Modify parameters as needed to experiment with different models and hyperparameters.

## Author
This project was developed by Vinay Kumar Modini.

