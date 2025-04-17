# 📘 Student Exam Score Analysis

## 📌 Overview
This project analyzes student exam scores based on various personal and socio-economic factors. The dataset contains scores from three subjects (Math, Reading, and Writing) and includes attributes like parental education, lunch type, and test preparation status. The goal is to identify key factors influencing student performance.

## 📊 Dataset Details
- **📂 Source:** Fictional dataset of a public school
- **📈 Number of Records:** 30,000+
- **🔢 Features:** 15
- **⚠️ Contains Missing Values:** Yes (ideal for data cleaning and preprocessing)
- **🔗 Access Dataset:** [Kaggle - Students Exam Scores](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)

### 📑 Columns Description
- 🎭 `Gender`: Student's gender (Male/Female)
- 🌍 `EthnicGroup`: Ethnic group (Group A to E)
- 🎓 `ParentEduc`: Parental education level (High School to Master's)
- 🍽️ `LunchType`: Lunch type (Standard or Free/Reduced)
- 📚 `TestPrep`: Test preparation course completion status
- 👨‍👩‍👧 `ParentMaritalStatus`: Parent(s) marital status
- 🏃 `PracticeSport`: Frequency of sports practice
- 👶 `IsFirstChild`: Whether the student is the first child in the family
- 👨‍👩‍👧‍👦 `NrSiblings`: Number of siblings
- 🏫 `TransportMeans`: Mode of transport to school
- ⏳ `WklyStudyHours`: Weekly study hours
- ➗ `MathScore`: Math exam score (0-100)
- 📖 `ReadingScore`: Reading exam score (0-100)
- ✍️ `WritingScore`: Writing exam score (0-100)

## 🛠️ Tools & Technologies Used
- **💻 Programming Language:** Python
- **📚 Libraries:**
  - 🐼 `pandas` – Data manipulation and analysis  
  - 🔢 `numpy` – Numerical computations  
  - 📊 `matplotlib` – Data visualization  
  - 🎨 `seaborn` – Statistical data visualization  

## 🔍 Analysis Performed
- **🧼 Data Cleaning & Preprocessing:**
  - Handling missing values
  - Encoding categorical variables
  - Identifying outliers

- **📊 Exploratory Data Analysis (EDA):**
  - Distribution of scores
  - Correlation between features
  - Impact of socio-economic factors on scores
  - Effect of parental education on student performance
  - Influence of study habits and sports activities on scores

## 💡 Key Insights
- **📈 Test Preparation Matters:** Students who completed a test preparation course scored significantly higher on average than those who did not.
- **🎓 Parental Education Impact:** Higher parental education levels correlated with better student performance, especially in Reading and Writing scores.
- **⏳ Study Hours Influence:** Students who studied more than 10 hours per week performed better across all subjects, while those with less than 5 hours of study showed lower average scores.
- **👩‍🎓 Gender-Based Performance:** Female students generally outperformed male students in Reading and Writing, while Math scores showed less variation by gender.
- **⚽ Sports and Academic Performance:** Students who engaged in regular sports activities performed better overall, indicating a positive relationship between physical activity and cognitive performance.
- **🏡 Socio-Economic Influence:**
  - 🍽️ Students with a standard lunch type performed better than those with free/reduced lunch, indicating possible economic disparities in education.
  - 🚗 Private transport users had slightly better scores than those using school buses, potentially due to differences in commute time and fatigue levels.
- **👶 Sibling Influence:** First-born children performed slightly better than their younger siblings, possibly due to greater parental focus or responsibilities.
- **👨‍👩‍👧‍👦 Number of Siblings Impact:** The number of siblings a student has doesn't seem to affect their scores much. In Reading and Writing, the difference is just over 1 point, and in Math, it's around 1.7 points. Interestingly, students with 7 siblings scored the highest, while those with 6 siblings scored the lowest. This pattern might be a random variation, and other factors could be influencing these results.
- **🌎 Ethnic Group Trends:** There were notable differences in performance across ethnic groups, suggesting socio-cultural and economic factors influencing education.

## ❓ Additional Questions Based on Dataset
- 🚗 What is the impact of different transportation modes on student performance?
- 👨‍👩‍👧‍👦 How does the number of siblings affect a student's test scores?
- ⏳ Is there a correlation between weekly study hours and performance in different subjects?
- ⚽ Do students who practice sports regularly perform better academically?
- 💔 What is the effect of parental marital status on student scores?
- 🍽️ How does the type of lunch provided at school impact student performance?
- 🌎 Are there any significant differences in scores based on ethnic group?
- 📊 Does the combination of multiple socio-economic factors influence student performance more than any single factor alone?

## 🏆 Conclusion
This analysis provides insights into how various socio-economic and personal factors influence student exam scores. The findings can help educators and policymakers implement targeted interventions to support students in need, promote effective study habits, and bridge performance gaps due to socio-economic differences.

