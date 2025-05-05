# Space Missions Dashboard Documentation  

## **Overview**  
A Power BI dashboard analyzing historical space mission data, including success rates, costs, and trends by company, country, and rocket type.  


## **Data Sources**  
- **Original Data:** Contains mission records with:  
  - **Company** (NASA, SpaceX, CASC, etc.)  
  - **Location** (Launch site)  
  - **Date & Time**  
  - **Rocket Type** (Falcon 9, Saturn V, etc.)  
  - **Missions and Mission Status** (Success, Failure, Partial Failure, Prelaunch)  
  - **Price** (Mission cost in millions)  
  - **Rocket Status** (Active/Retired)  

### **Data Transformations**  
1. **Extracted Country** from Location (e.g., "Florida, USA" → "USA").  
2. **Created Date Hierarchy** (Year → Month → Day) for time-based filtering.  
3. **Cleaned Mission Status** for consistent categorization.  

<img width="871" alt="image" src="https://github.com/user-attachments/assets/16da2886-0f13-48b1-b4e4-8301b03138c7" />

---

## **Key Metrics (Measures)**  
| Measure | Description |  
|---------|------------|  
| **Total Missions** | Count of all missions (1K in sample). |  
| **Total Price** | Sum of all mission costs ($162.30B in sample). |  
| **Successful Missions** | Missions with "Success" status (1K). |  
| **Failed Missions** | Missions with "Failure" status (48). |  
| **Partial Failed Missions** | Missions with "Partial Failure" status (19). |  
| **Prelaunch Missions** | Missions in "Prelaunch" status (1). |  

---
![Screenshot 2025-05-05 183650](https://github.com/user-attachments/assets/5233465f-0ce8-42be-a62e-c77b05e05863)

## **Dashboard Visualizations**  
1. **Summary Cards** – High-level metrics (Total Missions, Price, Success Rate).  
2. **Missions Over Time** – Trends by year/month.  
3. **Missions by Location & Price** – Geographic cost distribution.  
4. **Success by Company** – Top performers (SpaceX, NASA, CASC).  
5. **Missions by Rocket** – Most-used rockets (Falcon 9, Long March, etc.).  
6. **Rocket Status** – Active vs. Retired rockets.  
7. **Missions by Country** – USA, China, Russia, etc.  

---

## **Interactivity & Filters**  
✔ **Date Drill-Down** – Analyze by Year → Month → Day.  
✔ **Mission Status Toggles** – Filter by Success/Failure/Prelaunch.  
✔ **Collapsible Sections** – Focus on specific data segments.  

---

## **Usage Notes**  
- Compare **cost vs. success rates** across companies/countries.  
- Track **mission trends** over decades (e.g., Apollo era vs. modern SpaceX).  
- Identify **most reliable rockets** (Falcon 9 vs. Long March).  

**Example Insight:**  
*"NASA’s Saturn V had a high success rate (12/14 missions), while Soviet Energiya missions cost $5B each."*  

---  

**Last Updated:** May 2025  
**Data Source:** Historical space mission records (1967–2023).
