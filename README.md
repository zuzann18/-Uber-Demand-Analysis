
# Uber Demand Analysis

##  Project Overview
This project analyzes Uber ride demand in New York City, identifying key factors influencing ride pickups. The goal is to extract actionable insights that can help Uber optimize its operations based on weather conditions, holidays, and location-based trends.

## Objectives
- Identify variables influencing Uber ride pickups.
- Determine the most significant factors affecting demand.
- Provide recommendations for Uber management to capitalize on demand fluctuations.

## Dataset Description
The dataset consists of various features related to time, weather, and demand. The key columns include:

- **pickup_dt**: Date and time of the pick-up.
- **borough**: NYC borough.
- **pickups**: Number of pickups in a given period.
- **spd**: Wind speed (mph).
- **vsb**: Visibility (miles).
- **temp**: Temperature (°F).
- **dewp**: Dew point (°F).
- **slp**: Sea level pressure.
- **pcp01**: 1-hour liquid precipitation.
- **pcp06**: 6-hour liquid precipitation.
- **pcp24**: 24-hour liquid precipitation.
- **sd**: Snow depth (inches).
- **hday**: Holiday indicator (Y/N).

---

## 📓 Jupyter Notebook: Uber Demand Analysis

### 📝 Notebook Overview
The **Uber_Case_Study-1.ipynb** Jupyter Notebook provides a detailed **exploratory data analysis (EDA)** of Uber ride demand, highlighting the impact of various factors such as weather conditions and holidays.

### 📑 Notebook Sections
1️⃣ **Introduction**  
   - Overview of the dataset and project objectives.  

2️⃣ **Data Loading & Preprocessing**  
   - Importing libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`).  
   - Handling missing values and data inconsistencies.  

3️⃣ **Exploratory Data Analysis (EDA)**  
   - **Univariate Analysis:** Individual variable distributions.  
   - **Bivariate Analysis:** Relationships between factors affecting demand.  
   - **Time-Series Analysis:** Identifying trends over time.  

4️⃣ **Data Visualization**  
   - Line plots for ride demand trends.  
   - Heatmaps for variable correlations.  
   - Bar charts for demand across boroughs and holidays.  

---

## 📊 Key Findings

### 1️⃣ Influence of Weather
- **Temperature** has a significant positive correlation with ride demand. **Higher temperatures lead to more Uber rides.**
- **Precipitation (rain & snow)** negatively impacts pickups. **Bad weather reduces demand due to reduced mobility.**
- **Visibility** is also a factor—low visibility conditions reduce demand.
  ![image](https://github.com/user-attachments/assets/bf283d5a-dde8-4fe9-8843-9c4cdf9dd501)


### 2️⃣ Effect of Holidays & Time of Day
- **Holidays show a clear increase in Uber usage**, likely due to increased travel and reduced availability of public transport.
- **Peak demand is observed in the evening hours**, especially between 5 PM - 10 PM.
- **Weekends** see a significant **increase in demand** compared to weekdays.
![image](https://github.com/user-attachments/assets/618a2695-fb50-499d-9bd5-88528a1ba66c)

### 3️⃣ Borough-Wise Demand
- **Manhattan has the highest Uber pickup volume.** This is expected due to its high population density and business activity.
- **Brooklyn and Queens show moderate demand**, but it fluctuates more with weather conditions.
- **The Bronx and Staten Island have lower overall demand.**
![image](https://github.com/user-attachments/assets/e6d43dff-ba32-4d3a-b0b9-5bd2ed1b2018)


In the context of the data used in the Uber analysis, **borough** refers to the five main districts of New York City:

- **Manhattan**
- **Brooklyn**
- **Queens**
- **The Bronx**
- **Staten Island**

These boroughs are crucial for analyzing Uber ride demand, as each has distinct travel patterns, traffic conditions, and transportation needs.

For example:
- **Manhattan** has the highest number of rides due to high business and tourist activity.
- **Brooklyn and Queens** are significant for commuters traveling to work.
- **The Bronx and Staten Island** have lower ride volumes but may experience demand spikes during specific hours or weather conditions.

### Monthly Uber Pickups by Day Type

- **Working Days:**  
  - There's a general upward trend in total pickups from January to June.  
  - This indicates increasing demand throughout the period, possibly due to seasonal factors, increased Uber adoption, or other external influences.  

- **Non-Working Days:**  
  - The trend is similar to working days but with generally lower total pickups.  
  - This is expected as there are fewer non-working days in a month.  

## **Key Insights:**
**Uber demand is growing over time, suggesting a positive business trend.**  
 **While the overall trend is upward, slight variations exist between working and non-working days in certain months.**  
 


---

## 📌 Recommendations
Based on these findings, we propose the following business strategies:

### 🚀 Dynamic Pricing & Driver Allocation
- Implement **surge pricing based on real-time weather and holiday data** to optimize revenue.
- Increase **driver availability in high-demand areas during peak times** (evenings, weekends, and holidays).
- Reduce driver allocation in **low-visibility conditions or heavy rainfall**, as demand tends to drop.

### 📍 Location-Based Adjustments
- Focus **marketing efforts on outer boroughs (Brooklyn, Queens)** to improve demand in those regions.
- Increase **Manhattan coverage** during peak evening hours to maximize trip efficiency.

### 📈 Service Enhancements
- Offer **incentives to drivers** for working in high-demand periods.
- **Introduce promotions for rides booked in bad weather**, encouraging more usage even during low-mobility conditions.

---

## 📜 Conclusion
This analysis reveals that **weather, holidays, and borough location significantly impact Uber ride demand.** By leveraging these insights, Uber can implement strategic pricing, optimize driver availability, and enhance user experience. 

Applying **data-driven strategies** can lead to increased efficiency, better customer satisfaction, and higher revenue.

---

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook** for analysis and visualization

---

## 🚀 How to Use the Project

### 📥 Clone the Repository
```sh
git clone https://github.com/your-username/uber-demand-analysis.git
cd uber-demand-analysis
```

### 🛠 Install Dependencies
```sh
pip install pandas numpy matplotlib seaborn jupyter
```

### ▶️ Run the Notebook
```sh
jupyter notebook Uber_Case_Study-1.ipynb
```

---





