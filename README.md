# Hotel Hospitality Analysis

### Link to [Interactive Dashboard](https://www.novypro.com/profile_about/ibrahim-saiied-1?Popup=memberProject&Data=1740543412374x486468345160050240)

<div align="center">
    <img src="https://github.com/user-attachments/assets/b8cbeeef-942f-4db5-b781-a95d160fa329" alt="image" width="400" height="400">
</div>



## Introduction
<details>
   <summary><strong>📌 Overview (click)</strong></summary>

 ### **Overview**  
> This Power BI project provides a detailed analysis of **Lorem Ipsum Group's** performance, covering **revenue**, **occupancy rates**, and **booking trends**.  
> The analysis aims to uncover **insights** across various **properties and cities**, offering **data-driven recommendations** to **enhance revenue generation**, **optimize occupancy**, and **improve overall operational efficiency**.  

</details>


<details>
   <summary><strong>📂 Data Sources (click)</strong></summary>

### **Data Sources**  
> The primary dataset used for this analysis is the **"fact_bookings.csv"** file containing detailed information about each booking made by the customers.  

**▼ 📑Dataset Files Explanation** [[Download]](https://raw.githubusercontent.com/ibrahim-saiied/Hotel-Hospitality-Analysis/refs/heads/main/Data%20Set.rar)  

1. **Dim_date File**  
   > - **<ins>date</ins>**: Represents the dates present in **May, June, and July**.  
   > - **<ins>mmm yy</ins>**: Shows the date in the **"mmm yy"** format.  

2. **Dim_hotels File**  
   > - **<ins>property_id</ins>**: Unique ID for each **hotel**.  
   > - **<ins>property_name</ins>**: Name of each **hotel**.  
   > - **<ins>category</ins>**: Defines which **class** (**Luxury**, **Business**) a **property** belongs to.  
   > - **<ins>city</ins>**: The **location** of the **hotel/property**.  

3. **Dim_rooms File**  
   > - **<ins>room_id</ins>**: Represents the **type of room** (**RT1**, **RT2**, **RT3**, **RT4**) in a **hotel**.  
   > - **<ins>room_class</ins>**: Indicates to which **class** (**Standard**, **Elite**, **Premium**, **Presidential**) the **room type** belongs.  

4. **Fact_aggregated_bookings File**  
   > - **<ins>property_id</ins>**: Unique ID for each **hotel**.  
   > - **<ins>check_in_date</ins>**: All the **check-in dates** of the **customers**.  
   > - **<ins>room_category</ins>**: Type of **room** (**RT1**, **RT2**, **RT3**, **RT4**) in a **hotel**.  
   > - **<ins>successful_bookings</ins>**: All the **successful room bookings** for a particular **room type** on a **specific date**.  
   > - **<ins>capacity</ins>**: Maximum **rooms available** for a particular **room type** on a **specific date**.  

5. **Fact_bookings File**  
   > - **<ins>booking_id</ins>**: Unique **Booking ID** for each **customer** when booking **rooms**.  
   > - **<ins>property_id</ins>**: Unique ID for each **hotel**.  
   > - **<ins>booking_date</ins>**: Date of **room booking** by the **customer**.  
   > - **<ins>check_in_date</ins>**: Date of **check-in** at the **hotel**.  
   > - **<ins>check_out_date</ins>**: Date of **check-out** from the **hotel**.  
   > - **<ins>no_guests</ins>**: Number of **guests** who **stayed** in a **room**.  
   > - **<ins>room_category</ins>**: Type of **room** (**RT1**, **RT2**, **RT3**, **RT4**) in a **hotel**.  
   > - **<ins>booking_platform</ins>**: The **platform** used by the **customer** to **book the room**.  
   > - **<ins>ratings_given</ins>**: **Ratings** provided by the **customer** for **hotel services**.  
   > - **<ins>booking_status</ins>**: Indicates whether the **customer** **Cancelled**, **Checked Out**, or **No Show**.  
   > - **<ins>revenue_generated</ins>**: **Amount of money generated** by the **hotel** from the **customer**.  
   > - **<ins>revenue_realized</ins>**: **Final revenue** for the **hotel** based on **booking status**.  
       - If **Cancelled**, **40%** is **refunded** to the **customer**.  
       - If **Checked Out/No Show**, the **hotel** retains the **full amount**.
   
</details>


## Case Study
Lorem Ipsum Group owns multiple hotels across Egypt. Due to strategic moves from other competitors and ineffective decision-making, Lorem Ipsum are losing its market share.
They need to provide them insights from their historical data and Create a dashboard according to the data provided by stakeholders form the last 3 months in 2022.

## Process
1) Explore, understand and validating all data.
2) Importing and clean data and Adding some columns to aid in data analysis, such as a column to identify the day type weekend or weekday with power query. 
3) Data modeling
4) Creating Measures using DAX
5) Creating the Dashboard

## Measures
;
<img src="https://github.com/user-attachments/assets/cb3a363e-c8ab-48dd-927b-0d9092c9ef8f" alt="image" width="175" height="320" style="display: block; margin: 0;">

## Data Model
![image](https://github.com/user-attachments/assets/05a73c82-d1ea-44e2-bda2-58739c0c8f91)

## Dashboard
![file_2](https://github.com/user-attachments/assets/98de9529-d1af-4518-a918-48f9cb60a34a)


## Insights & Recommendations
1) **City Performance**
   - Hurghada is the highest in revenue, while Cairo However has high occupancy, suffers from many cancellations. It’s important to find out why Cairo has so many cancellations.

2) **Elite Customers**
   - Need to focus more on Elite customers because they drive the revenue boost, and it has the highst cancelation should be prioritized more as it has the highest influence on revenue
(like better communication or flexible booking options)

3) **Trend Changes**
   - Revenue, bookings, and cancellations started decreased on July 10, 2022, then decreased notably on July 26, 2022. This suggests something changed during that period, so further investigation is needed.

4) **Lorem Seasons**
   - Lorem Seasons is earning much less revenue compared to others. Enhancing its marketing strategy could improve its performance.









