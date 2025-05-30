# 🏙️ New York City Airbnb Data Analysis Case Study

## 📌 Objective

This case study explores the Airbnb rental market in New York City using 2019 listing data. The goal is to uncover key insights into pricing strategies, host behavior, and the impact of local regulations, and to provide actionable recommendations for hosts, guests, and policymakers.

---

## 📂 Dataset Overview

- **Source:** NYC Airbnb Open Data (2019)
- **Entries:** 38,821
- **Key Columns:**  
  - `price`, `minimum_nights`, `room_type`, `availability_365`, `number_of_reviews`, `neighbourhood_group`, `latitude`, `longitude`, `host_id`

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** – data cleaning and transformation  
- **Seaborn & Matplotlib** – visualizations (KDE plots, bar charts, heatmaps)  
- **Folium** – interactive geographic heatmap  
- **Jupyter Notebook** – analysis environment

---

## 🔍 Key Insights

### 1. Price Trends
- Manhattan and Brooklyn listings are priced **50–100% higher** than other boroughs.
- Majority of listings are under $169/night, but outliers exist up to $10,000/night.

### 2. Regulatory Impact
- **44%** of entire home listings have a **30-day minimum stay**, reflecting NYC's rental laws.
- Entire homes show limited availability due to short-term rental restrictions.

### 3. Demand Patterns
- **Affordable private rooms** (often < $150) in accessible locations receive **more reviews**, indicating higher occupancy and guest satisfaction.
- Weak correlation between price and reviews/availability suggests **independent pricing strategies**.

### 4. Host Behavior
- Most hosts manage fewer than 2 listings; large-scale hosts focus on volume, small hosts on premium pricing.

---

## 📊 Visualizations

- Price distributions by borough and room type  
- Geographic revenue heatmap using latitude and longitude  
- Room type variation across NYC  
- KDE plots for minimum nights, availability, and host listing counts

---

## ✅ Recommendations

### For Hosts
- Price private rooms below **$150/night** in Manhattan to increase occupancy and reviews.

### For Guests
- Explore listings in **Queens or the Bronx** for budget stays.
- Book **3–6 months in advance** for high-demand areas.

### For Policymakers
- Enforce the **30-day minimum stay law** to prevent misuse of short-term rental platforms.

---

## 👤 Author

**Umashankar Prajapati**  
B.Tech in Chemical Engineering, Minor in Management  
Indian Institute of Technology Jodhpur

---

## 📎 Project Files

- `notebooks/` – analysis notebooks  
- `visualizations/` – generated charts and plots  
- `NYC_Airbnb_Case_Study.pdf` – detailed report  
- `README.md` – project overview

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [LinkedIn](https://www.linkedin.com) or email at *your.email@example.com*.

