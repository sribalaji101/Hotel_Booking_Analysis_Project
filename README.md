# Hotel Booking Analysis Project
## Overview  
This project involves analyzing hotel booking data to uncover key insights into booking cancellation patterns, customer behavior, and pricing strategies. It focuses on identifying factors influencing cancellations, comparing city and resort hotels, and providing actionable recommendations to improve hotel revenue and reduce cancellations.  

---

## Key Steps  

### 1. Data Loading and Cleaning  
- Loaded the dataset and examined its structure and attributes.  
- Cleaned the data by handling missing values and ensuring consistency.  
- Conducted an exploratory data analysis (EDA) to understand key variables.  

### 2. Analysis and Insights  
- **Cancellation Trends:**  
  - Found that 37% of bookings were canceled, significantly impacting revenue.  
  - Observed that cancellations peak in January and during periods with higher room rates.  

- **Booking Patterns:**  
  - City hotels received more bookings than resort hotels.  
  - Higher prices correlated with higher cancellation rates.  

- **Customer Segments:**  
  - Analyzed market segments, finding that 46% of bookings were made via online travel agencies, while direct bookings accounted for only 4%.  

- **Geographic Trends:**  
  - Found that the highest number of cancellations came from customers in Portugal (country code `PRT`).  

### 3. Visualization  
- Used Matplotlib and Seaborn to create detailed visualizations, including:  
  - Bar graphs for cancellation rates and monthly booking trends.  
  - Line graphs comparing average daily rates (ADR) of city and resort hotels.  
  - Market segment distribution analysis.  
  - Country-wise cancellation distribution.  

---

## Tools and Libraries  
- **Programming Language:** Python  
- **Libraries Used:**  
  - `pandas`  
  - `seaborn`  
  - `matplotlib`  
  - `warnings`  

---

## Key Insights  
- **Cancellation Rates:**  
  - High cancellation rates directly correlate with higher ADR.  ![output_48_0](https://github.com/user-attachments/assets/f1931a30-f352-4fc7-8aaf-36b570f84738)

  - January has the highest cancellation rates, indicating potential for targeted campaigns.  ![output_52_0](https://github.com/user-attachments/assets/8f3a76d8-3f00-4a51-ad4c-ebf164115021)

- **Hotel Types:**  
  - City hotels generally receive more bookings but experience a similar cancellation pattern to resort hotels.  ![output_29_0](https://github.com/user-attachments/assets/5e528a49-c251-4bf3-8011-68803909e816)

- **Pricing Influence:**  
  - Higher prices significantly increase cancellation rates, suggesting the need for dynamic pricing strategies.  ![output_64_1](https://github.com/user-attachments/assets/2d71ca9d-d616-4d27-8e40-f8e5fe8658a0)

- **Customer Sources:**  
  - Online travel agencies dominate as the primary booking source, offering an area for potential partnership enhancements.

- **Geographic Trends:**  
  - Found that the highest number of cancellations came from customers in Portugal![output_54_0](https://github.com/user-attachments/assets/1ae5b125-c54d-42db-af0f-f71e4bc01543)


---

## Recommendations  
1. **Dynamic Pricing Strategies:**  
   - Adjust room rates based on demand patterns to minimize cancellations.  
2. **Targeted Discounts and Promotions:**  
   - Offer discounts during January to reduce cancellation impact.  
   - Provide weekend and holiday discounts, especially for resort hotels.  
3. **Quality Enhancements:**  
   - Focus on improving facilities in regions with high cancellations, such as Portugal (`PRT`).  
4. **Direct Booking Campaigns:**  
   - Increase direct bookings through marketing campaigns to reduce reliance on third-party platforms.  

---
