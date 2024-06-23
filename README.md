# Star Classification: Comparing Performance of Classification Algorithms
This project compares the performance of three different classification algorithms—Logistic Regression, K-Nearest Neighbors (K-NN), and Support Vector Machine (SVM)—on the task of classifying stars, which is a multi-classification problem.

# Dataset
The dataset used in this project contains features of stars and is available for download from [Link](https://github.com/YBIFoundation/Dataset/raw/main/Stars.csv)


# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

# Project Overview # 
   1.Data Import and Analysis

   - Imported the dataset
   - Checked for missing values
   - Analyzed the dataset using descriptive statistics and visualizations

 2.Data Preprocessing

   - Converted categorical data to numerical data (Star color, Spectral Class)

 3.Modeling

   - Split the dataset into training and testing sets
   - Applied feature scaling to the data
   - Built and evaluated models using three different classification algorithms:
      - Logistic Regression
      - K-NN
      - SVM (with linear kernel)

# Results

- Compared the accuracy of the three algorithms
- Identified the best-performing algorithm for this dataset

# Results and Conclusion
The results showed that SVM with a linear kernel achieved the highest accuracy (98.75%), followed by Logistic Regression (96.25%), and K-NN (75.00%). This suggests that SVM with a linear kernel is the most suitable algorithm for classifying stars based on the features in this dataset.
