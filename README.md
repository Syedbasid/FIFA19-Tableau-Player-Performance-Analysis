# FIFA 19 Player Performance & Market Analysis – Tableau Project

## 📌 Project Overview
This project presents a comprehensive exploratory and visual analysis of the FIFA 19 player dataset using Tableau.  
The objective is to analyze player performance, market value, skills, physical attributes, contract details, and growth potential through multiple analytical perspectives and an interactive dashboard.

The project consists of **11 distinct analyses**, each answering a specific football analytics question, and is presented through an interactive Tableau dashboard with filters and actions.

---

## 🎯 Business Problem
Football clubs, scouts, and analysts require data-driven insights to:
- Evaluate player performance across nationalities, ages, and positions
- Understand how market value and wages relate to player quality
- Identify skill specialization and physical attributes by position
- Detect high potential players for future investment
- Analyze club level squad quality and composition

This project addresses these needs using structured data visualization.

---

## 📂 Dataset Description
Dataset: **FIFA 19 Player Dataset**

The dataset includes:
- Demographics: Age, Nationality, Height, Weight
- Performance metrics: Overall Rating, Potential
- Market attributes: Market Value, Wage
- Playing characteristics: Position, Skills, Work Rate, Body Type
- Club and contract information

---

## 🔧 Data Preparation & Processing
- Verified correct data types for numerical and categorical fields
- Converted Market Value and Wage into numeric format
- Handled missing and invalid values using filters
- Created calculated fields where required
- Applied correct aggregation logic (AVG for ratings, COUNT for players)

---

## 📊 Detailed Analysis Breakdown (ALL 11 ANALYSES)

---

### 1️⃣ Player Performance Analysis
**Question:** How do overall ratings differ by nationality, age, and position?  
**Visualization:** Bar Chart
**Insight:**  
Certain nationalities consistently produce higher-rated players, especially in attacking and midfield positions. Players in their prime age range show stronger overall ratings.

---

### 2️⃣ Market Value and Wage Comparison
**Question:** What is the relationship between market value and wage?  
**Visualization:** Scatter Plot  
**Insight:**  
Market value and wages show a strong positive correlation, particularly for high-rated players.

---

### 3️⃣ Player Position and Skill Analysis
**Question:** Which positions exhibit the highest average skill ratings?  
**Visualization:** Bar Chart  
**Skills Analyzed:** Finishing, Dribbling, Ball Control  
**Insight:**  
Forwards excel in attacking skills, midfielders show balanced skill sets, and defenders display lower attacking skill values.

---

### 4️⃣ Potential vs Overall Rating Analysis
**Question:** How does player potential compare with current performance?  
**Visualization:** Scatter Plot with reference lines  
**Insight:**  
Younger players frequently show higher potential relative to their current overall rating, indicating strong growth prospects.

---

### 5️⃣ Age Distribution and Player Types
**Question:** How is player age distributed across body types and work rates?  
**Visualization:** Histogram  
**Insight:**  
Most players fall within the prime age range, with lean body types more common among younger players.

---

### 6️⃣ International Reputation vs Weak Foot Analysis
**Question:** Does international reputation correlate with weak foot rating?  
**Visualization:** Scatter / Bubble Chart  
**Insight:**  
Players with higher international reputation generally possess better weak foot ratings, though the relationship is moderate.

---

### 7️⃣ Contract Information Overview
**Question:** How does contract length vary by club and player potential?  
**Visualization:** Bar Chart  
**Insight:**  
Clubs with longer average contract durations tend to retain higher-potential players, reflecting long-term investment strategies.

---

### 8️⃣ Height and Weight Distribution Analysis
**Question:** How do physical attributes vary by position and body type?  
**Visualization:** Scatter Plot  
**Insight:**  
Defenders and goalkeepers are generally taller and heavier, while forwards and wingers are lighter and shorter.

---

### 9️⃣ Top Players by Market Value
**Question:** Which players have the highest market value?  
**Visualization:** Ranked Bar Chart  
**Insight:**  
Top-valued players are typically younger or in their prime, have high overall ratings, and belong to elite clubs.

---

### 🔟 Top Performing Clubs Analysis
**Question:** Which clubs have the highest average overall ratings and what is their age composition?  
**Visualization:**  
- Bar Chart (Average Overall Rating by Club)  
- Histogram (Age Distribution within Top Clubs)  

**Insight:**  
Top-performing clubs maintain high squad quality and rely primarily on players in their prime age range.

---

### 1️⃣1️⃣ Interactive Dashboard Integration (FINAL ANALYSIS)
**Question:** How can all analyses be combined for dynamic exploration?  
**Visualization:** Interactive Tableau Dashboard  

**Insight:**  
All key analyses are integrated into a single dashboard with global filters (Age, Position, Nationality) and dashboard actions. This enables dynamic cross-analysis and improves decision-making by allowing users to explore player and club insights interactively.

---

## 🧩 Dashboard Design & Interactivity
- Combined all major analyses into a single Tableau dashboard
- Used containers for a clean and structured layout
- Implemented global filters:
  - Age
  - Position
  - Nationality
- Enabled dashboard actions such as **Use as Filter**
- Designed informative tooltips for detailed player-level insights

---

## 🧠 Key Takeaways
- Player performance varies significantly by nationality, position, and age
- Market value is closely aligned with wages and overall ratings
- Skill specialization is strongly position-dependent
- Younger players often present higher development potential
- Top clubs balance squad performance with age composition
- Interactive dashboards enhance exploratory analysis

---

## 🛠 Tools & Technologies Used
- Tableau Desktop
- FIFA 19 Dataset
- GitHub (project hosting and documentation)

---

## 👤 Author
**Name:** Syed Basid S

