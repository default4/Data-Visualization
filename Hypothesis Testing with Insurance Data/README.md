# Hypothesis Testing with Insurance Data

A statistical analysis project that aims to understand the relationships between various factors and insurance charges using hypothesis testing.

## Project Goals

1. **Understand if there's a significant difference in insurance charges based on:**
   - Smoking status
   - Gender
   - Region

2. **Explore the association between:**
   - Gender and smoking status
   - Region and smoking status

## Steps and Results

### 1. Data Exploration

- **Dataset Columns**: Age, Gender, BMI, Number of Children, Smoker Status, Region, Insurance Charges.
- **Basic Statistics**: Provided insights into the distribution, averages, and potential outliers in the data.

### 2. Two Sample Tests

#### a. Insurance Charges: Smokers vs. Non-Smokers

- **T-test Result**: Extremely significant (p-value < 0.05).
- **Conclusion**: Smokers have higher insurance charges than non-smokers.
  
#### b. Insurance Charges: Males vs. Females

- **T-test Result**: Significant (p-value < 0.05).
- **Conclusion**: There's a difference in insurance charges between males and females, though not as pronounced as between smokers and non-smokers.

### 3. Multiple Sample Tests (ANOVA)

#### a. Insurance Charges across Different Regions

- **ANOVA Result**: Significant difference (p-value < 0.05).
- **Conclusion**: Insurance charges vary based on the region.

### 4. Non-Numeric Tests (Chi-Squared Test)

#### a. Association between Gender and Smoking Status

- **Chi-Squared Result**: Significant association (p-value < 0.05).
- **Conclusion**: There's a statistically significant association between an individual's gender and their smoking status.
  
#### b. Association between Region and Smoking Status

- **Chi-Squared Result**: Not significant (p-value > 0.05).
- **Conclusion**: There isn't a statistically significant association between the region and smoking status.

## Visualization

Various plots like box plots, histograms, and bar plots were used to visually support and represent the results of the hypothesis tests.
