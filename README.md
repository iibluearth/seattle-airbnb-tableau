# 🏡 Seattle Airbnb Tableau Project

🔗 **[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/kayla.mann/viz/AirBnBFullProject_17585723461060/Dashboard1?publish=yes)

## 📊 Resources
- **Dataset:** [Kaggle: Seattle Airbnb Open Data](https://www.kaggle.com/datasets/airbnb/seattle)
- **Tools Used:** Microsoft Excel, Tableau

## 📘 Project Overview

### Context
Since 2008, Airbnb has provided a unique and personalized way for guests and hosts to connect.  
As part of the Airbnb Inside initiative, this dataset captures the listing activity of homestays in Seattle, WA.

### Content
The dataset includes:
- **Listings**: Full descriptions and average review scores  
- **Reviews**: Unique IDs for reviewers with detailed comments  
- **Calendar**: Daily prices, listing IDs, and availability  

### Inspiration
This analysis seeks to answer:
- What is the vibe of each Seattle neighborhood based on listings?  
- What are the busiest times of year to visit Seattle? How much do prices spike?  
- Are Airbnb listings and visitors in Seattle trending upward?

---

## 📊 Key Tables & Findings

### Average Price by Zipcode
| Zipcode | Avg Price |
|---------|-----------|
| 98134   | 206.6     |
| 98119   | 171.1     |
| 98101   | 166.9     |
| 98109   | 158.6     |
| 98121   | 154.0     |
| 98199   | 151.8     |
| 98116   | 145.7     |
| 98136   | 144.1     |
| 98112   | 143.4     |
| 98104   | 135.2     |
| 98122   | 133.3     |
| 98102   | 127.3     |
| 98126   | 127.2     |
| 98107   | 123.1     |
| 98103   | 122.3     |
| 98115   | 109.9     |
| 98144   | 105.4     |
| 98105   | 104.1     |
| 98146   | 97.8      |
| 98117   | 95.1      |
| 98178   | 94.7      |
| 98118   | 93.8      |
| 98108   | 84.8      |
| 98177   | 84.2      |
| 98106   | 76.9      |
| 98133   | 71.0      |
| 98125   | 64.7      |

---

### Revenue by Week (2016)
Revenue trends show seasonality, with peaks during summer and winter travel periods.  
- **Weeks Observed:** Jan 10, Feb 7, Mar 6, Apr 3, May 1, May 29, Jun 26, Jul 24, Aug 21, Sep 18, Oct 16, Nov 13, Dec 11, Jan 8 (2017).  
- **Range:** 0K – 2200K total weekly revenue. 

---

### Average Price by Bedrooms
| Bedrooms | Avg Price |
|----------|-----------|
| 1        | 96.2      |
| 2        | 175.4     |
| 3        | 249.7     |
| 4        | 315.4     |
| 5        | 450.0     |
| 6        | 584.8     |

---

### Distinct Count of Listings by Bedrooms
| Bedrooms | Distinct Listings |
|----------|--------------------|
| 1        | 1,811              |
| 2        | 483                |
| 3        | 206                |
| 4        | 55                 |
| 5        | 20                 |
| 6        | 5                  |

---

## 📈 Tableau Visualizations
Created in Tableau:
- **Price by Zipcode (Bar Graph)** → `SUM of AVG(Price)`  
- **Price per Zipcode (Filled Map)** → `SUM of AVG(Price)`  
- **Revenue for the Year (Line Graph)** → `SUM(Price [Calendar])`  
- **Avg Price per Bedroom (Bar Graph)** → `SUM of AVG(Price)`  
- **Distinct Count of Bedroom Listings (Table)** → `SUM of CNTD(Id)`  

➡️ All graphs were combined into an **interactive dashboard**.  

---

## 🖼️ Dashboard Preview

<img src=https://i.imgur.com/szk5pMq.png/>
</p>

---

## 🔎 Key Insights

### 1. Vibe of Seattle Neighborhoods  
- **High-priced, upscale areas (98134, 98119, 98101, 98109):** These neighborhoods reflect a premium, urban vibe with luxury condos, modern apartments, and properties close to downtown attractions.  
- **Mid-range areas (98116, 98112, 98122, 98103):** Balanced neighborhoods with family homes and cozy apartments, popular among both tourists and long-term visitors.  
- **Affordable areas (98133, 98125, 98106, 98108):** Budget-friendly neighborhoods further from downtown, offering value stays and practical rentals.  

➡️ Overall, Seattle offers a mix of **luxury urban stays, neighborhood charm, and budget options**, giving visitors diverse experiences depending on preference and budget.  

---

### 2. Busiest Times of Year & Price Spikes  
- **Peak demand:** Summer months (June–August) and the holiday season (November–December).  
- **Revenue growth:** Weekly revenue exceeds **$2M during peak times**, compared to under $1M in slower months.  
- **Price spikes:** Average nightly prices increase by **20–40%** during high-demand periods.  

➡️ Seattle is busiest in **summer and holidays**, with clear seasonal pricing spikes.  

---

### 3. Upward Trend in Listings & Visitors  
- Revenue line graphs show a **steady increase throughout the year**, signaling growth in bookings and visitor activity.  
- Expansion of 1-bedroom listings indicates rising supply, while higher revenue confirms growing demand.  

➡️ Seattle’s Airbnb market is on an **upward trend**, with both listings and visitors increasing over time.  
