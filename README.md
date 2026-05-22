# Uber India Data Analysis

## Project Overview

This project provides a comprehensive business intelligence dashboard analyzing Uber ride data in India. The dashboard evaluates operational performance, financial metrics, vehicle utilization, and cancellation trends to uncover actionable insights for service optimization and revenue growth.

## Executive Summary

* **Total Completed Rides:** 93,000
* **Total Revenue:** 47,260,574
* **Average Driver Rating:** 4.23 | **Average Customer Rating:** 4.40
* **Cancellation Rate:** 25% (37,500 cancelled orders)
* **Revenue per KM:** 20
* **Dominant Vehicle Category:** Auto (23,155 completed rides; 11,727,615 in revenue)
* **Dominant Payment Method:** UPI (45% of total revenue)

## Dashboard Structure

The analysis is divided into four primary segments:

1. **Summary:** High-level overview of ride volume, booking statuses, and time-of-day demand trends.
2. **Vehicles:** Granular breakdown of performance by vehicle type, average ride distances, and pickup/ride duration metrics.
3. **Cancelled:** Detailed analysis of cancellation origins (driver vs. customer) and underlying reasons, alongside unmet demand ("No Driver Found" metrics).
4. **Revenue:** Financial breakdowns by month, vehicle type, payment method, and top customer contributions.

---

## Key Insights and Analysis

### 1. Operational & Demand Trends

* **Peak Utilization:** Demand surges between 4:00 PM and 8:00 PM, peaking sharply at 6:00 PM. This evening rush accounts for the bulk of daily ride volume.
* **Supply Deficit:** The "No Driver Found" metric strictly correlates with peak demand hours (5:00 PM - 7:00 PM), indicating that driver supply is failing to meet customer demand during crucial high-revenue windows.
* **Booking Status:** 62% of all requested rides are completed successfully. However, the 25% overall cancellation rate and 6% "No Driver Found" rate represent a significant loss in potential revenue.

### 2. Vehicle Performance

* **Market Preference:** "Auto" is the undisputed leader in both volume (37,419 total requests / 23,155 completed) and revenue (11.7M). "Go Mini" and "Go Sedan" follow as the next most popular choices.
* **Underutilization:** Premium and larger options (Uber XL, eBike) see significantly lower volume. Despite the varying capacities and vehicle types, the average ride distance remains almost perfectly static across all categories (~24.6 KM), suggesting users treat all vehicle tiers similarly regarding trip distance.

### 3. Cancellation Dynamics

* **Driver-Driven Cancellations:** Drivers are responsible for the vast majority of cancellations (72%). The most frequently cited reasons are "Customer related issue," "The customer was coughing/sick," and "Personal & car related issues."
* **Customer-Driven Cancellations:** Customers account for 28% of cancellations. The primary reasons are relatively evenly distributed among "Wrong Address," "Change of plans," and "Driver is not moving towards pickup."

### 4. Financials

* **Payment Preferences:** The Indian market heavily favors digital payments. UPI dominates at 45% of total revenue (21.2M), followed by Cash (25%). Credit and Debit cards make up a smaller fraction of the market share.
* **Revenue Stability:** Monthly revenue remains relatively stable, hovering between 3.8M and 4.2M, with a notable peak in March and a dip in February.

---

## Strategic Recommendations & Next Steps

Based on the data analysis, the following business actions are recommended:

**1. Optimize Peak Hour Supply**

* **Action:** Implement targeted driver incentive programs and surge pricing adjustments specifically between 4:00 PM and 8:00 PM.
* **Goal:** Reduce the high "No Driver Found" rate during these hours to capture lost revenue and improve customer reliability scores.

**2. Address Driver Cancellation Rates**

* **Action:** Investigate the high volume of "Customer related issue" and "Sickness" cancellations. Implement a stricter review process for driver-initiated cancellations and introduce a standardized pre-ride verification prompt.
* **Goal:** Lower the 72% driver cancellation share and improve the 62% successful completion rate. Ensure drivers are not using ambiguous reasons to avoid undesirable routes.

**3. Capitalize on Vehicle Tier Preferences**

* **Action:** Allocate marketing budget and driver onboarding efforts toward the highest-performing tiers: Auto and Go Mini. Evaluate the ROI of maintaining low-performing tiers like Uber XL; consider running promotional discounts to increase their utilization or phasing out underperforming assets.
* **Goal:** Maximize asset turnover and align fleet availability with actual consumer preferences.

**4. Leverage UPI Dominance**

* **Action:** Deepen integrations and partnerships with major UPI providers (e.g., PhonePe, Google Pay, Paytm). Offer localized cashback campaigns for users who maintain UPI as their default payment method.
* **Goal:** Further reduce reliance on cash transactions (currently 25%), lowering friction for drivers and improving transaction security and speed.

---

## Technical Details

* **Data Sources:** Uber India Rides from kaggle.
* **Tools Used:** Excel.
