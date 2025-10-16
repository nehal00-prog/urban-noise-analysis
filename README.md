# 🏙️ Urban Noise Pattern Analysis via Mobile Recordings

## 📘 Project Overview
This project focuses on analyzing urban noise patterns in different Indian cities using real-world recordings from the **Noise Monitoring Data in India** Kaggle dataset.
The main goal is to understand how noise levels vary by **time, location, and type of area** — and to visualize these insights for better awareness and urban planning.

---

## 🎯 Objectives
- To clean and preprocess raw noise data collected from various urban locations.
- To detect noise trends and anomalies using Python data analysis techniques.
- To visualize noise levels through meaningful charts and graphs.
- To identify high-noise zones and suggest possible insights.

---

## 📂 Dataset
**Source:** [Noise Monitoring Data in India - Kaggle](https://www.kaggle.com/datasets)

**Key Features:**
- `Location` – Area of recording  
- `Date` & `Time` – Timestamp of data collection  
- `Leq_dB` – Equivalent continuous sound level in decibels  
- `Noise_Type` – Type/category of noise source (traffic, industrial, etc.)

---

## 🧠 Technologies Used
| Category | Tools / Libraries |
|-----------|------------------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Notebook | Jupyter Notebook (.ipynb) |
| Version Control | Git & GitHub |

---

## 🔍 Data Analysis Steps
1. **Data Collection** – Importing dataset from Kaggle.  
2. **Data Cleaning** – Handling null values, duplicates, and incorrect entries.  
3. **Exploratory Data Analysis (EDA)** –
   - Mean/median noise level calculation  
   - Hourly and daily variation study  
   - Area-wise comparison  
4. **Visualization** – Plotting graphs to reveal noise trends.  
5. **Insights** – Highlighting most and least noisy areas with recommendations.

---

## 📊 Sample Visualizations
- 📈 Average Noise Level by Time of Day  
- 🌆 City-wise Noise Distribution  
- 🔉 Comparison of Weekday vs Weekend Noise  

---

## 💡 Insights
- Commercial and traffic-heavy areas show consistent high noise levels.  
- Noise levels peak during morning and evening rush hours.  
- Residential areas are quieter but still exceed WHO’s recommended limits at times.

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/nehal00-prog/urban-noise-analysis.git
   cd urban-noise-analysis
   ```
2. Install required libraries  
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook  
   ```bash
   jupyter notebook A_P.ipynb
   ```

---

## 📜 License
This project is licensed under the **MIT License** — you’re free to use and modify it with proper credit.

---

## 🙌 Acknowledgments
- Dataset provided by **Kaggle**
- Created by **Nehal Wahab**
- Guided by project mentors and open-source community
