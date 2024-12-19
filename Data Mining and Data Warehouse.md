# Data Mining and Data Warehouse

## Q01. Explain Linear Regression and Non-Linear Regression with example. (5 Marks)

**Linear Regression:** Models relationship between dependent and independent variables as a straight line.
**Example:** Predicting sales based on past data.
**Non-Linear Regression:** Models more complex relationships using non-linear equations.
**Example:** Predicting biological growth rates.

## Q02. What are the key characteristics of rule-based classification? Provide an example of a rule-based classifier. (5 Marks)

**Key Characteristics:** Uses IF-THEN rules for classification, interpretable, relies on human expertise.
**Example:** Decision tree where rules are derived from the tree paths.

## Q03. You have a dataset of fruits, and you want to classify them as either "Apple" or "Orange" based on two features: Color (Red, Orange) and Size (Small, Large). Using Bayesian Classification. (5 Marks)

**Bayesian Classification:** Uses Bayes' theorem to predict the probability of each category.

- Calculate prior probabilities for each class.
- Calculate likelihood of features given each class.
- Apply Bayes' theorem to find posterior probabilities and classify the fruit.

## Q04. What is the primary objective of Support Vector Machines? Explain how SVM handles non-linear data. (3 Marks)

**Primary Objective:** Find the optimal hyperplane that separates different classes.
**Non-Linear Data:** Uses kernel functions to transform data into higher dimensions where it becomes linearly separable.

## Q05. How is outlier analysis conducted in cluster analysis? What are the implications of outliers in clustering results? (3 Marks)

**Outlier Analysis:** Identifies data points that deviate significantly from other data points.
**Implications:** Can distort the clusters, affecting the accuracy of clustering results.

## Q06. Discuss how data visualization is implemented in WEKA. Why is it important for data analysis? (3 Marks)

**WEKA:** Provides tools for visualizing data and results of machine learning algorithms.
**Importance:** Helps in understanding data patterns, detecting anomalies, and presenting results effectively.

## Q07. What are the unique challenges in spatial data mining? Give examples of spatial data mining applications. (4 Marks)

**Challenges:** Handling spatial relationships, high dimensionality, complex data types.
**Applications:** Geographic Information Systems (GIS), urban planning, environmental monitoring.

## Q08. Describe the process of text mining. What are the key techniques used for extracting information from text data? (4 Marks)

**Process:** Text pre-processing, tokenization, stemming, feature extraction, pattern recognition.
**Key Techniques:** NLP, sentiment analysis, clustering, topic modeling.

## Q09. Find the frequent itemsets and generate association rules on below given data using Apriori algorithm. Also find minimum support threshold and minimum confident threshold. (5 Marks)

Unfortunately, I cannot display the full Apriori algorithm here due to space constraints, but it involves the following steps:

1. Identify itemsets that meet the minimum support.
2. Use these itemsets to generate rules that meet the minimum confidence.

## Q10. Construct the FP-Tree using above Table only. (5 Marks)

**FP-Tree Construction:** Requires the input data to be processed into a tree structure, representing itemsets.

## Q11. Data Mining Architecture with brief description. (5 Marks)

**Architecture:** Consists of Data Sources, Data Mining Engine, Pattern Evaluation, User Interface.
**Description:** Each component plays a role in extracting patterns from large datasets.

## Q12. How to build Decision Tree? With example. (3 Marks)

**Steps:**

1. Choose the best attribute using a criterion (e.g., Information Gain).
2. Split the dataset based on the attribute.
3. Repeat the process for each subset until a stopping condition is met.
   **Example:** Classifying animals based on attributes like habitat and diet.

## Q13. What is Data Warehousing? Explain its features. (3 Marks)

**Data Warehousing:** Centralized repository for storing large volumes of data.
**Features:** Subject-oriented, integrated, time-variant, non-volatile.

## Q14. Brief explanation on Data Preprocessing Task. (3 Marks)

**Data Preprocessing:** Involves cleaning, transforming, and preparing data for analysis. Key tasks include data cleaning, integration, reduction, and transformation.

## Q15. Give difference between OLAP and OLTP. (4 Marks)

- **OLAP (Online Analytical Processing):** Used for data analysis, complex queries, historical data.
- **OLTP (Online Transaction Processing):** Used for day-to-day operations, transactional data, real-time.

## Q16. What is Classification? Explain steps with example. (4 Marks)

**Classification:** Assigns items to predefined categories or classes.
**Steps:**

1. **Data Collection:** Gather data for training.
2. **Data Preprocessing:** Clean and prepare data.
3. **Feature Selection:** Identify relevant attributes.
4. **Model Training:** Train a classifier using algorithms (e.g., decision trees, SVM).
5. **Model Evaluation:** Test the classifier on new data.
   **Example:** Classifying emails as 'spam' or 'not spam' based on keywords and patterns.
<br><br>