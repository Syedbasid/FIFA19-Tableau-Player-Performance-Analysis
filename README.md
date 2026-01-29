# FIFA 19 Player Performance & Market Analysis – Tableau Project

## 📌 Project Overview
This project presents an end-to-end exploratory and visual analysis of the FIFA 19 player dataset using Tableau.  
The objective is to analyze player performance, market value, skills, physical attributes, and growth potential through multiple analytical perspectives and an interactive dashboard.

The project includes **10 detailed analyses**, each addressing a specific football analytics question, and culminates in a unified interactive Tableau dashboard.

---

## 🎯 Business Problem
Football clubs, scouts, and analysts require data-driven insights to:
- Evaluate player performance across positions and nationalities
- Understand the relationship between market value, wages, and ratings
- Identify skill specialization by position
- Detect high-potential players for long-term investment
- Analyze squad composition at club level

This project answers these questions using structured visual analytics.

---

## 📂 Dataset Description
Dataset: **FIFA 19 Player Dataset**

The dataset contains comprehensive player-level information, including:
- Demographics: Age, Nationality, Height, Weight
- Performance: Overall Rating, Potential
- Market Information: Market Value, Wage
- Playing Details: Position, Skills, Work Rate, Body Type
- Club Information: Club, Contract Valid Until

---

## 🔧 Data Preparation
- Verified and corrected data types for numerical and categorical fields
- Converted Market Value and Wage into numeric format
- Handled missing and invalid values using filters
- Created calculated fields where required
- Applied correct aggregation logic (AVG for ratings, COUNT for players)

---

## 📊 Detailed Analysis Breakdown (All 10 Tasks)

---

### 1️⃣ Player Performance Analysis
**Question:** How do overall ratings differ by nationality, age, and position?  
**Visualization:** Bar Chart / Heatmap  
**Insight:**  
Certain nationalities consistently produce higher-rated players, especially in attacking and midfield positions. Players in their prime age range show stronger overall ratings.

---

### 2️⃣ Market Value and Wage Comparison
**Question:** What is the relationship between market value and wage?  
**Visualization:** Scatter Plot  
**Insight:**  
Market value and wages are strongly correlated. Higher-rated players typically command both higher wages and higher market values.

---

### 3️⃣ Player Position and Skill Analysis
**Question:** Which positions exhibit the highest average skill ratings?  
**Visualization:** Bar Chart  
**Skills Analyzed:** Finishing, Dribbling, Ball Control  
**Insight:**  
Forwards excel in attacking skills, midfielders show balanced skill sets, and defenders have lower attacking skill values, confirming positional specialization.

---

### 4️⃣ Potential vs Overall Rating Analysis
**Question:** How does player potential compare with current performance?  
**Visualization:** Scatter Plot with reference lines  
**Insight:**  
Younger players often have higher potential relative to their current overall rating, highlighting future growth opportunities.

---

### 5️⃣ Age Distribution and Player Types
**Question:** How is player age distributed across body types and work rates?  
**Visualization:** Histogram  
**Insight:**  
Most players fall within the prime age range. Lean body types are more common among younger players, while experienced players show varied work rates.

---

### 6️⃣ International Reputation vs Weak Foot Analysis
**Question:** Is international reputation related to weak foot rating?  
**Visualization:** Scatter / Bubble Chart  
**Insight:**  
Players with higher international reputation generally possess stronger weak foot ratings, though the relationship is moderate rather than absolute.

---

### 7️⃣ Contract Information Overview
**Question:** How does contract length vary by club and potential?  
**Visualization:** Bar Chart  
**Insight:**  
Top clubs tend to secure high-potential players with longer contracts, indicating long-term investment strategies.

---

### 8️⃣ Height and Weight Distribution
**Question:** How do physical attributes vary by position and body type?  
**Visualization:** Scatter Plot  
**Insight:**  
Defenders and goalkeepers are generally taller and heavier, while forwards and wingers are lighter and shorter, reflecting role-based physical requirements.

---

### 9️⃣ Top Players by Market Value
**Question:** Which players have the highest market value?  
**Visualization:** Ranked Bar Chart  
**Insight:**  
Top-valued players are typically younger or in their prime and have high overall ratings, often belonging to elite clubs.

---

### 🔟 Top Performing Clubs
**Question:** Which clubs have the strongest squads and what is their age composition?  
**Visualization:**  
- Bar Chart: Average Overall Rating by Club  
- Histogram: Age Distribution within Top Clubs  

**Insight:**  
Top-performing clubs maintain high average squad ratings and primarily rely on players in their prime age range, balancing experience with performance.

---

## 🧩 Dashboard Design & Interactivity
- Combined key analyses into a single interactive Tableau dashboard
- Used containers for a clean and structured layout
- Implemented global filters:
  - Age
  - Position
  - Nationality
- Enabled dashboard actions such as **Use as Filter**
- Designed informative tooltips for player-level details

---

## 🧠 Key Takeaways
- Player performance varies significantly by nationality, position, and age
- Market value closely aligns with wages and overall ratings
- Skill sets are strongly position-dependent
- Younger players present higher development potential
- Top clubs strategically balance performance and squad age

---

## 🛠 Tools & Technologies Used
- Tableau Desktop
- FIFA 19 Dataset
- GitHub (version control & documentation)

---

---

## 👤 Author
**Name:** Syed Basid S


