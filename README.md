🚲 **Smart-City-Bike-Analysis
**

The dataset represents the operational data of a Smart City Bike Sharing system used across several
European cities. It contains information about bike stations, their geographic locations, parking
capacity, bike availability, and supported payment methods. This data helps analyze how
efficiently the bike-sharing infrastructure supports urban transportation.This data helps analyze
bike station utilization, infrastructure capacity, and accessibility of bike-sharing services across
cities.

---
🛠 **Tools & Technologies**
Power BI – Dashboard creation & visualization
Data Modeling – Relationships & measures
DAX – KPI calculations
Map Visualization – Geo analysis

---
📊**Data cleaning :**
• Standardized text formatting to maintain consistency across station names, cities, and
categorical fields.
• Removed null, duplicate, and incomplete records to improve data quality and
reliability.

---

🎯**Dax Measure:**
Dax Measures
Average_Bike_Availability = AVERAGE(BikeTable[Available Bikes])
No of stations = COUNTROWS(BikeTable)

Dax Custom Column
PaymentType = IF(BikeTable[banking] = True,"Online Payment Available","Cash Only”
Bonus Availability = IF(BikeTable[bonus]=True,"Yes Discount Available","No Discount")

---

🎯**Key Insight:**

• The system prioritizes continuous usage and redistribution instead of keeping large
bike inventories at each station.
• Maintaining an average of 7 available bikes indicates operational efficiency but also
signals potential demand pressure during peak hours.

---

 💹**Bike Analysis_Dashboard:**
 
 <img width="673" height="376" alt="Bike station Analysis" src="https://github.com/user-attachments/assets/8423cbf2-a87b-4670-8b5d-d977e8c2686b" />


---

 📍**conclusion:**
 Conclusion
The bike-sharing system demonstrates a well-developed smart mobility infrastructure across
multiple European cities. With over 3,000 stations, strong digital payment adoption, and
incentive-based redistribution mechanisms, the system is designed to support high-frequency
urban commuting.However, the concentration of infrastructure in a few key cities suggests opportunities to expand
capacity and optimize bike distribution, ensuring consistent availability as demand grows.

---

