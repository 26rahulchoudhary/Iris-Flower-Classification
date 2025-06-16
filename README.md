Iris Flower Classification using Logistic Regression

🌸 Iris Classification Project

A Python-based machine learning project focused on classifying Iris flower species using Logistic Regression. 
The project includes comprehensive data preprocessing, visualization, model training, and evaluation on a clean and widely-used dataset.

📌 Features

1. Dataset Handling

   * Load and process the Iris dataset from CSV
   * Clean data by removing duplicates and handling column formatting

2. Exploratory Data Analysis (EDA)

   * Visualize data with pair plots, histograms, and correlation heatmaps
   * Analyze relationships between petal/sepal dimensions and species

3. Model Building

   * Split dataset into training and test sets
   * Apply Logistic Regression for multi-class classification
   * Fit model and predict on unseen data

4. Evaluation Metrics

   * Accuracy Score
   * Confusion Matrix
   * Classification Report with Precision, Recall, and F1-Score
   * Visual feedback on model performance


🛠 Design Choices

1. ML Algorithm

   * Logistic Regression selected for its simplicity and effectiveness in multi-class problems
   * Easy to interpret and works well with linearly separable features

2. Data Visualization

   * Seaborn and Matplotlib used to create meaningful plots
   * Visual aids to understand data distribution and model behavior

3. Evaluation Strategy

   * Train/test split with random state for reproducibility
   * Use of multiple evaluation metrics to get a complete performance picture

4. Code Modularity

   * Clear separation of EDA, modeling, and evaluation sections
   * Easy to extend with additional algorithms or tuning

---

📦 Dependencies
* `pandas>=1.5.0`: Data manipulation
* `numpy>=1.24.0`: Numerical computations
* `seaborn>=0.12.2`: Data visualization
* `matplotlib>=3.7.1`: Plotting graphs
* `scikit-learn>=1.3.0`: Machine learning models and metrics

📁 File Structure

```
📦 Iris-Classification
 ┣ 📄 Classification.ipynb
 ┣ 📄 Iris.csv
 ┗ 📄 README.md
```

🧠 Assumptions and Rationale

* The Iris dataset is balanced and does not require resampling techniques.
* Logistic Regression is appropriate due to the linear separability between species.
* No missing data required imputation.
* Model can be enhanced further with hyperparameter tuning or tested with alternative algorithms (KNN, Decision Trees, etc.).

📬 Contact
    Rahul Choudhary
    📧 [rahulchoudhary5266@gmail.com](mail to: rahulchoudhary5266@gmail.com)
    📍 Mumbai, Maharashtra, India
    🔗 [LinkedIn](https://www.linkedin.com/in/rahul-choudhary-03b571251/)
