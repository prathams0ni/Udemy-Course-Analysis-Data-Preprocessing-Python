# 📊 Udemy Course Analysis: Data Preprocessing.

## 📌 Project Overview
Udemy is one of the largest online learning platforms, offering thousands of courses across multiple domains such as Business, Technology, Music, Health, and more.  
With millions of learners worldwide, understanding what makes a course successful is crucial for instructors and platform decision-makers.

This project performs **end-to-end Data Preprocessing and Exploratory Data Analysis (EDA)** on Udemy course data to uncover insights related to pricing strategies, enrollments, content structure, and learner engagement.

---

## 🧩 Problem Statement
Not all Udemy courses perform equally in terms of enrollments and popularity.  
The challenge is to identify:
- Which factors influence course enrollments
- How pricing impacts learner interest
- Differences between free and paid courses
- The effect of course level, duration, and content structure on engagement

This project addresses these questions using data-driven analysis.

---

## 🎯 Objectives
- Clean and preprocess raw Udemy course data
- Handle missing values, duplicates, and inconsistencies
- Transform and engineer features for analysis
- Perform in-depth exploratory data analysis (EDA)
- Generate actionable insights for pricing and content strategy

---

## 📂 Dataset Information
- **Dataset Name:** Udemy Courses Dataset  
- **File Used:** `udemy_courses.csv`  
- **Data Type:** Tabular  
- **Key Features:**
  - Course title and category
  - Price
  - Number of subscribers (enrollments)
  - Number of lectures
  - Content duration
  - Course level

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:

- Data inspection and structure analysis
- Removal of duplicate and inconsistent records
- Handling missing values appropriately
- Standardization of categorical variables
- Feature transformation and creation of price bands
- Identification and analysis of outliers

Cleaned outputs generated:
- `clean_udemy.csv`
- `median_enrollments_by_price_band.csv`

---


## 🔍 Key Insights
- Free and low-priced courses generally attract higher enrollments
- Beginner-level courses tend to perform better in terms of subscribers
- Course structure (lectures and duration) influences engagement
- Strategic pricing aligned with learner expectations improves course reach

---

## ⚙️ Tools & Technologies Used
- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Jupyter Notebook**

---


---

## ⚠️ Assumptions & Limitations
**Assumptions:**
- Enrollment count reflects learner interest
- Dataset represents Udemy course trends reasonably well

**Limitations:**
- Instructor reputation and marketing effects are not included
- Ratings and reviews data may be incomplete
- Dataset represents a snapshot in time

---

## 📈 Future Scope
- Build predictive models to estimate course enrollments
- Apply clustering to group similar courses
- Create interactive dashboards using Power BI or Tableau
- Develop recommendation systems based on course features

---

## ✅ Conclusion
This project demonstrates how **systematic data preprocessing and detailed exploratory data analysis** can transform raw data into meaningful insights.

The findings can help instructors and platforms:
- Optimize pricing strategies
- Improve course design
- Enhance learner engagement through data-driven decisions

---
