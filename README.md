# Wind Turbines in the U.S.  
**Data Analysis & Visualization Capstone Project**

## Problem Statement

This project explores wind turbine data across the U.S. to uncover trends in turbine distribution, capacity, and technological growth. 
The main goal is to understand how wind energy infrastructure has evolved regionally and nationally, using clear analysis and visual storytelling.

---

## Project Workflow

### 1. Data Collection

- **Source**: [U.S. Wind Turbine Database (USWTDB)](https://eerscmap.usgs.gov/uswtdb/)
- Dataset includes turbine location, installation year, capacity, manufacturer, and other features.

### 2. Data Cleaning

- The dataset was clean — no missing or duplicate values were found.
- Renamed several columns to improve clarity and readability (e.g.,'Site.State': 'State','Site.County': 'County',).
- Ensured date formats were consistent for temporal analysis.
- Applied filtering later during visualization to focus on specific states, years, and capacity ranges.

### 3. Exploratory Data Analysis (EDA)

- Grouped turbines by state and by year to identify growth trends.
- Analyzed average turbine height and capacity over time.
- Compared turbine counts and manufacturers across regions.
- Investigated land ownership types and project sizes.

### 4. Visualizations

| Visualization | Description |
|---------------|-------------|
|![image](https://github.com/user-attachments/assets/ec8eec0a-22b7-4ed3-a03a-e686f64063da) | Annual growth of turbine installations |
| ![image](https://github.com/user-attachments/assets/58f9fc8a-8b5f-40f0-ac31-5e4f2e9e5ba7) | States with the most turbines |
| ![image](https://github.com/user-attachments/assets/854a704f-e813-406c-8044-15db5b6c4593) | Average rated capacity over time |
|![image](https://github.com/user-attachments/assets/6c6c308a-8c2a-47ca-b167-a15523b74cba) | Changes in hub height by year |
|![image](https://github.com/user-attachments/assets/3f71f76a-3b58-45d4-958f-fa658273c043) | Wind Turbine Locations |
| ![image](https://github.com/user-attachments/assets/7ef07d3a-9581-4ee3-897a-7638570eb746) [**Interactive Map of Wind Turbine Capacity by State (% of Total)**](https://musical-sprinkles-61bd91.netlify.app/) | Interactive Bokeh map displaying Wind Turbine Capacity by State (% of Total) |


All plots were created using `Matplotlib`, `Seaborn`, and `Bokeh` for interactive visuals.

---

## Insights

- **Texas** leads with the highest number of installed turbines.
- Newer turbines are **taller** and have **greater capacity**, showing technological advancements.
- A few manufacturers dominate the U.S. wind turbine market.
- Western states have more turbines on federally owned land.

---

## Tools Used

- **Python Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Bokeh  
- **Notebook Platform**: Jupyter Notebook  
- **Visualization**: Static and interactive charts

> I learned how to use **Bokeh** for creating interactive visualizations during my **Data Talent Program at M2M Tech** and applied this knowledge in building this hands-on project as part of my **internship experience**.

---

## Recommendations

- Transform this into a **dashboard** using **Tableau** or **Power BI**.
- Combine with **weather or energy output data** for predictive modeling.
- Expand analysis to include **environmental or policy impact** studies.

---

## Project 

- [`Wind_Turbines_in_the_U_S.ipynb`](Wind_Turbines_in_the_U_S.ipynb): Full analysis notebook  

---

## Sources

- [US GeoJSON source](https://eric.clst.org/tech/usgeojson/)
- [CORGIS - Wind Turbines Dataset](https://corgis-edu.github.io/corgis/csv/wind_turbines/)
- [Bokeh docs on mapping geo data](https://docs.bokeh.org/en/latest/docs/user_guide/geo.html)
- [Published Interactive Visualization on Netlify](https://your-netlify-site.netlify.app)  

---

Created by [Mariia-Olena Zhupnyk](https://github.com/helenzhupnyk)  
Capstone project for portfolio – April 2025  
Internship project for M2M Tech’s Data Talent Program
