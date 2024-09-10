# Mental-Health-Analysis🩺
### Overview
This project aims to classify mental health issues such as anxiety, depression, and stress into various severity levels using machine learning algorithms. The severity levels are determined based on data collected from the Depression, Anxiety, and Stress Scale (DASS-42) questionnaire and the Ten Item Personality Inventory.
### Dataset
The dataset used for this project is derived from the DASS-42 questionnaire, which includes 42 questions designed to measure the symptoms of depression, anxiety, and stress. The dataset also incorporates responses from the Ten Item Personality Inventory to enhance the classification process.

### Class Labels
The dataset is categorized into four main class labels:

__Mental_state__ – Overall mental state of the individual

__Stress_state__ – Severity of stress

__Depression_state__ – Severity of depression

__Anxiety_state__ – Severity of anxiety

Each class label has five possible values:

1.Normal

2.Mild

3.Moderate

4.Severe

5.Extremely Severe

### Machine Learning Algorithms
The following machine learning algorithms were applied to classify the mental health conditions:

- Decision Tree

- Naive Bayes

- K-Nearest Neighbor (KNN)

### Data Preprocessing and Techniques

__Data Preprocessing__: Essential steps to clean and prepare the data for modeling.

__Principal Component Analysis (PCA)__: Used for dimensionality reduction.

__K-Fold Cross-Validation__: Employed to evaluate the performance of the models.

### Results
The Decision Tree algorithm demonstrated the highest accuracy in classifying mental health issues into the five severity levels. Both '__Entropy__' and '__Gini Index__' attribute selection measures yielded similar accuracy results.

### Conclusion
The Decision Tree classifier was found to be the most effective algorithm for this classification task, outperforming Naive Bayes and K-Nearest Neighbor in terms of accuracy.

### Installation
To run this project, you need to have Python installed along with the following libraries:

- pandas

- numpy

- scikit-learn

- matplotlib (optional for visualization)

- seaborn (optional for visualization)

### Acknowledgments
The Depression, Anxiety, and Stress Scale (DASS-42) and the Ten Item Personality Inventory are valuable resources for mental health assessment.
Special thanks to the open-source community for providing the tools and libraries used in this project.
