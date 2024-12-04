# Alternate Dimensional Analysis: Spaceship Titanic

This repository contains an analysis of the **Spaceship Titanic** dataset, exploring the mysterious case of passengers transported to an alternate dimension during a catastrophic spacetime anomaly. By leveraging data science and machine learning, we aim to predict whether a passenger was transported, using features such as demographics, spending habits, and CryoSleep status.

---

## **Background**

The **Spaceship Titanic**, a luxurious interstellar vessel, encountered a spacetime anomaly, resulting in the unexplained disappearance of certain passengers. This project delves into this intriguing event, utilizing passenger data to build a predictive model for classifying transported passengers. The analysis blends science fiction with data science, providing actionable insights into passenger behaviors.

---

## **Dataset**

The dataset consists of records for approximately 8,700 passengers, two-thirds of the total aboard. The training data includes details on whether passengers were transported to another dimension during the anomaly. Each record contains the following features:

- **PassengerId**: Unique identifier for each passenger (format: `gggg_pp`, where `gggg` = group, `pp` = position within the group).  
- **HomePlanet**: Passenger's planet of origin.  
- **CryoSleep**: Indicator of whether the passenger was in suspended animation during the voyage.  
- **Cabin**: Assigned cabin (format: `deck/num/side`).  
- **Destination**: Intended disembarkation planet.  
- **Age**: Passenger's age.  
- **VIP**: Indicator of VIP services purchased.  
- **RoomService, FoodCourt, ShoppingMall, Spa, VRDeck**: Spending amounts on various amenities.  
- **Name**: Passenger's full name.  
- **Transported**: Target variable indicating whether the passenger was transported (binary).

---

## **Objectives**

1. **Explore Demographics**: Analyze passenger distributions by age, origin, and CryoSleep status.  
2. **Understand Spending Habits**: Investigate how passengers utilized onboard amenities.  
3. **Build Predictive Models**: Develop a machine learning model to classify transported passengers.  
4. **Key Questions**:
   - What factors influenced passenger transportation?  
   - How does CryoSleep affect transportation likelihood?  
   - What are the spending patterns of transported vs. non-transported passengers?  

---

## **Tools and Libraries**

- **Python**: Core programming language for analysis.  
- **pandas**: Data manipulation and preprocessing.  
- **matplotlib**: Visualization of trends and distributions.  
- **seaborn**: Advanced visualizations for statistical insights.  
- **Jupyter Notebook**: Interactive environment for code and documentation.

---

## **Analysis Workflow**

### **1. Data Preparation**
- Load and clean the dataset:
  - Handle missing values.
  - Convert data types (e.g., categorical encoding).  
  - Engineer features where necessary.  

### **2. Exploratory Data Analysis (EDA)**
- **HomePlanet Analysis**: Visualize passenger distribution by origin.  
- **CryoSleep Status**: Assess the impact of suspended animation.  
- **Age Distribution**: Understand the demographic spread.  
- **Spending Patterns**: Examine amenity usage and preferences.  

### **3. Insights**
- Relationship between age and spending habits.  
- CryoSleep status and likelihood of being transported.  
- Spending behavior differences across home planets.  

### **4. Predictive Modeling**
- Build and evaluate machine learning models to predict transportation status:  
  - Train/test split for validation.  
  - Address class imbalance.  
  - Optimize hyperparameters for better accuracy.

---

## **Visualizations**

- **Bar Charts**: Passenger distributions by origin and spending categories.  
- **Histograms**: Age distribution and spending habits.  
- **Heatmaps**: Correlations among features.  
- **Line Charts**: Spending trends across age groups.  

---

## **Key Findings**

1. **Transportation Trends**: Certain demographics (e.g., CryoSleep passengers) were more likely to be transported.  
2. **Spending Insights**: Passengers with higher spending at specific amenities showed different transportation probabilities.  
3. **HomePlanet Influence**: Passengers from different planets exhibited distinct spending behaviors and transportation rates.  
4. **CryoSleep Effect**: Being in CryoSleep significantly influenced transportation likelihood.

---

## **Challenges**

- **Imbalanced Data**: Adjusting for unequal representation in transportation status.  
- **Feature Selection**: Identifying key features affecting predictions.  
- **Model Optimization**: Tuning hyperparameters for the best results.

---

## **Conclusion**

This project provides a comprehensive analysis of the Spaceship Titanic dataset, combining advanced data techniques with creative problem-solving. By understanding the factors influencing passenger transportation, we gain valuable insights into passenger behavior and interstellar travel dynamics.

---
