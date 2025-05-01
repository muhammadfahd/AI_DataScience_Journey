
# Day 15 - EDA & Missing Values
---

[Why EDA is important](#why-is-exploratory-data-analysis-eda-important)
[Handling Missing Values & importance](#handling-missing-values-why-is-it-important)



## Why is Exploratory Data Analysis (EDA) Important?

![Importance of EDA](https://www.questionpro.com/blog/wp-content/uploads/2023/10/How-important-Exploratory-Data-Analysis-in-Data-Science-1.jpg)

1. ### **Importance of Exploratory Data Analysis (EDA)**
When you encounter a new dataset, what's the first thing you should do? Should you train an ML model without understanding the data? Absolutely not! The first step should be EDA.

* **Understanding the Data**
Through EDA, we can better comprehend our data: identify the variables, their ranges, and the patterns present within them.

* **Identifying Challenges**: 
EDA helps us detect anomalies and unusual points that could create problems during model training.

* **Uncovering the Data's Story**:
Every dataset has a story. EDA allows us to bring that story to light.

2. ### **Data Preprocessing: Preparing Data for ML**
If EDA is the first step to understanding data, then data preprocessing is the step where we prepare the data for machine learning.

**Data Cleaning**:
Consider this: if the data has issues, can we train a good model? Therefore, we need to handle missing values and unusual points.

**Data Conversion**:
Machines only understand numbers, so we need to convert text data into numeric form.

**Feature Engineering**:
For ML models, we also create new features to improve the model's performance.

3. ### EDA and Data Preprocessing: The Backbone of Data Science and ML
**Enhanced Model Training**:
Proper data preprocessing leads to better accuracy and performance of ML models.

**Time-Saving**:
Through EDA and data preprocessing, we can identify and resolve potential future issues in advance.

**Conclusion**: 
What if EDA and data preprocessing didn't exist? ML projects would face numerous challenges. But with these two tools, you can have a better experience in data science and ML.

---

## Handling Missing Values: Why Is It Important?


### Introduction
In the world of data science and machine learning, data is everything. But what if your dataset is incomplete? What happens when some values are missing? This is one of the most common challenges data professionals face — and how you handle missing values can greatly affect the success of your analysis or model.

### What causes Missing Values?
Missing values are simply gaps in your data — places where a value should exist but doesn’t. These can occur for many reasons:

* Human error during data entry
* Data corruption or loss during collection or transfer
* Sensors or tools failing to record a value
* Participants skipping questions in surveys

![Missing Values](https://spotintelligence.com/wp-content/uploads/2024/10/missing-data-causes.jpg)
### Why Are Missing Values a Problem?
i. **Distort Analysis**
Most statistical analyses and machine learning models require complete data. Missing values can skew your results or cause your model to underperform.

ii. **Inaccurate Predictions**
If your training data has missing values, your model might learn patterns that don’t reflect reality. This leads to poor predictions and can even result in wrong business decisions.

iii. **Hide Real Patterns**
Sometimes, the fact that data is missing is a pattern in itself. For example, if most people who skip a survey question are from a particular age group, that’s important information you might miss if you just drop the missing data.

### Common Methods to Handle Missing Values

1. **Remove Data**
   * **Delete Rows**: Remove rows with missing data (good if few rows are affected).

   * **Delete Columns**: Remove columns with too many missing values.

⚠️ Use this method carefully — you may lose valuable data.

2. **Imputation (Filling in Missing Data)**
    * **Mean/Median/Mode Imputation**: Replace missing values with the average, median, or most frequent value.
    * **Forward/Backward Fill**: Fill missing values using nearby values (especially useful for time series).
    * **Model-Based Imputation**: Use predictive models to estimate missing values based on other features.

3. **Use Algorithms That Handle Missing Values**
Some ML algorithms like XGBoost or LightGBM can work even with missing values, making preprocessing easier.

4. **Best Practices**
   * **Explore Before Imputing**: Perform Exploratory Data Analysis (EDA) to understand where and why values are missing.

   * **Visualize Missing Data**: Use tools like seaborn or missingno to visually inspect missing patterns.

   * **Document Your Approach**: Always record how and why you handled missing values in a particular way.

### **Conclusion**
Handling missing values is not just a technical task — it’s a strategic decision that can influence the outcome of your entire project. Ignoring them can result in unreliable models and misleading insights, while proper handling ensures your data is clean, your models are accurate, and your decisions are data-driven.

> 💡 **Remember**: Better data leads to better models — and it all starts with handling missing values the right way.