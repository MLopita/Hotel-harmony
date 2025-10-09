# Hotel Harmony: Data Insights for Optimized Operations  
### Leveraging Data Analytics to Enhance Hotel Performance and Guest Satisfaction  
**By:** Lopita Mishra  

## Project Overview  
**Company:** Elite Hotels International  
**Industry:** Hospitality  
**Scenario:**  
Elite Hotels International operates multiple properties across diverse regions and is facing challenges in managing booking patterns, cancellations, and customer satisfaction.  This project applies data-driven analysis to identify key trends in hotel bookings, cancellations, and guest preferences to support operational optimization and strategic decision-making.

**Objective:**  
To analyze hotel booking data to derive insights that can help optimize operations, enhance guest experiences, and improve overall revenue performance.

**EDA Notebook:**  
[Open in Google Colab](https://colab.research.google.com/drive/1ockrq2j2hEirLicnDOGqhQbN8__P0z9X)

## Problem Statement  
**Problem:**  
Elite Hotels International seeks to understand and optimize booking behaviors, reduce cancellations, and improve guest satisfaction metrics.  

**Importance:**  
Addressing this challenge will:  
- Improve operational efficiency and resource utilization.  
- Enhance guest satisfaction and loyalty.  
- Boost revenue through better demand forecasting and pricing strategies.

## Dataset Information  
**Source:** [Hotel Booking Demand Dataset – Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand)
| Column | Description |
|--------|-------------|
| hotel | Name of the hotel (Resort Hotel or City Hotel) |
| is_canceled | 1 = booking canceled, 0 = not canceled |
| lead_time | Days between booking and arrival |
| arrival_date_year | Year of arrival |
| arrival_date_month | Month of arrival |
| stays_in_weekend_nights | Weekend nights stayed |
| stays_in_week_nights | Weeknights stayed |
| adults | Number of adults |
| children | Number of children |
| babies | Number of babies |
| meal | Type of meal booked |
| country | Country of origin |
| market_segment | Market segment designation |
| distribution_channel | Channel through which booking was made |
| is_repeated_guest | 1 = repeated guest, 0 = new guest |
| previous_cancellations | Count of previous cancellations |
| previous_bookings_not_canceled | Previous successful bookings |
| reserved_room_type | Reserved room type code |
| assigned_room_type | Room type assigned |
| booking_changes | Number of booking changes |
| deposit_type | Deposit type (No Deposit / Non Refund / Refundable) |
| agent | Travel agency ID |
| company | Company ID |
| days_in_waiting_list | Days booking waited for confirmation |
| customer_type | Type of customer (Transient, Contract, Group, etc.) |
| adr | Average Daily Rate |
| required_car_parking_spaces | Number of parking spaces required |
| total_of_special_requests | Number of special requests |
| reservation_status | Final reservation status (Canceled, Checked-Out, No-Show) |
| reservation_status_date | Date of the last reservation status update |

## Stakeholders  
| Type | Stakeholders |
|------|---------------|
| Internal | Management Team, Operations Team, Marketing Team, Customer Service Team |
| External | Guests, Travel Agencies, Suppliers |

## Data Preparation  
### Data Cleaning Steps  
- Handled missing values in columns like `agent`, `company`, and `children`  
- Converted date columns into proper datetime formats  
- Checked and removed duplicates  
- Standardized categorical text fields  

### Data Transformation  
- Created metrics for lead time, cancellation rate, occupancy rate, and revenue trends  
- Aggregated data by hotel type, market segment, and customer type for trend analysis  

## Exploratory Data Analysis (EDA)  
The analysis was conducted in Google Colab using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.  

### Key Analyses Performed  
- Distribution of bookings across hotel types (Resort vs City)  
- Cancellation trends by lead time and deposit type  
- Monthly and yearly ADR (Average Daily Rate) trends  
- Market segment and distribution channel performance  
- Relationship between special requests, ADR, and guest satisfaction  
- Popular arrival months and peak seasons  
- Comparison of repeated vs new guest behaviors  

## Key Insights  
| Insight | Business Impact |
|----------|----------------|
| Resort hotels have higher ADR but also higher cancellation rates | Need for better cancellation policies and flexible pricing |
| Majority of bookings are from Online Travel Agents (OTAs) | Partnerships with OTAs should be strengthened |
| Most bookings occur between June and August | Indicates a strong seasonal demand peak |
| Average lead time is around 90–100 days | Early bookings enable dynamic pricing strategies |
| Guests with more special requests tend to have higher ADR | Indicates a premium customer segment |
| Repeated guests stay longer and have fewer cancellations | Loyalty programs can improve retention |
| Car parking demand is higher in Resort Hotels | Operational planning for parking capacity required |

## Strategic Recommendations  
1. **Cancellation Management:**  
   Introduce flexible booking policies and deposit options to reduce cancellation rates.  

2. **Revenue Optimization:**  
   Adjust ADR dynamically based on seasonality, lead time, and booking channel.  

3. **Customer Loyalty Focus:**  
   Create targeted campaigns and loyalty rewards for repeat customers.  

4. **Market Segmentation:**  
   Focus marketing efforts on high-value market segments and countries with frequent bookings.  

5. **Operational Efficiency:**  
   Utilize special request and stay duration data to optimize housekeeping and staffing schedules.  

## Tools & Technologies  
| Tool | Purpose |
|------|----------|
| Python (Google Colab) | Data Cleaning & Analysis |
| Pandas, Matplotlib, Seaborn | Statistical & Visual Analysis |
| Excel | Data validation and initial exploration |
| Kaggle | Dataset Source |
| GitHub | Project hosting & documentation |

## Deliverables  
1. **Colab EDA Notebook:** [Hotel Harmony – EDA File](https://colab.research.google.com/drive/1ockrq2j2hEirLicnDOGqhQbN8__P0z9X)  
2. **Case Study Document:** Problem definition, data dictionary, and guided analysis questions  
3. **Insights Report:** Summary of findings, visualizations, and recommendations  

## Project Outcomes  
- Improved understanding of booking patterns and customer behavior  
- Identified key factors influencing cancellations and ADR  
- Formulated actionable strategies for marketing and operations  
- Demonstrated use of data analytics in optimizing hotel performance  

## Author  
**Lopita Mishra**  
Email: lopitamishra2001@gmail.com  
LinkedIn: https://linkedin.com/in/lopita-mishra-096534191  
Portfolio: https://lopita-mishra-portfolio.netlify.app/  
GitHub: https://github.com/MLopita  
