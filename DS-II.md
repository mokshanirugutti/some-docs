## index
### [1.EDA](#exploratory-data-analysis-eda)
### [2.Data Science Process](#data-science-process)
### [3.Linear regression](#linear-regression)
### [4.KNN](#k-nearest-neighbors)
### [5.K-Means](#k-means)
### [6.SVM](#support-vector-machinesvm)
### [7.logistic regression](#logistic-regression)

### Exploratory data analysis (EDA) [^](#index)
Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods.
it helps data scientists to discover patterns, spot anomalies, test a hypothesis, or check assumptions.
Data scientists can use exploratory analysis to ensure the results they produce are valid and applicable to any desired business outcomes and goals

#### **Types of exploratory data analysis**

**Univariate non-graphical**. This is simplest form of data analysis, where the data being analyzed consists of just one variable. Since it’s a single variable, it doesn’t deal with causes or relationships. The main purpose of univariate analysis is to describe the data and find patterns that exist within it.

**Univariate graphical**. Non-graphical methods don’t provide a full picture of the data. Graphical methods are therefore required. Common types of univariate graphics include:

*Stem-and-leaf plots*, which show all data values and the shape of the distribution.

*Histograms*, a bar plot in which each bar represents the frequency (count) or proportion (count/total count) of cases for a range of values.

*Box plots*, which graphically depict the five-number summary of minimum, first quartile, median, third quartile, and maximum.
 
**Multivariate nongraphical:** Multivariate data arises from more than one variable. Multivariate non-graphical EDA techniques generally show the relationship between two or more variables of the data through cross-tabulation or statistics.

**Multivariate graphical:** Multivariate data uses graphics to display relationships between two or more sets of data. The most used graphic is a grouped bar plot or bar chart with each group representing one level of one of the variables and each bar within a group representing the levels of the other variable.

Most common data science programming languages/Tools used to create an EDA include: `Python`, `R`

---

### Data Science process [^](#index)

The data science process is a structured approach that guides data scientists in transforming raw data into actionable insights. It typically involves the following key steps:

**1. Problem Definition:**

* **Clearly define the problem:** This is the starting point, where you identify the specific question or problem you want to solve using data.
* **Set clear objectives:** Define what you want to achieve with the analysis. Are you trying to predict future outcomes, classify data, or identify patterns?
* **Gather domain knowledge:** Understand the context of the problem and the relevant industry or field.

**2. Data Collection:**

* **Identify data sources:** Determine where you will obtain the necessary data. This could involve internal databases, external sources like APIs, or public datasets.
* **Gather data:** Collect the relevant data using appropriate methods, such as web scraping, database queries, or data APIs.
* **Ensure data quality:** Verify the accuracy, completeness, and consistency of the collected data.

**3. Data Preparation:**

* **Data cleaning:** Handle missing values, outliers, and inconsistencies in the data.
* **Data transformation:** Convert data into a suitable format for analysis, such as normalizing or standardizing values.
* **Feature engineering:** Create new features from existing data to improve model performance.

**4. Exploratory Data Analysis (EDA):**

* **Understand the data:** Explore the data using descriptive statistics and visualizations to get a sense of its distribution, relationships, and patterns.
* **Identify trends and patterns:** Look for meaningful insights and anomalies in the data.
* **Formulate hypotheses:** Based on the EDA, develop hypotheses to be tested with further analysis.

**5. Model Building:**

* **Select appropriate models:** Choose machine learning algorithms or statistical models that are suitable for the problem and data type.
* **Train models:** Use the prepared data to train the selected models.
* **Evaluate models:** Assess the performance of the models using appropriate metrics, such as accuracy, precision, recall, or F1-score.

**6. Model Deployment:**

* **Choose a deployment platform:** Select a suitable platform to deploy the model, such as a web application, API, or cloud service.
* **Integrate the model:** Integrate the model into a production environment to make predictions or automate decisions.
* **Monitor performance:** Continuously monitor the model's performance and retrain it as needed to maintain accuracy.

**7. Communication of Results:**

* **Present findings:** Communicate the results of the analysis to stakeholders in a clear and concise manner.
* **Visualize insights:** Use visualizations to make the results more understandable and impactful.
* **Provide actionable insights:** Translate the findings into actionable recommendations for decision-making.

The data science process is often iterative, with steps being revisited as needed.

---

### Linear Regression [^](#index)
Linear regression is a data analysis technique that predicts the value of unknown data by using another related and known data value. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable.


#### **Why is linear regression**
Linear regression models are relatively simple and provide an easy-to-interpret mathematical formula to generate predictions. Linear regression is an established statistical technique and applies easily to software and computing. Because linear regression is a long-established statistical procedure, the properties of linear-regression models are well understood and can be trained very quickly.

#### **How does linear regression work?**
At its core, a simple linear regression technique attempts to plot a line graph between two data variables, x and y. As the independent variable, x is plotted along the horizontal axis. Independent variables are also called explanatory variables or predictor variables. The dependent variable, y, is plotted on the vertical axis. You can also refer to y values as response variables or predicted variables.

#### **Types of Linear Regression**
- Simple Linear Regression:
    - One independent variable.
    - Example: Predicting house price based on size.
- Multiple Linear Regression:
    - Two or more independent variables.
    - Example: Predicting house price based on size, location, and number of bedrooms.



#### **Applications in Data Science**
- Predicting sales revenue based on advertising spend.
- Estimating housing prices based on features like location, size, and amenities.
- Forecasting stock prices based on historical trends.
- Modeling customer lifetime value in business.


---


### [k-Nearest Neighbors](https://www.ibm.com/think/topics/knn) [^](#index)

The k-nearest neighbors (KNN) algorithm is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. It is one of the popular and simplest classification and regression classifiers used in machine learning today.
While the KNN algorithm can be used for either regression or classification problems, it is typically used as a classification algorithm

**Uses** : handwriting detection, image recognition, and video recognition

---

### [k-means](#https://www.ibm.com/think/topics/k-means-clustering) [^](#index)
K-means is a clustering algorithm that partitions data into groups based on the distance between their centroids

**How it works** 
K-means is an iterative algorithm that starts by choosing the number of clusters, k, and then defines a centroid for each cluster. The algorithm then assigns each observation to the cluster with the nearest centroid.

**used for** 
K-means is a type of unsupervised learning algorithm that's used to solve clustering problems. It's also known as Lloyd's algorithm.

**How to measure distance** 
The distance between data points is used to determine how similar they are. A shorter distance means the observations are more similar. One way to measure distance is Euclidean distance, which is the same distance used in the Pythagorean theorem. 

**Stopping criteria**
The algorithm stops when the centroids of new clusters don't change, the points remain in the same cluster, or the maximum number of iterations is reached.

---

### [Support Vector Machine(SVM)](#https://www.ibm.com/think/topics/support-vector-machine) [^](#index)
A support vector machine (SVM) is a supervised machine learning algorithm that classifies data by finding the best hyperplane to separate data points into different classes: 
SVMs are used in many fields, including bioinformatics, because they: Can handle large datasets with many predictor values, Can learn complex models, Are less likely to overfit than other algorithms, and Have high learning ability. 

**How they work** 
SVMs plot data points in an n-dimensional space, where n is the number of features. They then find the hyperplane that maximizes the distance between classes, while ignoring outliers.  

**History** 
SVMs were developed in the 1990s by Vladimir N. Vapnik and his colleagues.   

**Support Vector Classifier** 
SVC is a specific implementation of the SVM algorithm that's designed for classification tasks.  

**Kernels** 
Kernels help transform data points to make them more separable when linear separation isn't possible.   

**Overfitting** 
Overfitting is when a model performs well on training data but can't generalize to new data. SVMs are less likely to overfit than other algorithms.  

---

### [Navie Bayes](https://www.ibm.com/think/topics/naive-bayes) [^](#index)
Naïve Bayes is a supervised machine learning algorithm that uses probability to classify events. It's based on Bayes' theorem and is a type of probabilistic classifier that assumes that features are independent of each other.
Here are some characteristics of Naïve Bayes: 

**Simplicity** 
Naïve Bayes is one of the simplest Bayesian network models. It's known for being fast, simple, and accurate.

**Applications** 
Naïve Bayes is used for a variety of tasks, including text classification, spam filtering, recommendation systems, and multi-class prediction. 

**Advantages** 
Naïve Bayes works well on large datasets and performs well on both binary and multi-class classification.

**Disadvantages** 
One disadvantage of Naïve Bayes is the "zero-frequency problem". This occurs when there are no occurrences of a class label and a certain attribute value together, which results in a zero probability estimate.  

---
### [logistic regression](#https://aws.amazon.com/what-is/logistic-regression/) [^](#index)
Logistic regression is a data analysis technique that uses mathematics to find the relationships between two data factors.
It then uses this relationship to predict the value of one of those factors based on the other. The prediction usually has a finite number of outcomes, like yes or no.

Logistic regression is a supervised learning algorithm that uses a logistic function to predict the probability of a target variable based on one or more predictor variables. 

logistic function is a mathematical function used to model the relationship between input variables (features) and the probability of a binary outcome. It is also known as the **sigmoid function** because of its S-shaped curve.

### Formula of the Logistic Function:

$$
f(z) = \frac{1}{1 + e^{-z}}
$$

Here:
- f(z): The logistic function's output, which represents a probability value between 0 and 1.
- z: The linear combination of input features and their coefficients, expressed as:
  z = β₀ + β₁x₁ + β₂x₂ + ... + βₙxₙ
  where:
  - β₀: The intercept (bias term).
  - β₁, β₂, ..., βₙ: Coefficients for the input features.
  - x₁, x₂, ..., xₙ: Input features.

It's used for binary classification problems, like predicting whether a person will buy a house or not based on their age, income, and other factors.
It's widely used in applications such as customer churn prediction, credit risk assessment, and medical diagnosis. It's also used for feature selection and engineering.
