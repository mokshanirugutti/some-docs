## index
### [1.EDA](#exploratory-data-analysis-eda)
### [2.Data Science Process](#data-science-process)
### [3.Linear regression](#linear-regression)
### [4.KNN](#k-nearest-neighbors)

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

### Linear Regression
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


### k-Nearest Neighbors
The k-nearest neighbors (KNN) algorithm is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. It is one of the popular and simplest classification and regression classifiers used in machine learning today.