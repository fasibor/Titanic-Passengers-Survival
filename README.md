# Titanic Survival Dashboard

This project analyzes survival patterns aboard the Titanic using Power BI. It explores how class, age, gender, fare, and cabin location influenced survival outcomes. Inspired by the 1997 *Titanic* movie, this analysis transforms historical data into actionable insights with real-world implications for emergency preparedness.

---
![Screenshot_1](https://github.com/user-attachments/assets/7e8467e4-6b70-412d-a475-f54f0c2eae40)



## Dashboard Overview

This Power BI dashboard presents visualizations and breakdowns of:
- Passenger class distribution and survival
- Age group trends (children, teens, adults, elderly)
- Gender-based survival rates
- Cabin occupancy and its impact on evacuation
- Fare amounts vs. survival likelihood

> **Tool Used:** Power BI  
> **Techniques:** DAX, custom columns/measures, data transformation

---

## Why This Project Matters

This project highlights structural and demographic factors that influenced survival aboard the Titanic. The findings can inform future transportation safety practices by addressing systemic inequalities and evacuation inefficiencies.

### Benefits:
- **Emergency Strategy Optimization:** Identify gaps in evacuation protocol.
- **Data Transparency:** Reevaluate assumptions about gender and class roles.
- **Demographic Risk Profiling:** Protect vulnerable groups (elderly, children).
- **Cabin Allocation Insights:** Minimize risks from overcrowding and poor layout.

---

## Getting Started

To explore or replicate this analysis:

1. **Download the Dataset**  
   Get the [Titanic dataset from Kaggle](https://www.kaggle.com/datasets/khushikyad001/titanic-passenger-survival-dataset).

2. **Open in Power BI**  
   Load and clean the dataset. Apply transformations, DAX formulas, and visual filters.

3. **Analyze Key Metrics**:
   - **Survival by Class**: 1st, 2nd, 3rd
   - **Age Group Trends**: children, teens, adults, elderly
   - **Cabin Crowding**: G6, E46, C85, and unspecified
   - **Fare Analysis**: Did higher ticket price mean safer passage?

4. **Customize Visuals**  
   Add slicers, filters, and KPIs based on survival outcomes and demographics.

---

## Key Findings

### Lower Class  
In the lower class, survival rates were nearly equal between females (50.13%) and males (49.87%), with teens exhibiting the highest survival at 62.5%, followed by children (~55%), elderly (~51%), and adults (~49%). A significant number of passengers were assigned to unspecified cabins, which showed slightly higher survival rates but likely reflect disorganized cabin allocation. Overcrowding was common in cabins G6, C85, and E46, hindering efficient evacuation. Additionally, fare paid did not strongly influence survival outcomes, indicating underlying systemic issues in cabin assignment and emergency preparedness.

### Middle Class  
The middle class had a nearly equal gender distribution, with males showing a higher survival rate (52.19%) than females (47.81%). Among age groups, children had the best survival at 51%, followed by adults (49%), elderly (47%), and teens with the lowest at 38%. Overcrowding remained an issue in cabins E46, G6, C85, and unspecified cabins, with survival rates varying by cabin—G6 had the highest, while C85 had the lowest. Although the total fare paid amounted to $30,000, economic factors did not directly translate into a survival advantage.

### Upper Class  
In the upper class, survival rates were similar for females (50.82%) and males (49.18%), with teens having the highest survival at 53%, followed by children (50%), adults (49%), and the elderly (47%). Cabin occupancy was highest in unspecified cabins and G6, while C85 had the lowest survival rate. Despite higher total fares reflecting premium status, survival outcomes were uneven, indicating gaps in emergency procedures even among upper-class passengers. Notably, the numbers of male and female survivors and fatalities were nearly equal, suggesting gender-neutral survival outcomes in this class.

---

## Pattern Observations

1. Teens consistently show the highest survival rates across all classes, possibly due to greater mobility and awareness.  
2. Unspecified cabins are common across all classes, suggesting poor cabin assignment protocols that hinder safety and evacuation.  
3. Overcrowded cabins (G6, C85, E46) appear across classes, limiting access to exits and contributing to lower survival rates in those areas.  
4. Survival rates for elderly passengers are consistently lowest, indicating a vulnerable group needing specialized attention.  
5. Fare paid does not guarantee higher survival, pointing to structural flaws in how cabin placement and evacuation are managed regardless of ticket price.

---

## Recommendations

### 1. Implement Smart Cabin Allocation Systems  
To enhance safety and evacuation efficiency, I recommend eliminating unspecified cabins and ensuring passengers are evenly distributed to avoid overcrowding. We should implement a dynamic cabin assignment system that takes into account factors like age, mobility, group size, and proximity to emergency exits. Additionally, I suggest adjusting fare structures to incentivize and provide fair access to safer cabins for passengers across all economic groups.

### 2. Create Specialized Safety Zones & Programs  
I recommend creating child-focused safety areas staffed with trained attendants close to lifeboats, establishing elderly care zones with improved accessibility and dedicated mobility support, and developing youth cabins supervised by crew that include peer-leader safety programs to help teens respond effectively during emergencies.

### 3. Leverage Technology for Safety  
I suggest deploying wearable safety devices like digital ID bands or smart wristbands that offer real-time evacuation guidance and tracking, alongside implementing crowd monitoring systems in cabins to detect overcrowding and improve evacuation efficiency.

### 4. Tailor Safety Training & Drills  
I recommend conducting age-appropriate safety simulations—interactive drills for teens, family-based exercises for children, and personalized briefings for the elderly—while also implementing gender-sensitive communication strategies to ensure clear and effective guidance for all passengers.

### 5. Enhance Upper-Class Safety Protocols  
I suggest introducing exclusive, clearly marked emergency exits and dedicated evacuation staff for upper-class cabins, while regularly monitoring survival trends by cabin and passenger demographics to proactively refine and improve safety measures.




---

## Who Maintains the Project?

This dashboard was created by **Felix Asibor**.  
Contributions are welcome!

### How to Contribute:
- Fork the repo
- Create a new branch
- Submit a pull request with improvements
- Ensure your updates align with survival analysis or data storytelling best practices

---

## Contact

For feedback or collaboration:
- [LinkedIn](https://www.linkedin.com/in/fesibor)
- GitHub Issues tab

---

## Tags

`#PowerBI` `#DataAnalytics` `#TitanicData` `#SurvivalAnalysis` `#DataVisualization` `#DAX` `#DashboardDesign` `#BI` `#MaritimeSafety` `#HistoricalData`

---
