# 📊 Crime Data Analysis: Understanding Global Crime Patterns

## 🔍 Project Overview
This project analyzes global crime trends, exploring how socio-economic factors such as **GDP, population, education, and unemployment** influence crime rates. Using **data visualizations, correlation analysis, and key statistical insights**, this study identifies significant patterns in crime across 97 countries.

---

## 📂 Dataset Overview
- **Total Entries:** 343
- **Countries Represented:** 97
- **Continents Represented:** 6
- **Key Features:**
  - `Crime Index`, `Safety Index`, `GDP`, `Population`, `Education Enrollment`, `Unemployment Rate`, `Income per Capita`
- **Data Sources:** Kaggle, World Bank, and Other Public Datasets
- **Data Cleaning & Preprocessing:** No missing values after merging and filling gaps.

---

## 🔑 Key Findings
### 🌍 **Top Cities by Crime Index**
#### **Highest Crime Cities:**
1. **Pretoria, South Africa** (81.98)
2. **Celaya, Mexico** (81.80)
3. **San Pedro Sula, Honduras** (80.87)
4. **Port Moresby, Papua New Guinea** (80.71)
5. **Durban, South Africa** (80.60)

#### **Lowest Crime Cities:**
1. **Abu Dhabi, UAE** (11.67)
2. **Doha, Qatar** (13.96)
3. **San Sebastian, Spain** (14.86)
4. **Quebec City, Canada** (15.14)
5. **Zurich, Switzerland** (17.26)

### 📊 **Statistical Highlights**
- **Highest GDP (2022):** China ($17.88T)
- **Lowest GDP (2022):** Maldives ($6.18B)
- **Largest Population:** China (1.42B)
- **Smallest Population:** Iceland (372,899)
- **No direct correlation between GDP and crime levels.**

### 🔗 **Correlation Analysis**
| Factor                     | Correlation with Crime Index |
|----------------------------|-----------------------------|
| **Income per Capita**      | **-0.37 (Negative)**        |
| **Unemployment Rate**      | **0.35 (Positive)**         |
| **Education Enrollment**   | **-0.22 (Negative)**        |
| **GDP**                    | **-0.06 (Weak Negative)**   |
| **Population**             | **0.01 (No Impact)**        |

🔹 **Higher Income = Lower Crime** 🟢

🔹 **Higher Unemployment = Higher Crime** 🔴

🔹 **Higher Education Enrollment = Generally Lower Crime** 🟢

🔹 **GDP has little impact on crime rates** 🤔

---

## 📊 **Data Visualizations**

### 📌 **Distribution of Crime Index**
📊 **Observation:** The crime index follows a **wide distribution**, with some cities experiencing extremely high crime rates while others maintain low crime levels.

![image](https://github.com/user-attachments/assets/4845de0d-435d-465f-a5e3-ab2903c457d2)


### 📌 **Correlation Heatmap**
🔥 **Insight:** Crime Index shows a **moderate to strong correlation** with various socio-economic factors, with **notable relationships between unemployment, income, and education levels.**

![image](https://github.com/user-attachments/assets/2f4c17fe-8d20-4e7a-a2de-adf4e1d1d4d6)


### 📌 **Top 10 Highest and Lowest Crime Indices**
🏙️ **Comparison:** We identified the **top 10 cities with the highest crime index** and the **10 cities with the lowest crime index** for a direct contrast.

![image](https://github.com/user-attachments/assets/1bdba862-5442-4fc1-b09c-9083097860a3)

### 📌 **Correlation Matrix Heatmap**
📉 **Trend:** A detailed correlation matrix helps visualize **relationships between crime rates and socio-economic variables** such as GDP, population density, and growth rate.

![image](https://github.com/user-attachments/assets/03a872f2-5a36-4fb6-81f0-4bdd2581d725)

### 📌 **Crime Index vs. Income per Capita**
📉 **Observation:** Generally, **higher income per capita is linked to lower crime rates**, but significant **outliers** exist in certain regions.

![image](https://github.com/user-attachments/assets/dc34e1f7-20bd-4f3f-a656-67dbda90cf09)


### 📌 **Crime Index vs. School Enrollment Rates**
📉 **Finding:** Cities with **higher school enrollment rates** tend to have **lower crime rates**, suggesting education plays a key role in crime prevention.

![image](https://github.com/user-attachments/assets/f7c6f3d4-6b5c-4cfe-94bf-15403ea96eed)


### 🗺️ **Folium Interactive Crime Map**
🌍 **Interactive Visualization:** Using **Folium**, we mapped global crime index values with **color-coded markers** to indicate different crime severity levels.

---


## 🚀 Next Steps
✅ Extend analysis with **law enforcement data, social policies, and governance stability.**

✅ Investigate **real-time crime data for predictive modeling.**

✅ Perform **time-series forecasting on crime trends.**

---

## 🛠️ Tech Stack
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Folium
- **Jupyter Notebook / Google Colab** for EDA & Visualization
- **GitHub** for version control

---

## 📁 Project Files
📜 `crime_data_analysis.ipynb` → Full analysis notebook

📊 `crime_data_cleaned.csv` → Preprocessed dataset

🗺️ `crime_map.html` → Interactive crime visualization

---

## 🎯 How to Use
1️⃣ **Clone the repository:**
```bash
git clone https://github.com/yourusername/crime-data-analysis.git
```

2️⃣ **Open Jupyter Notebook / Google Colab**

3️⃣ **Run the analysis!**

---

## 🔗 Links
📌 **Project Notebook:** [Google Colab](https://colab.research.google.com/)

📌 **Dataset Source:** [Kaggle Crime Data](https://www.kaggle.com/)

📌 **Portfolio Website:** [Portfolio](https://al-raoushbasel.github.io/portfolio/)

---

## 📝 Author
👤 **Basel Al-Raoush**  
📧 **Email:** basel.alraoush15@gmail.com  
🌍 **LinkedIn:** [linkedin.com/in/basel-alraoush](https://linkedin.com/in/basel-alraoush)  

🔔 If you found this project useful, give it a ⭐ on GitHub!
