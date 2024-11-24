# **Demographic and Lifestyle Data Analysis**  

EN : This project involves analyzing a dataset obtained from Kaggle that contains various demographic, health, and lifestyle-related features. The primary goals of the project are to explore and analyze the data, handle missing values, and perform detailed exploratory data analysis (EDA) with visualizations to extract insights.  

TR : Bu proje, çeşitli demografik, sağlık ve yaşam tarzıyla ilgili özellikler içeren, Kaggle'daki bir veri setinin analizini içerir. Projenin birincil hedefleri, verileri keşfetmek ve analiz etmek, eksik değerleri ele almak ve içgörüler çıkarmak için görselleştirmelerle ayrıntılı keşifsel veri analizi (EDA) gerçekleştirmektir.
---

## **Dataset Features**  
The dataset includes the following features:  
- **Name**: The full name of the individual.  
- **Age**: The age of the individual in years.  
- **Marital Status**: The marital status of the individual. Possible values: *Single, Married, Divorced, Widowed*.  
- **Education Level**: The highest level of education attained by the individual. Possible values: *High School, Associate Degree, Bachelor's Degree, Master's Degree, PhD*.  
- **Number of Children**: The number of children the individual has.  
- **Smoking Status**: Indicates whether the individual is a smoker or not. Possible values: *Smoker, Former, Non-smoker*.  
- **Physical Activity Level**: The level of physical activity undertaken by the individual. Possible values: *Sedentary, Moderate, Active*.  
- **Employment Status**: The employment status of the individual. Possible values: *Employed, Unemployed*.  
- **Income**: The annual income of the individual (in USD).  
- **Alcohol Consumption**: The level of alcohol consumption. Possible values: *Low, Moderate, High*.  
- **Dietary Habits**: The dietary habits of the individual. Possible values: *Healthy, Moderate, Unhealthy*.  
- **Sleep Patterns**: The quality of sleep. Possible values: *Good, Fair, Poor*.  
- **History of Mental Illness**: Whether the individual has a history of mental illness. Possible values: *Yes, No*.  
- **History of Substance Abuse**: Whether the individual has a history of substance abuse. Possible values: *Yes, No*.  
- **Family History of Depression**: Indicates if there is a family history of depression. Possible values: *Yes, No*.  
- **Chronic Medical Conditions**: Whether the individual has chronic medical conditions. Possible values: *Yes, No*.  

---

## **Project Workflow**  

### 1. **Handling Missing Data**  
- The original dataset did not include any missing data.  
- Random missing data was artificially created to simulate real-world scenarios.  
- Various methods were applied to analyze and handle the missing data effectively, including:  
  - Visualizing missing data patterns.  
  - Imputation techniques (e.g., mean, median, mode) by other categories.
  - Removal of missing data. 

### 2. **Exploratory Data Analysis (EDA)**  
- Performed detailed EDA to uncover patterns and relationships within the dataset.  
- Visualizations include:  
  - Distributions of numerical features like Age and Income.  
  - Comparisons between categorical variables (e.g., History of Mental Illness vs. Employment Status ).  
  - Relationships between Age groups, Income ranges, and other variables.  

### 3. **Visualizations**  
- Correlation matrix to identify relationships between variables.  
- Charts, plots for categorical data distributions.  
- Heatmaps and charts to analyze interactions linked to Age groups and Income ranges.  
etc.
---

## **Insights and Use Cases**  
- The dataset provides valuable insights into the demographic and lifestyle factors that may influence income levels and overall well-being.  
- The analysis can serve as a foundation for:  
  - Building predictive models to classify individuals based on lifestyle and health parameters.  
  - Identifying patterns for public health interventions or personalized lifestyle recommendations.  

---

## **Tools and Libraries**  
The following tools and libraries were used in this project:  
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  

---

## **Usage**  

The notebook is also available on Kaggle : https://www.kaggle.com/code/dannyachami/global-ai-hub-projesi-mental-illness-analysis

### **Dataset**  
The dataset used in this project is available on Kaggle. You can download it here : https://www.kaggle.com/datasets/anthonytherrien/depression-dataset  
---

## **Contributions**  
Contributions are welcome! Please fork this repository and submit a pull request.  
