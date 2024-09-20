**Topic** : Comparatative anaylsis of computational techniqes for anxiety prediction.

This project analyzes student mental health data and uses machine learning models to predict depression. It involves data cleaning, visualization, and implementing classification models like Random Forest, Logistic Regression, and Decision Trees.

**Overview**
The dataset contains information about students' demographics, academic performance, and mental health conditions (depression, anxiety, panic attacks). The goal is to:
1. Analyze the data to understand mental health trends.
2. Predict depression using machine learning models.
3. Compare model performance based on accuracy.
 
 **Key Steps**
1. Data Loading & Cleaning: Data is loaded from Google Drive, columns are renamed, missing values handled, and categorical values (e.g., Gender, Marriage) are converted to numbers.
2. Exploratory Data Analysis (EDA): Visualizations such as pie charts, bar plots, and a Venn diagram help understand the data distribution and correlations.
3. Model Training:
   - Random Forest, Logistic Regression, and Decision Tree classifiers are used to predict depression.
   - The dataset is split into training and test sets, and models are evaluated using accuracy, confusion matrices, and F1-scores.

 **Results**
- Random Forest performed the best with `95%` accuracy.
- The data shows some students experience multiple mental health issues (depression, anxiety, panic).

**How to Run**
1. Upload the dataset to Google Drive and adjust the file path in the code.
2. Run the code in Google Colab or any Jupyter notebook.
3. Install required libraries:
   bash
   pip install pandas numpy seaborn matplotlib missingno scikit-learn matplotlib-venn

**Conclusion**
The Random Forest model predicts depression with high accuracy, making it the best model in this project. Future improvements can include trying more advanced models or handling data imbalances.
