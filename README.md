<p align="center">
  <img src="assests/Power BI Dashboard.jpeg" alt="Global Data Professional Survey Dashboard" width="800"/>
</p>

---

## 📌 Project Overview
This project provides a **comprehensive analysis of the data professional industry** based on real-world survey data. Using **Microsoft Power BI**, it demonstrates an **end-to-end workflow**: from data ingestion and transformation via Power Query, to the creation of an **interactive dashboard** visualizing key career metrics.

The dataset includes responses from **630+ data professionals** collected via social media platforms such as LinkedIn and Twitter.

---

## 📊 Key Features & Visualisations
The dashboard explores several critical dimensions of the data career landscape:

- **Demographics:** Tracks the total number of survey respondents and their **average age (~30 years old)**.
- **Salary Insights:** Average salary breakdown by job title; **data scientists** report the highest average earnings (~$93,000).
- **Technical Preferences:** Clustered column chart displaying the most popular programming languages, with **Python** as the leader.
- **Sentiment Analysis:** Interactive gauge charts measuring **happiness levels** regarding work-life balance and current salary.
- **Career Entry:** Visualisation depicting the perceived difficulty of entering the data field.
- **Geographic Distribution:** Tree map allowing users to filter salary and happiness metrics by **country** (e.g., United States, India, United Kingdom, Canada).

---

## 🔄 Data Transformation (Power Query & DAX)
Significant data cleaning was performed to make the raw survey data usable:

- **Standardising Titles:** Simplified job titles and programming languages by splitting columns using delimiters (e.g., parentheses, colons) to handle "Other" responses.
- **Salary Cleaning:** Transformed salary ranges (e.g., "106k-125k") into numeric values by removing non-digit characters and converting data types.
- **DAX Calculations:** Created a custom column to calculate the **average salary** from the transformed range values, providing a numeric metric for analysis.

---

## 🛠️ Tools Used
- **Microsoft Power BI Desktop:** Data modelling and dashboard creation.  
- **Power Query:** Advanced data cleaning and transformation.  
- **GitHub:** Project version control and documentation.

---

## 📝 How to Use
1. **Download the Dataset:** Obtain the raw CSV survey responses.  
2. **Open the .pbix File:** Load the project in **Power BI Desktop** to explore applied transformations.  
3. **Interact with the Dashboard:** Use the **Tree Map** to filter the report by country and observe how salary and sentiment vary across regions.  

---

## ✅ Conclusion
This project demonstrates the ability to transform **raw, uncleaned survey data** into a **professional, high-level business intelligence tool**. It showcases skills in:  
- Data cleaning and transformation  
- Standardising inconsistent text entries  
- Designing **user-centric interactive visualisations**  

---

## 📁 Project Files
```text
├── dataset/
│   └── global_data_professional_survey.csv
├── dashboard/
│   └── Global_Data_Professional_Survey.pbix
├── assets/
│   └── dashboard_screenshot.png
└── README.md
