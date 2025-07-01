<p align="center">
  <img src="images/ncd_types_chart.png" alt="Non-Communicable Diseases Diagram" width="700"/>
</p>

# 🩺 GCC vs Global NCD Analysis — Capstone Project

**Author**: Mohamed Jamal  
**Bootcamp**: General Assembly Data Analytics  
**Date**: July 2025  

This project compares Non-Communicable Disease (NCD) mortality trends in GCC countries with global and MENA regions, aiming to support data-informed health policy and long-term planning.

---

## 📁 Project Structure

\`\`\`
GCC_vs_Global_NCD_Analysis/
│
├── data/
│   └── ncd_mortality_gcc_reshaped.csv         # Cleaned dataset used for analysis
│
├── graphs/
│   └── Capstone graphs.pbix                   # Power BI dashboard for visualization
│
├── notebooks/
│   └── Exploratory Data Analysis (EDA).ipynb  # Jupyter Notebook with full analysis
│
├── presentation/
│   └── Mohamed Jamal Capstone.pptx            # Final presentation (Lightning Talk #2)
│
├── report/
│   └── Mohamed Jamal Technical Report.docx    # Full technical writeup of the project
│
└── README.md                                  # Project overview and documentation
\`\`\`

---

## 🎯 Project Objectives

- Identify and compare leading causes of NCD-related death in GCC vs global and MENA regions
- Visualize and quantify mortality per 100,000 using ICD-10 categories
- Highlight disparities and data gaps in reported causes of death
- Provide actionable recommendations for GCC health systems and Vision 2030 goals

---

## 👥 Target Audience

- GCC Public Health Authorities
- Regional Policy Makers
- WHO and UN-affiliated researchers
- Healthcare system strategists
- Data analysts working in global health

---

## 🛠 Tools & Technologies

- **Python** (Jupyter Notebook) — for data analysis
- **Excel** — for reshaping and inspecting raw data
- **Power BI** — for building visuals and dashboards
- **PowerPoint** — for presentation delivery

---

## 📊 Datasets Used

1. **WHO Mortality Database (ICD-10)**  
   - [Link](https://www.who.int/data/data-collection-tools/who-mortality-database)  
   - Cause-of-death data by ICD-10 category across countries and years

2. **WHO NCD Country Profiles (2020)**  
   - [Bahrain](https://cdn.who.int/media/docs/default-source/country-profiles/ncds/bhr_en.pdf)  
   - [Saudi Arabia](https://cdn.who.int/media/docs/default-source/country-profiles/ncds/sau_en.pdf)  
   - [UAE](https://cdn.who.int/media/docs/default-source/country-profiles/ncds/are_en.pdf)

3. **World Bank Population Estimates**  
   - [Link](https://data.worldbank.org/indicator/SP.POP.TOTL)

4. **UN ESCWA Regional Population Data**  
   - [Link](https://data.unescwa.org)

---

## 🧪 Key Insights

- **Cardiovascular disease** is the top NCD killer in all analyzed GCC countries.
- **Kuwait** and **Saudi Arabia** have the **highest NCD mortality per capita**.
- Bahrain's data was not available in ICD-10 format and was **approximated using WHO profiles**.
- GCC NCD mortality is **higher than global averages**, despite better infrastructure.
- There is a **data attribution gap** — ICD-10 shows 10–25% NCD death attribution, while WHO models estimate 80%.

---

## 📈 Visualizations

Visuals are available in:
- `graphs/Capstone graphs.pbix` — interactive Power BI dashboard
- `presentation/Mohamed Jamal Capstone.pptx` — final slides
- `notebooks/Exploratory Data Analysis.ipynb` — static visual outputs

Includes:
- Treemaps by top NCD causes
- Mortality rates per 100,000 (bar and line charts)
- Bahrain proxy pie chart from WHO profiles

---

## 💡 Recommendations

- Improve ICD-10 reporting and cause-of-death documentation (esp. Bahrain)
- Invest in preventive care for cardiovascular and metabolic diseases
- Launch age- and gender-targeted awareness campaigns
- Align strategies with WHO targets and **GCC Vision 2030 health priorities**

---

## ⚠️ Limitations

- Bahrain not included in ICD-10 export — used 2020 WHO NCD Profile instead
- Potential inconsistencies in national death registration or coding systems
- Global comparison may not account for all social and environmental risk factors

---

## 📚 References

1. WHO Mortality Database – ICD-10: https://www.who.int/data/data-collection-tools/who-mortality-database  
2. WHO NCD Country Profiles (2020): https://www.who.int/publications/i/item/ncd-country-profiles-2020  
3. World Bank Population Data: https://data.worldbank.org/indicator/SP.POP.TOTL  
4. UN ESCWA Regional Data: https://data.unescwa.org  
5. ICD-10 Code Reference: https://icd.who.int/browse10/2019/en#/  
6. Frontiers in Public Health:  
   - *Image Source*: [NCD Types Diagram](https://www.frontiersin.org/articles/10.3389/fpubh.2020.574111/full)  
   - *License*: CC BY 4.0

---

## 📫 Contact

For questions, suggestions, or collaborations:  
**GitHub**: [github.com/your-username]  
**Email**: [your-email@example.com] *(optional)*
