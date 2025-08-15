## 📌 Project Overview
This project delivers an **interactive data visualization** of more than **1,300 verified and unverified customer reviews** of British Airways.  
It combines structured ratings (comfort, staff, food, etc.) with free-text feedback, enriched with **geographic metadata** to analyze satisfaction by country, region, and continent.  
Ultimately, it turns raw review data into actionable insights for airline service improvement.

---

## 📂 Data Description

### 1) `ba_reviews.csv`
- **Rows:** 1,324  
- **Columns:** 19  
- **What’s inside:** one row = one review. Text + structured ratings + flight details.

**Key columns**
- `header` — review title  
- `author` — reviewer name  
- `date` — review date  
- `place` — reviewer country  
- `content` — full review text  
- `aircraft` — aircraft type (e.g., A320, A380)  
- `traveller_type` — Business, Couple Leisure, Solo Leisure, etc.  
- `seat_type` — Economy, Premium Economy, Business, First  
- `route` — origin → destination (string)  
- `date_flown` — flight date  
- **Ratings (0–10 or -1 = missing):**  
  `rating`, `seat_comfort`, `cabin_staff_service`, `food_beverages`, `ground_service`, `value_for_money`, `entertainment`


### 2) `Countries.csv`
- **Rows:** 251  
- **Columns:** 4  
- **Purpose:** join table for geography (continent/region).
- Columns: `Country`, `Code` (ISO-3), `Continent`, `Region`

---



## 🚀 How to Run
1. Open **Tableau Desktop** (or upload to **Tableau Public**).
2. Open `Airways Dashboard.twbx`. The data is packaged; it should load as-is.
3. Use filters: Date range, Seat Type, Traveller Type, Aircraft, Country, Route.
4. Hover for tooltips; click bars/map to cross-filter.

### Or

## 🎛️ Open Dashboard Link : 
https://public.tableau.com/app/profile/youssef.eissa8870/viz/AirwaysDashboard_17552015499560/Dashboard?publish=yes
