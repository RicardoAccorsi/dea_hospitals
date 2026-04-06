# 🏥 Hospital Productivity Analysis Project

This project analyzes the **productivity and efficiency of Brazilian healthcare regions** using **Data Envelopment Analysis (DEA)** and the **Malmquist Productivity Index**. The goal is to understand how hospital performance evolves over time and identify patterns across regions.

---

## 📁 Project Structure

- **Bases**: datasets used in the analysis  
- **Notebooks**: all project notebooks  
- **Figuras**: visualizations generated during the analysis  

---

## 🚀 Overview

Healthcare systems operate under resource constraints, making efficiency and productivity critical. This project applies **quantitative methods from Operations Research** to evaluate how hospital performance changes over time.

We combine:
- **Clustering techniques** to group similar health regions  
- **Malmquist Index** to measure productivity dynamics  

This allows us to analyze not only *how efficient regions are*, but also *how their performance evolves*.

---

## 📓 Main Notebooks

### `clusterizacao_malmquist.ipynb`
- Performs **clustering of health regions** based on methodologies used by the **Brazilian Federal Court of Accounts (TCU)**  
- Computes the **Malmquist Productivity Index** from **June 2019 to March 2024**

---

### `analise_resultados.ipynb`
Presents the main analyses derived from the Malmquist Index:

- Decomposition into:
  - **Catch-up effect (efficiency change)**
  - **Frontier shift (technological change)**
- Monthly productivity evolution  
- General visualizations  
- Analysis of:
  - Top 20 regions with **highest productivity growth**
  - Top 20 regions with **largest decline**
- Cumulative productivity  
- Trends in **efficiency and productivity** across different **hospital stratifications**  

---

## 📊 Results & Insights

### 🔍 Productivity Dynamics
The analysis shows that productivity changes are driven by two main components:
- **Catch-up effect:** improvements in how efficiently regions use resources  
- **Frontier shift:** changes in the overall production frontier (technology/system-level changes)

Different regions exhibit distinct patterns, with some improving efficiency while others benefit from broader system advancements.

---

### 📈 Heterogeneity Across Regions
There is significant variation in performance:
- Some regions show **consistent productivity gains over time**
- Others experience **persistent decline**, indicating structural inefficiencies
- The top-performing regions differ substantially from the worst-performing ones, highlighting inequality in healthcare delivery

---

### 🏥 Hospital Stratification Effects
When analyzing hospitals by characteristics (e.g., size or structure):
- Productivity trends vary across groups  
- Certain types of hospitals demonstrate **more stable efficiency gains**, while others are more volatile  

---

### 📉 Cumulative Productivity Trends
Cumulative analysis reveals:
- Long-term divergence between regions  
- Some regions consistently move closer to the efficiency frontier  
- Others fall behind, suggesting the need for targeted policy intervention  

---

### 🎯 Key Takeaways
- Hospital productivity is **highly heterogeneous across regions**  
- Improvements are not uniform and depend on both **efficiency gains and systemic changes**  
- The Malmquist Index provides a powerful framework to track **dynamic performance over time**  
- Results can support **data-driven policy and resource allocation decisions**  

---

## 🛠️ Methods & Tools

- **Python**
- **R**
- **Pandas / NumPy**
- **Data Envelopment Analysis (DEA)**
- **Malmquist Productivity Index**
- **Clustering via K-means**
- **Data visualization (Matplotlib / Seaborn)**

---
