# 📊 Drug Classification Dashboard – Power BI Project (Review 2)

## ✅ Submitted by:
**Shubham Mishra (Admin),**  
Annu Kumar,  
Saksham Bhardwaj,  
Suraj Tiwari  

B.Tech CSE, Semester IV  
Galgotias University  

---

## 🎯 Project Objective

The aim of this dashboard is to visualize and interpret patterns in drug prescriptions using patient data such as:

- Age
- Sex
- Blood Pressure (BP)
- Cholesterol level
- Sodium to Potassium ratio (Na_to_K)

Unlike Review 1 (ML-based classification), this phase focuses on **interactive visual storytelling** using **Power BI**.

---

## 📁 Dataset

- File: `drug200.csv`
- Records: 200
- Features: Age, Sex, BP, Cholesterol, Na_to_K
- Target: Drug (drugA, drugB, drugC, drugX, drugY)

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop**
- CSV Data Import
- Data Transformation using Power Query
- DAX for calculated columns (if used)
- Slicers and Tooltips for interactivity

---

## 📊 Dashboard Components

| Visual | Description |
|--------|-------------|
| Bar Chart | Drug prescription count distribution |
| Pie Chart | Gender distribution |
| Box Plot | Na_to_K distribution across drugs |
| Scatter Plot | Age vs Na_to_K, colored by drug class |
| Text Box | Summary of key insights |

---

## 🎛️ Interactive Features

### ✅ Slicers (Filters)
- Sex (Male / Female)
- Blood Pressure (LOW / NORMAL / HIGH)
- Cholesterol (NORMAL / HIGH)

> These allow filtering all visuals dynamically.

### 💬 Tooltips
- Enabled on scatter and bar charts
- Provide hover info like Age, BP, Cholesterol, Na_to_K, and Drug

---

## 🔍 Key Insights Displayed

- `Na_to_K` has the highest impact on drug classification
- Most patients with high Na_to_K are prescribed **DrugY**
- Drug prescription pattern varies slightly by gender and BP
- Scatter plot reveals clusters based on Na_to_K and age

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Review2_Drug_Visualization.pbix` | Main Power BI file |
| `drug200.csv` | Dataset file |
| `README.md` | This project summary |
| `presentation.pptx` | Final review presentation |

---

## 🧭 How to Use the Dashboard

1. Open `Review2_Drug_Visualization.pbix` in Power BI Desktop.
2. Use the slicers to filter data by `Sex`, `BP`, or `Cholesterol`.
3. Hover over charts to view detailed insights.
4. If multiple pages are added, navigate using tabs or page navigation buttons.

---

## 👥 Team Members

- Shubham Mishra (Project Lead)
- Annu Kumar
- Saksham Kumar
- Suraj Tiwari

---

## 🏁 Acknowledgement

This is Review 2 of the **Drug Classification Project**, focused on interactive dashboards, submitted as part of the **Data Analytics Evaluation** at Galgotias University under GUVI's review structure.

Thanks for reviewing!  
— **Shubham Mishra**

