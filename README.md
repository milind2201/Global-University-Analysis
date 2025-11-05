# 🌍 Global University Ranking Dashboard

### **Overview**
The **Global University Ranking Dashboard** is an interactive data analytics project developed using **Power BI** and **SQL**.  
It provides a visual and data-driven perspective on how universities across the world perform based on factors like **research output, teaching quality, global engagement**, and **overall ranking scores**.

The project integrates multiple data sources to explore higher education trends across years, countries, and ranking categories, following a **MECE (Mutually Exclusive, Collectively Exhaustive)** analytical structure.

---

## 🎯 **Objectives**
- Deliver insights into the global distribution and performance of universities.  
- Identify key drivers that influence university rankings.  
- Track how performance metrics evolve across time and regions.  
- Provide a visual and analytical foundation for higher education research.

---

## 🧩 **MECE Breakdown**

### **1. Country Overview**
Analyzes national representation and trends in global university rankings.  
**Key Goals:**
- Determine the number of countries represented in the dataset.  
- Identify nations hosting the highest number of universities.  
- Highlight countries producing top-ranked institutions.  
- Recognize emerging education hubs based on performance patterns.

---

### **2. Institutional Profile**
Provides a detailed evaluation of individual universities’ performance indicators.  
**Key Goals:**
- Count and list all universities represented in the dataset.  
- Identify universities with the largest enrollments.  
- Evaluate student-to-staff ratios and resource efficiency.  
- Assess performance across teaching, research, and global engagement.

---

### **3. Yearly Trends**
Tracks performance and enrollment metrics over time.  
**Key Goals:**
- Identify the time span covered by the dataset.  
- Determine the year with the highest student growth.  
- Track progression in university rankings over time.  
- Analyze changes in international and female student representation.

---

### **4. Ranking Breakdown**
Examines the logic and composition of global ranking systems.  
**Key Goals:**
- Determine the number of ranking systems included.  
- Compare indicators and weightage across rankings.  
- Identify top-performing universities by score and category.  
- Reveal which metrics most influence overall ranking outcomes.

---

## 📊 **Tools & Technologies**
- **Power BI** – Data visualization and dashboard design  
- **SQL** – Data preprocessing and structured querying  
- **DAX** – Custom measures and KPIs  
- **Power Query** – Data cleaning and transformation  
- **Excel / CSV** – Data source integration  

---

## 🧠 **Key Insights**
- Balanced performance in research, teaching, and global outlook leads to stronger rankings.  
- Regional trends highlight Asia’s rising competitiveness in research excellence.  
- International engagement correlates strongly with institutional visibility.  
- Longitudinal analysis reveals shifts driven by academic collaboration and policy reform.

---

## 🧮 **Custom Metric**
A new composite measure — **Global Competitiveness Index (GCI)** — was introduced to capture the overall institutional performance:
```DAX
Global Competitiveness Index =
( [Research_Score] * 0.4 ) +
( [Teaching_Score] * 0.3 ) +
( [International_Outlook] * 0.3 )
