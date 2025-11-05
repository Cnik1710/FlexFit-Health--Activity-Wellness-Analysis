# FlexFit-Health--Activity-Wellness-Analysis
 ---
## 🎯 Objective
Analyze and interpret **FlexFit Health’s wearable activity data** to uncover actionable insights that drive **user engagement, product optimization, and wellness outcomes**.
### **Project Purpose:**
  * Assess how active users are across months and activity types.
  * Identify engagement patterns based on distance, minutes, and calories burned.
  * Provide insights to improve **user motivation and fitness app performance**.
### **Key KPIs:**
  * **Total Users:** 33
  * **Total Duration:** 11 Months
  * **Average Calories Burned:** 2.30K
  * **Average Steps:** 7.64K
  * **Average Active Minutes:** 227.54
  * **Untracked Distance:** 13.49 Km
  * **Active Days:** 864 | **Inactive Days:** 76
### **Deliverables:**
  * Interactive **Power BI dashboard** showing user activity & wellness patterns.
  * Detailed analysis on **engagement trends and activity performance**.

---

## 📘 Project Overview 
### **Context Highlights:**
  * The analysis helps FlexFit Health’s **marketing, R&D, and product teams** understand:
  * How users engage with fitness trackers
  * Which neighborhoods are most active
  * Relationships between **steps, calories, and active minutes**
  * How activity varies by **age, location, and time**

Using **Excel, Power Query, and Power BI,** the project transforms raw activity data into an **interactive dashboard** that visualizes key metrics and trends — driving **data informed wellness strategies** and enhanced **user engagement**.


 ---
 
## 🗂️ Data Overview & Schema     
### **Data Source:**  
  * **Source:** Fictionalized fitness tracking dataset (inspired by open educational datasets).
  * **Data Type:** Structured user profiles and daily activity logs captured via FlexFit smart devices.
  * **Time Period:** Continuous daily activity tracking snapshot for the year **2016**.
### **Data Structure & Metrics:** 
  * **Key Index Types:** User-level records in the User Details dataset and date-level activity logs in the Activity dataset.
  * **Total Rows:** Users – **58**, Activity Logs – **~10,000+**.
  * **Categories:** Around 15+ features across three main segments:
      * **Demographics:** First Name, Last Name, Age, Address, Neighborhood, Date
      * **Performance Indicators:** Total vs. Tracker Distance, Logged Activity Distance, and Active Minutes split
  * **Calculated Metrics:** Derived fields using **custom DAX measure** for Power BI insights.
      * **Activity metrics:** Steps, Distance, Active Minutes (Light, Fairly, Very)
      * **Derived metrics:** Total Calories Burned,  Engagement Level, Tracker Distance, Untracked Distance, Total Active Time, Activity Intensity Score

 ---

## 💻 Tech Stack    
### **Tools:**
  * **Excel**
      * Data cleaning & preprocessing
  * **PowerQuery** 
      * ETL transformations
  * **PowerBI**
      * Visualization, DAX measures & dashboard design
      * DAX – Calculated measures and time intelligence
   * **PowerPoint**
      * Presentation and final dashboard snapshots
---
        
## 📈 Methodology & Analysis  
### **Prepare, Process & Analytical Approach:** 
  * **Data Preparation & Cleaning**
    * Handled missing and inconsistent activity logs.
    * Standardized numeric fields and validated record accuracy.
    * Merged datasets via **User ID** to build a unified analytical model.
  * **Data Modeling & Integration**
    * Established **User → Date → Activity** relationships.
    * Ensured **one-to-many integrity** (1 user → many activity records).
  * **Feature Engineering**
    * Derived new measures: **Active Minutes, Engagement Type, and Untracked Distance**.
    * Split **Address → Neighborhood** using Power Query for location insights.
  * Visualization Design
    * Built two interactive dashboards:
        * Engagement Overview
        * Activity Performance
    * Applied synchronized **slicers** for Age Group, User, and Timeframe filters.
  * Data Validation & Formatting
    * Verified data consistency across all relationships.
    * Standardized **date formats, distance units (KM), and column names** for Power BI readiness.

---
 
## ❓ Problem Statement     
FlexFit Health, a next-generation fitness technology company, provides smart wearables that track users’ daily movements, calories burned, and overall activity levels.

This project analyzes daily user-level activity data from **New York City residents (Brooklyn & Manhattan) over an 11-month period** to explore user engagement, fitness behaviors, and wellness outcomes.

### Key Questions:
  * How active are users across different months and age groups?
  * Which users show the highest calorie burn and active minutes?
  * What is the monthly trend of engagement levels?
  * How much of total distance remains untracked?


---

## 💡 Key Insights      
### **Top Findings:** 
  * April shows **highest activity & calorie burn** among all months.
  * **Young Adults (27.45%)** are the most engaged demographic.
  * **Untracked Distance:** ~13.49 Km — indicates device off-time or missing syncs.
  * **Active Minutes & Distance** strongly correlate with **higher engagement levels**.
  * Few users (e.g., Michael Brown, Andrew Garcia) dominate activity metrics.

### **Supporting Metrics:**
  * Monthly average active minutes gradually decline from May–December.
  * Low engagement spikes during months of reduced activity tracking.

---
 
## 📍 Conclusion
### **Summary:** 
  * User activity patterns show that engagement and consistency fluctuate across months and age groups. While a few users maintain strong calorie burn and active minutes, overall participation is highly seasonal.

  * Improving **data tracking accuracy**, encouraging **steady user engagement**, and tailoring **personalized fitness goals** can significantly enhance activity outcomes and platform adoption.

  * The analysis highlights that **smart insights from wearables** can empower both users and health teams — driving informed decisions that promote healthier, more active lifestyles.


---
 
## 🖥️ Dashboard Overview
### Engagement Overview
![image_alt](https://github.com/Cnik1710/FlexFit-Health--Activity-Wellness-Analysis/blob/1f12bdde4be1cf5b49d4e20f42c6fd290bb4ce6b/05.%20FlexFit%20Health%20-%20Activity%20%26%20Wellness%20Analysis%20(1)%20Dashboard.png)

### Activity Performance
![image_alt](https://github.com/Cnik1710/FlexFit-Health--Activity-Wellness-Analysis/blob/0dbed7cc30f0466b1137d92c4c4932653a48b6ea/06.%20FlexFit%20Health%20-%20Activity%20%26%20Wellness%20Analysis%20(2)%20Dashboard.png)

---
 
## ✅ Business Impact & Use Cases   
  * Enables **fitness app designers** to personalize activity goals and challenge levels based on user behavior trends.

  * Assists **health analysts** in identifying underperforming users and tailoring interventions for better wellness outcomes.

  * Helps **marketing teams** target users with low engagement levels through data-driven retention campaigns.

  * Supports **product teams** in enhancing engagement features such as streak tracking, goal reminders, and performance badges.

  * Guides **R&D teams** to understand device usage and improve sensor accuracy or battery optimization.

  * Allows **business strategy teams** to measure the **impact of product adoption by neighborhood and demographic segment**.

  * Provides **leadership** with a comprehensive view of user engagement KPIs to drive **data-informed decision-making**.

 ---
 
 ## 🙏 Acknowledgements & Contact 
 ### Project Analyst: Anik Chakraborty	
   📧 Email: anikc1710@gmail.com  
 ### Special Thanks To: 
 * Coding Ninjas – for project framework and guidance  
   
