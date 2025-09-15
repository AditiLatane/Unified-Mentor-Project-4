## Unified-Mentor-Task-4

# Olympics data analysis

## Aim

For a project based on Olympics data analysis, the primary focus will be on exploring and understanding the dataset, performing exploratory data analysis (EDA), and uncovering trends and insights related to athletes, countries, and sports over the years.

## Problem Statement

The primary goal is to:
1. Analyze the dataset to understand trends in medal distribution.
2. Identify the top-performing countries and athletes.
3. Study the gender distribution of events and medals.
4. Visualize the data using Python.

🔗[Dataset Link](https://drive.google.com/file/d/1EHMliUCEb8k6VhkpxK00oaY6GQtkwrhg/view?usp=sharing)

## Steps : 

### 1.  Data Preparation
1. Import libraries.
2. Load the dataset.
3. Clean the dataset (handling missing values).
4. Standardize categorical values
5. Check consistency between related columns
6. Dropping unnecessary columns
7. Normalize text values

### 2. Exploratory Data Analysis (EDA):
1. Summary statistics of the dataset.
2. Plot and analyze trends of medals across years.
3. Identify the top-performing athletes and countries.

### 3. Questions answered
1. Which city hosted maximum number of olympics?
2. Which city hosted the most events?
3. Understand the events themselves.
4. Which Athlete has won the most medals from a given period?
5. Put some light on gender ratio in winning teams?
6. Which country has won the most medals and how many in each year?
7. Can you tell me which country has dominated any particular sport?
8. Has any athlete changed his or her Event or Discipline or sport and still won the medal?
9. Which country has won the most medals and how many in each year? Elaborate the result and dive into details.(Pick any 5 country for this)


### 4. Predictive Analysis:
Train a machine learning model to predict whether an athlete will win a medal based on their country, sport, and other attributes.

Steps:
1. Encode categorical variables
2. Feature Engineering
    1. Country-Level/City-Level Features
    2. Sport/Discipline-Level Features
    3. Athlete-Level Features
    4. Gender-Based Features
    5. Event-Level Features
    6. Temporal Features

3. Splitting and Training Dataset
   
    Training shape: (12252, 20) (12252,)
   
    Testing shape: (3063, 20) (3063,)

5. Choose a Model
   1. Logistic Regression
   2. Decision Tree
   3. Random Forest
   4. XGBoost
   5. LightGBM
   
## 5. Results
   
| Model               | Accuracy (%) |
|----------------------|--------------|
| Random Forest        | 73.49        |
| XGBoost              | 71.73        |
| Decision Tree        | 71.07        |
| LightGBM             | 69.34        |
| Logistic Regression  | 41.01        |


## 6. Conclusion 

- **Top Performing Country**  
  - United States  

- **Top Athletes**  
  - Nemov, Alexei – 12 medals  
  - Andrianov, Nikolay – 12 medals  
  - Diabatin, Aleksandr – 11 medals  

- **Gender Participation**  
  - Male: 64%
  - Female: 36%  

- **Trend of Medals Over Years**  
  - Medals won increased steadily across the years.  
  - Significant peak observed in 2000, with over **2000 medals** awarded.  

- **Predictive Analysis**  
  - Random Forest achieved the **best accuracy: 73.49%**  


🔗 **Next Project:** [Unified-Mentor-Task-1](https://github.com/AditiLatane/Unified-Mentor-Task-1)
