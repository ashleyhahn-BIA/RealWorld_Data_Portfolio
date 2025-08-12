# Customer Segmentation Analysis – Zomato

**Tools:** Power BI | DAX | Data Cleaning | Data Modeling | Business Insights
## 📌 Project Overview
This project analyzes **millions of transactional and demographic records** from Zomato to uncover patterns in customer behavior.  
The goal was to identify:
- **High-value customer segments** based on repeat purchase activity
- **Regional differences** in order patterns
- **Top-performing product categories** driving sales

The findings informed strategies for **customer retention, targeted marketing, and product optimization**.

![](<Screenshot 2025-08-12 134234.png>)
---

## 🛠 Data & Preparation

**Data Sources:**
- **Orders** – Transaction-level data (sales, date, restaurant ID)  
- **Restaurant** – City, cuisine, cost for two  
- **Users** – Demographics (age, gender, income)  
- Additional **city-to-region mapping** file for Urban/Rural classification  

**Transformations & Data Modeling:**
- **Created calculated columns:**
  - `Age Group` – Segmented customers into ranges (18–24, 25–34, etc.)
  - `IsRepeat` – Flagged repeat customers
  - `RegionType` – Classified cities into *Urban* or *Rural*
  - `CleanCuisine` – Consolidated cuisine naming inconsistencies
- **Created DAX measures:**
  - `Max Revenue by Age Group`
  - `Top Revenue Age Group`
- Cleaned null values, removed duplicates, and aggregated purchase history  
- Built **relationships** between transactional, demographic, and restaurant datasets

---

## 📊 Key Insights & Impact

### 1. **High-Value Age Segments**
- Ages **18–24** emerged as the most **profitable and loyal segment**, generating **$552M** in revenue.
- Males aged 25–34 placed **more repeat orders** than their female counterparts.
- **Impact:** Guided marketing to focus on **youth loyalty programs** and upselling to the **25–34 age group**.

### 2. **Urban vs. Rural Purchase Patterns**
- Urban customers placed **113.96K orders**, 3× higher than rural customers (**34.30K orders**).
- Over **60% of total revenue** came from urban centers.
- **Impact:** Confirmed that **urban delivery zones** should remain the primary focus for growth, while rural campaigns should be highly targeted.

### 3. **Product Category Trends**
- **Top cuisines:**  
  - North Indian – 32.5K orders  
  - Chinese – 25.9K orders  
  - Fast Food – 11K orders
- Orders concentrated in a **small set of high-demand cuisines**.
- **Impact:** Led to recommendations for **app UX optimization** to prominently feature high-performing cuisines.

---

## 📈 Business Recommendations
1. **Target 18–24 age group** with loyalty/reward programs and weekend promotions.
2. **Upsell to 25–34 age group** through personalized offers.
3. Maintain **urban delivery focus** and expand partnerships with top-performing urban restaurants.
4. Promote **North Indian & Chinese cuisines** through in-app banners and push notifications.
5. Partner with high-demand restaurants for **co-branded campaigns**.

---

## 🖥 Dashboard Preview
![Dashboard Screenshot 1](LINK_TO_IMAGE_1)
![Dashboard Screenshot 2](LINK_TO_IMAGE_2)
![Dashboard Screenshot 3](LINK_TO_IMAGE_3)

---

## 🔗 Interactive Dashboard
[View the Live Power BI Dashboard](LINK_TO_DASHBOARD)

---

## 🚀 Skills Demonstrated
- End-to-end **data cleaning, modeling, and transformation**
- **DAX measures** for dynamic segmentation and revenue analysis
- **Visual storytelling** through Power BI dashboards
- Translating data into **clear, actionable business strategies**
