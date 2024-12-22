# SCT_DS_04
# Traffic Accident Data Analysis  

## 📄 Project Overview  
This project focuses on analyzing traffic accident data to identify patterns related to time of day, weather conditions, and road features. The goal is to derive actionable insights that can inform road safety initiatives, reduce accident rates, and improve urban planning.  

## 🔑 Key Insights  
- *Time Analysis*: Accidents peak during rush hours (7-9 AM, 4-6 PM) and drop during late-night hours (12 AM - 5 AM).  
- *Weekly Trends*: Saturdays record the highest accidents, while Sundays see fewer incidents.  
- *Weather & Lighting*: Higher accidents occur during twilight and nighttime due to reduced visibility.  
- *Road Features*: Intersections and traffic signals are critical hotspots for accidents.  
- *Hotspot Visualization*: Heatmaps highlight high-risk areas near major intersections and highways.  

## 🛠 Technologies Used  
- *Programming Languages*: Python  
- *Libraries*: Pandas, Matplotlib, Seaborn, Folium  
- *Tools*: Jupyter Notebook  

## 📊 Dataset  
- The dataset contains *20,000 records and 20 columns*, including details like accident time, location, road features, weather conditions, and more.  
- *File Used*: SCT_DS_4.csv  

### Dataset Features  
- Start_Time, End_Time: Timestamp of the accident.  
- Start_Lat, Start_Lng: Geographic location of the accident.  
- Weather_Condition, Sunrise_Sunset: Environmental conditions during the accident.  
- Traffic_Signal, Stop: Road features impacting accident frequency.  

## ⚙ Code Execution Steps  
1. *Data Preparation*:  
   - Loaded the dataset.  
   - Converted time columns to datetime format.  
   - Extracted Hour and Day_of_Week for time-based analysis.  

2. *Time-of-Day Analysis*:  
   - Analyzed hourly and weekly distribution of accidents.  
   - Visualized accident trends using bar plots.  

3. *Weather and Road Conditions Analysis*:  
   - Examined accident rates during day/night and twilight periods.  
   - Analyzed the impact of road features like traffic signals, stop signs, and roundabouts.  

4. *Hotspot Visualization*:  
   - Created an interactive heatmap to identify high-risk accident areas.  

## 📈 Visualizations  
- *Hourly and Weekly Distribution*:  
   - Bar plots show accident trends by time of day and days of the week.  
- *Day/Night Analysis*:  
   - Accident counts categorized by lighting conditions.  
- *Road Features Impact*:  
   - Horizontal bar chart displaying accident frequency for road features.  
- *Heatmap*:  
   - An interactive map visualizing accident hotspots.  

## 📝 Conclusions  
1. *Peak Hours*: Rush hours are high-risk periods for accidents.  
2. *Twilight and Night Risks*: Poor visibility significantly increases accident rates.  
3. *Critical Road Features*: Traffic signals and intersections require targeted safety measures.  
4. *Hotspot Identification*: High-density accident areas need enhanced monitoring and interventions.  

## 🌟 Next Steps  
- *Data Enrichment*: Add weather data like precipitation and temperature for deeper insights.  
- *Predictive Modeling*: Build machine learning models to predict accident likelihood.  
- *Policy Recommendations*: Share insights with local authorities for actionable road safety strategies.  

## 📬 Contact Information  
*Author*: Prathviraj Chavan  
- Email: [mr.prathvirajchavan@gmail.com](mailto:mr.prathvirajchavan@gmail.com)  
- LinkedIn: [Prathviraj Chavan](https://www.linkedin.com/in/prathvirajchavan)  

---
