# 🌍💧 Access to Drinking Water Part 1 – Data Analysis Project

---

## 📢 Acknowledgement
This project is part of the **ALX Africa / ExploreAI Data Science Program**.  
🙏 Thanks to ALX and ExploreAI for providing the datasets and project guidance!  
Dataset source: **WHO/UNICEF Joint Monitoring Programme (JMP) – Estimates on the Use of Water (2020)**

---

## 🌟 Badges
![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Data Analysis](https://img.shields.io/badge/Skill-DataAnalysis-yellow)
![ALX Africa](https://img.shields.io/badge/Program-ALXAfrica-blue)

---

## 📖 Overview
> Analyze **global access to safe and affordable drinking water** using the WHO/UNICEF JMP 2020 dataset.  

This project includes:
- Data import and cleaning  
- Feature engineering  
- Exploratory analysis  
- Statistical summaries  
- Data visualization  
- Insights on access to water by area, population size, and income group  

---

## 🚀 Repo Navigation
- **README.md** → overview & documentation  
- **`/analysis/Project_1.xlsx`** → cleaned dataset, calculations, and analyses  
- **`/data/Estimates-on-the-use-of-water-2020.csv`** → raw dataset  

---

## 📂 Repository Structure
📦 access-to-drinking-water  
┣ 📂 data  
┃ ┗ 📜 Estimates-on-the-use-of-water-2020.csv  
┣ 📂 analysis  
┃ ┗ 📊 Project_1.xlsx  
┗ 📜 README.md  

---

## 🔎 Data Description
**Original Features (16 columns)**:
- `name` → Country/area  
- `year` → Observation year  
- `pop_n` → National population (in thousands)  
- `pop_u` → Urban population share (%)  
- Water access indicators:  
  - `wat_bas_*` → At least basic service (%)  
  - `wat_lim_*` → Limited service (%)  
  - `wat_unimp_*` → Unimproved service (%)  
  - `wat_sur_*` → Surface water only (%)  

**Engineered Features**:
- `value_cnt` → Row completeness check  
- `pop_u_val` → Urban population count  
- `pop_r` → Rural population share (%)  
- `pop_n (m)` → Population in millions (rounded)  
- Rounded versions of access indicators (`wat_bas_n (rounded)`, etc.)  

---

## 🔹 Analysis Highlights

<details>
<summary>Click to expand key findings</summary>

1. **Population Comparison**  
   - Total dataset population vs UN World Cities Report (2020): ~7.82B  
   - Urban share ~55%, closely matching global estimates  

2. **Water Access by Area**  
   - Urban areas: higher access to basic water services  
   - Rural areas: higher shares of unimproved/surface water  

3. **Statistical Distributions**  
   - Skewed distributions; outliers affect averages  
   - Boxplots reveal inequality between countries  

4. **Population Size & Access**  
   - 100% stacked bars show national, rural, urban impact on service levels  

5. **Income Group Analysis**  
   - Higher GNI → higher basic access  
   - Low-income countries → largest share of limited/unimproved access  
   - High-income countries → near universal basic access  

</details>

---

## 🌍 Key Insights
- **Global alignment:** Population and urban share match world estimates  
- **Inequality:** Rural and low-income regions face the biggest challenges  
- **Urbanization link:** Higher urbanization → better water access  
- **Income matters:** Economic development strongly predicts access  

---

## 🛠️ Tools Used
- **Microsoft Excel** → data cleaning, feature engineering, analysis, visualization  
- **WHO/UNICEF JMP dataset (2020)**  

---

## 📚 References
- WHO/UNICEF JMP – *Estimates on the Use of Water (2020)*  
- UN Sustainable Development Goal 6 – Clean Water and Sanitation  

---

## 👤 Author
**Sifiso Sibiya** – Data Scientist & Analyst  
Focused on solving real-world problems in South Africa and globally 🌍
