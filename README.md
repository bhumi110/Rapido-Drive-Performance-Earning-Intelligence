# Rapido Driver Performance & Earning Intelligence

An interactive **Power BI analytics project** focused on analyzing Rapido's driver ecosystem across earnings, operational performance, service quality, and recruitment.

The project transforms a heavily unclean ride-hailing dataset into structured, meaningful insights to understand driver performance and identify potential business improvement opportunities.

---

## 📌 Project Overview

Driver Performance Hub provides a comprehensive view of driver operations through four interactive dashboards.

The analysis focuses on understanding:
- Driver activation and distribution across cities.
- Earnings patterns across different driver segments.
- Trip completion and cancellation performance.
- Customer feedback and driver service quality.
- Recruitment, selection, and onboarding effectiveness.

The objective is to turn raw data into actionable insights that can support operational and business decisions.

## 📊 Dashboard Pages

### 1. Executive Overview
Provides a high-level snapshot of overall driver performance.

**Key Metrics:**
- Total Drivers
- Active Drivers
- Driver Activation Rate
- Average Daily Earnings
- Average Driver Rating
- Average Trip Completion Rate
- Total Trips Completed

**Analysis:**
- Driver distribution across cities.
- Active vs. inactive driver comparison.
- City-wise average earnings.
- Driver performance overview.

### 2. Earnings & Performance
Analyzes driver earnings and operational performance across different segments.

**Analysis:**
- Average daily earnings by city.
- Earnings by vehicle type.
- Earnings by driver experience.
- Earnings across preferred shifts.
- Earnings by driver rating.
- Trip completion and cancellation rates.

### 3. Driver Quality
Evaluates driver service quality and customer experience.

**Analysis:**
- Customer complaints and compliments.
- Average driver ratings across cities.
- Trip completion rates by city.
- Cancellation rates.
- Driver experience and completion performance.
- Peak-hour availability analysis.

### 4. Recruitment & Onboarding
Analyzes the driver recruitment funnel and onboarding process.

**Analysis:**
- Total applicants.
- Selected, rejected, and on-hold candidates.
- Recruitment selection rate.
- Average interview scores by recruitment result.
- Rejection reasons.
- Document verification status.
- Background check status.
- Monthly recruitment trends.

---

## 📂 Dataset Information

The original dataset contained:

| Feature | Details |
|:---|:---|
| Rows | 50,000 |
| Columns | 33 |
| Platforms | Uber, Rapido |
| Domain | Ride-hailing, HR Analytics, Driver Recruitment |

**Project Scope:** Although the original dataset contained records from multiple ride-hailing platforms, this project specifically focuses on Rapido.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|:---|:---|
| Power BI | Dashboard development and visualization |
| SQL Server | Data cleaning and transformation |
| DAX | Calculated measures and business KPIs |

---

## 🧹 Data Cleaning & Preparation

One of the major parts of this project was working with a heavily unclean dataset.

The data preparation process involved:

- Identifying and handling missing values.
- Handling missing numerical values using median.
- Removing records with missing customer names.
- Identifying data inconsistencies.
- Filtering the dataset to focus specifically on Rapido.
- Preparing the cleaned data for analysis and visualization.

This process helped transform the original dataset into a more structured and analysis-ready format.


**Key Observations:**

1. **Driver Activation:** Only 49.5% of registered drivers are active, indicating an opportunity to investigate driver engagement and retention.

2. **City-wise Earnings:** Hyderabad recorded the highest average daily earnings at ₹1,492, while Jaipur recorded the lowest at ₹1,404.

3. **Customer Feedback:** The platform received approximately 7.21 lakh compliments compared to 3.62 lakh complaints.

4. **Trip Completion:** The trip completion rate indicates scope for investigating cancellations and operational inefficiencies.

5. **Recruitment:** The selection rate stands at 34.24%, with poor communication being the most frequently recorded rejection reason.


## 💡 Key Learnings

Through this project, I gained practical experience in:

- Working with heavily unclean real-world datasets.
- Identifying and handling missing values and data inconsistencies.
- Applying appropriate data-cleaning techniques.
- Preparing and structuring data for Power BI.
- Developing DAX measures for business KPI calculations.
- Designing interactive dashboards.
- Translating analytical findings into business insights.

## 🎯 Business Recommendations

Based on the analysis, potential areas of improvement include:

- Investigating the reasons behind driver inactivity.
- Understanding city-wise differences in driver earnings.
- Identifying major reasons for trip cancellations.
- Improving service quality through customer feedback analysis.
- Optimizing recruitment screening and onboarding processes.

---
⭐ If you find this project interesting, feel free to explore the repository!
