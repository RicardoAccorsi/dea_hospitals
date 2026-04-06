# 🏥 Hospital Productivity Analysis Project

This project analyzes the **productivity and efficiency of Brazilian healthcare regions** using **Data Envelopment Analysis (DEA)** and the **Malmquist Productivity Index**. The goal is to understand how hospital performance evolves over time and identify patterns across regions.

---

## 📁 Project Structure
- **Notebooks**: all project notebooks  

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

### 📈 Overall Productivity Growth
Hospital productivity in Brazil’s public health system (SUS) increased by **5.36% between 2019 and 2024**. This growth, however, was not driven by improvements in operational efficiency, but rather by external factors.

---

### ⚙️ Efficiency vs. Technological Change
Productivity dynamics reveal a clear trade-off:

- **Technological Change (TC): +17.69%**  
  Significant advancements in the production frontier, likely reflecting improved infrastructure, medical technologies, and system-level improvements.

- **Efficiency Change (EC): -10.95%**  
  A decline in how efficiently hospitals utilize available resources, indicating persistent **managerial and operational inefficiencies**.

👉 In short: **technology is improving, but hospitals are not keeping up in terms of internal efficiency.**

---

### 🌍 Regional and Structural Inequality
Performance varies significantly across regions and hospital profiles:

- **Urban and high-income regions**:
  - Higher efficiency levels  
  - Consistent productivity gains  
  - Better access to infrastructure and resources  

- **Rural and smaller hospitals**:
  - Declining efficiency  
  - Greater difficulty in resource allocation and management  
  - More vulnerable to structural constraints  

---

### 🏥 Hospital Characteristics
Key institutional differences were observed:

- **Large hospitals and teaching hospitals**:
  - Higher efficiency  
  - Stronger productivity growth  
  - Likely benefit from scale and knowledge diffusion  

- **Specialized hospitals**:
  - Lower productivity growth compared to general hospitals  

---

### 🔍 Key Takeaways
- Productivity gains in the SUS are primarily driven by **technological progress rather than efficiency improvements**  
- There is **significant heterogeneity** across regions and hospital types  
- Structural and socioeconomic factors play a central role in determining performance  
- Improving **managerial efficiency** remains a critical challenge  

---

### 🎯 Policy Implications
The results suggest that effective healthcare policies should:

- Complement technological investments with **operational efficiency improvements**  
- Address **regional inequalities** in infrastructure and resources  
- Support smaller and rural hospitals with targeted interventions  
- Promote best practices from high-performing hospitals  

---

Overall, this study highlights that while the system is advancing technologically, **sustainable productivity gains will depend on improving how resources are managed and utilized**.

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
