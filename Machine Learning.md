# Machine Learning

## Q01. Explain why a single-layer perceptron can solve linearly separable problems like AND and OR but fails to solve the XOR problem. Use the concept of linear separability to support your explanation. (5 Marks)

**Single-Layer Perceptron:** Can only solve linearly separable problems because it can only create a single linear decision boundary.
**XOR Problem:** Not linearly separable; requires a non-linear boundary which a single-layer perceptron cannot create.

## Q02. Explain the concept of a Perceptron and its role in neural networks. (5 Marks)

**Perceptron:** Basic unit of a neural network. Consists of input nodes, weights, a bias, and an activation function.
**Role:** Forms the building blocks of neural networks, enabling them to learn and make decisions.

## Q03. What is the bias-variance trade-off, and why is it important in machine learning? (5 Marks)

**Bias-Variance Trade-off:** Balancing between bias (error due to assumptions in the model) and variance (error due to model complexity).
**Importance:** Ensures that the model neither overfits nor underfits the data, providing better generalization.

## Q04. Compare TensorFlow and PyTorch as deep learning frameworks. Which one would you choose and why? (3 Marks)

**TensorFlow:** Developed by Google, known for scalability, production readiness.
**PyTorch:** Developed by Facebook, known for ease of use, dynamic computation graph.
**Choice:** Depends on the use case. TensorFlow for production; PyTorch for research and experimentation.

## Q05. Name different evaluation metrics used in Regression? Explain R-squared. (3 Marks)

**Evaluation Metrics:** MSE, MAE, RMSE, R-squared.
**R-squared:** Measures the proportion of variance in the dependent variable explained by the independent variables. Indicates the goodness of fit.

## Q06. Write a short note on Recommendation System. (3 Marks)

**Recommendation System:** Suggests products or services to users based on their preferences and behavior.
**Types:** Collaborative filtering, Content-based filtering, Hybrid methods.
**Applications:** E-commerce, streaming services, social media.

## Q07. Explain the architecture and working of a Convolutional Neural Network (CNN). (4 Marks)

**Architecture:** Composed of convolutional layers, pooling layers, and fully connected layers.
**Working:** Convolutional layers extract features, pooling layers reduce dimensionality, fully connected layers classify the features.

## Q08. In a binary classification problem, out of 30 datapoints, 12 belong to class A and 18 belong to class B. What is the entropy of the dataset? (4 Marks)

**Entropy Calculation:**
\[
Entropy = - (P(A) \log_2 P(A) + P(B) \log_2 P(B))
\]
\[
= - \left( \frac{12}{30} \log_2 \frac{12}{30} + \frac{18}{30} \log_2 \frac{18}{30} \right)
\]
\[
= 0.964
\]

## Q09. Let's consider a dataset where we want to predict the annual salary of employees based on their years of experience. The dataset is as follows. (5 Marks)

**I. Calculate the means of X and Y
II. Calculate the coefficient (slope) ß1.
III. Calculate the intercept B0.
IV. Using the linear regression model, predict the annual salary for an employee with 6 years of experience.**
\[
\mu_X = \frac{Sum(X)}{N}, \mu_Y = \frac{Sum(Y)}{N}
\]
\[
\beta_1 = \frac{Cov(X, Y)}{Var(X)}
\]
\[
B_0 = \mu_Y - \beta_1 \mu_X
\]
**Prediction:** Use the linear equation \( Y = \beta_1 X + B_0 \).

## Q10. Build a Decision Tree Using the ID3 Algorithm Based on Information Gain. A company wants to classify customers based on their purchase behavior, The dataset contains 2 features: "Age" (in years) and "Income" (in thousands dollars), and binary target variable "Buys" (1 for buying a product, 0 for not buying). The initial dataset contains four records. (5 Marks)

**I. Calculate the entropy of the target variable "Buys" for the entire dataset.
II. Calculate the Information Gain and find the root element.**
**Entropy and Information Gain Calculation:** Follow ID3 steps to split the dataset and create the decision tree.

## Q11. What is the bias-variance tradeoff, and why is it important in machine learning? (5 Marks)

**Covered in Q03**

## Q12. Compare and contrast supervised learning with unsupervised learning, focusing on their objectives and typical applications. (3 Marks)

**Supervised Learning:** Uses labeled data to train models. **Objective:** Predict outcomes based on input data.
**Applications:** Regression, classification.
**Unsupervised Learning:** Uses unlabeled data. **Objective:** Find hidden patterns.
**Applications:** Clustering, dimensionality reduction.

## Q13. Name different evaluation metrics used in Regression? Explain R-squared. (3 Marks)

**Covered in Q05**

## Q14. You have a dataset with 1200 samples. You decide to split the dataset into a training set (80%) and a testing set (20%). How many samples will be in the training set and how many in the testing set? (3 Marks)

**Training Set:** 1200_0.8 = 960 samples.
**Testing Set:** 1200_0.2 = 240 samples.

## Q15. Consider the following confusion matrix of the win/loss prediction of cricket match. Calculate model accuracy, Sensitivity, Specificity, Precision, Recall. (4 Marks)

**Model Accuracy:**
\[
\frac{TP + TN}{TP + TN + FP + FN}
\]
**Sensitivity (Recall):**
\[
\frac{TP}{TP + FN}
\]
**Specificity:**
\[
\frac{TN}{TN + FP}
\]
**Precision:**
\[
\frac{TP}{TP + FP}
\]
**Recall:**
\[
\frac{TP}{TP + FN}
\]

## Q16. What is the main objective of a Support Vector Machine (SVM)? (4 Marks)

**Objective:** Find the optimal hyperplane that maximizes the margin between different classes in the feature space.
