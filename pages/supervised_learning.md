# ML : Supervised Learning

Machine learning algorithms can be categorized into different types based on their learning approaches, data characteristics, and task objectives. Supervised learning is one such type, where the model learns patterns from labeled data. In supervised learning, the input data is divided into features (input) and target (output). The goal is to predict the target or output using the provided features.

💡 Supervised learning encompasses two main techniques:
   - Classification
   - Regression

This GitHub page provides essential information and detailed insights into each technique, offering comprehensive and tailored questions for technical interviews for data scientists and machine learning engineers. It can help you master everything about classification and regression, ensuring you're well-prepared to pass your technical interview.

## List of Questions

### Q0- What does regression analysis mean?

- It is a statistical technique used in data science and machine learning fields.
- It aims to model the relationship between a dependent variable (y) and one or more independent variables (x).
- Modeling the relationship between inputs and output helps understand the relationship nature and strength.
- In addition,  it help making the correct predictions based on that understanding.
- Mainly, we use regression analysis to resolve problems and answer questions such as:
    - How does a change in one variable (independent variable) impact another variable (dependent variable)?
    - Can we predict the value of the dependent variable based on the values of one or more independent variables?
- It is widely used in various fields:
    - Economics
    - Finance
    - Biology
    - Psychology
    - Machine learning
- More details and additional questions regarding regression analysis can be found in the subsequent pages :
    -  [Regression analysis Part I](./regression_analysis_I.md)
    -  [Regression analysis Part II](./regression_analysis_II.md)

### Q1- What does classification analysis mean?
- It is one fundamental task in machine learning and data science that uses the supervised learning approach. 
- Commonly used in building predictive models to categorize data into predefined classes or categories based on input features or attributes.
- Algorithm learns patterns and relationships between input features and class labels.
- Once the model is trained, it can predict the class labels of new or unseen data instances.
- This predictive capability enables various applications such as:
    -  Spam detection
    -  Sentiment analysis
    -  Medical diagnosis
    -  Fraud detection
- More detailed questions and informations, regarding classification analysis, is provided in the subsequent pages :  [Classification analysis](./classification_analysis.md)

### Q2- How to determine whether to perform regression or classification analysis ?
- Briefly, it all depends on your target or output variable:
     - Continuous or numerical : Regression
     - Discrete or categorical or qualitative: Classification
- Examples of regression:
     - Predicting item prices
     - Estimating stock prices
     - Forecasting temperature
- Examples of classification:
     - Email is spam or not
     - Customer churn or not
     - Disease exist or not
     - Image classification
       
### Q3- What are the main differences between classification and regression problems?
- Target or output variable:
     - For regression is Continuous or numerical
     - For classification is categorical or qualitative
- Machine learning Models :
     - Some models are used for both classification and regression such as Decision trees, Random forests and neural networks etc.
     - Some models are only used for :
        - Classification: Logistic Regression , SVM etc.
        - Regression: Linear Regression, polynomial regression etc.
- Evaluation metrics are also different:
     - For regression : mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE).
     - For classification: accuracy, precision, recall, and F1-score   

