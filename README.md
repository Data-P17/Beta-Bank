# Beta-Bank
A Supervised Learning project. Displaying Customer Retention Prediction Model
At Beta Bank, customer attrition, even in small numbers, translates to a significant loss in long-term revenue. Our data confirms what many in the industry already know: it’s far more cost-effective to retain an existing customer than to acquire a new one. And yet, we continue to lose a portion of our client base.
This presentation is about changing that trajectory.
I’ll walk you through how we can leverage customer behavior data to predict churn before it happens. Using advanced predictive modeling, we can identify at-risk clients early and intervene with strategies designed to retain them — preserving not only immediate revenue but also long-term customer value.
The goal is simple: use data to inform proactive retention efforts, reduce churn, and ultimately strengthen our competitive position in the market.
Let’s look at the numbers, and the opportunity, ahead of us.

## Work Flow

1. **Import Libraries**

   * Import Python libraries needed for data analysis, visualization, preprocessing, machine learning, and model evaluation.

2. **Data Exploration**

   * Load each CSV dataset
   * Review dataset structure, columns, and data types

3. **Data Cleaning**

   * Identify and remove duplicate records
   * Identify and handle missing values

4. **Feature Engineering**

   * Apply ordinal encoding to categorical features

5. **Model Development**

   * Split data into features and target variables
   * Analyze class distribution
   * Split data into training, validation, and testing datasets
   * Analyze the dataset splits

6. **Model Training**

   * Train Logistic Regression model
   * Train Random Forest Classifier model

7. **Model Adjustments**

   * Apply weighted class adjustments
   * Apply threshold adjustments
   * Perform final testing

8. **Model Metrics & Validation**

   * Measure AUC-ROC score
   * Measure ROC Curve performance
   * Perform sanity testing

9. **Conclusion**

   * Summarize findings, model results, and insights
