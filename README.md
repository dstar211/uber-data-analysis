# 🚕 Case Study: Optimizing NYC Mobility through Uber Revenue Analytics

## 📖 The Story
In the fast-paced world of urban transportation, understanding the "pulse" of the city is key to profitability. This project analyzes **103.7K bookings** in New York City to uncover how time, location, and vehicle type influence a total revenue of **$1.55M**.

---

## 🔍 The Challenge
Uber operations managers often face "Information Overload." With over 100,000 trips, it was difficult to see:
* **When** to surge-price or offer driver incentives.
* **Where** the highest demand for premium vs. economy vehicles exists.
* **How** payment methods affect the bottom line.

---

## 🛠️ The Solution (Analytical Framework)
I built a three-page interactive dashboard system (Overview, Time, and Details) to transform raw trip logs into a strategic command center.

### 1. Executive Revenue Overview
![Uber Overview](./uber_1.png)
* **KPIs:** Tracked a healthy **$15.0 average booking amount** across **349K miles** of travel.
* **Payment Story:** Discovered that **Uber Pay (55%)** is the dominant force, suggesting a highly loyal digital user base compared to cash users (22%).

### 2. Temporal Intelligence (The "Time" Factor)
![Uber Time Analysis](./uber_2.png)
* **The Insight:** While daytime bookings are steady, **Night trips drive 47% ($940K)** of total revenue. 
* **The "Saturday Peak":** Saturday leads the week with **18.7K bookings**, peaking between 6:00 PM and Midnight.

### 3. Granular Logistics (The "Details" View)
![Uber Details](./uber_3.png)
* **Route Analysis:** Identified the farthest trip as a **144.1-mile journey** from the Lower East Side to Crown Heights North.
* **Hotspots:** **Penn Station/Madison Sq West** remains the high-pressure zone with **4.5K pickups**.

---

## 💡 Key Business Recommendations
* **Night Shift Incentives:** Shift 15% more driver supply to the 8:00 PM – 2:00 AM window on weekends to capture the high-value "Night Trip" market.
* **Station Staging:** Implement a "Fast-Track" pickup lane at Penn Station to lower the **16-minute average trip time**.
* **Vehicle Strategy:** Since **UberX** is the volume leader ($583K revenue), prioritize these vehicles in high-density zones like **Kips Bay** and **East Village**.

---

## ⚙️ Technical Skills 
* **Data Source:** Analyzed 103,728 rows of trip data.
* **Tools:** Power BI (DAX, Time-Series Modeling, Geospatial Mapping).
* **Metrics:** AVO (Average Order Value), Revenue Density, and Demand Heatmapping.
