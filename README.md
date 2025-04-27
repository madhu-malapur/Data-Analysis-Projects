# 📊 Zomato Data Analysis—Interactive Dashboard Creation Using Power BI

## Project Overview

This project is a Zomato Analysis Dashboard built to visualize key restaurant metrics. It shows insights like total votes, ratings, average cost, and total restaurants. The dashboard includes year-wise restaurant counts, city-wise distribution, table booking availability, and top-rated restaurants and cuisines, offering a complete overview of Zomato’s restaurant data.



## Download Dataset

You can download the dataset used for this project here:

👉 [Download Zomato_Restaurant_Data.xlsx](https://github.com/madhu-malapur/YOUR-REPO-NAME/raw/main/Zomato_Restaurant_Data.xlsx)


# 📊 Zomato Dashboard KPIs

- **Currency Conversion:**
  - Convert the `Average Cost for 2` column into USD (currently in local currencies).

- **Core KPIs:**
  - Number of Restaurants based on **City** and **Country**.
  - Number of Restaurants opened by **Year**, **Quarter**, and **Month**.
  - Count of Restaurants based on **Average Ratings**.
  - Distribution of Restaurants based on **Average Price Buckets**.
  - Percentage of Restaurants with **Table Booking Available** (`Has_Table_booking`).
  - Percentage of Restaurants with **Online Delivery Available** (`Has_Online_delivery`).

- **Visual Analysis:**
  - Charts and insights based on:
    - **Cuisines**
    - **City**
    - **Ratings**
    - 

## 📋 Process Overview

- 📥 **Data Collection**: Used the provided Excel file containing restaurant data.
- 🏗️ **Data Modeling**:
  - Built a structured **Data Model** using all the sheets.
- 📅 **Calendar Table Creation**:
  - Generated a Calendar Table based on `Datekey_Opening`.
  - Added columns:
    - Year
    - Month Number
    - Month Full Name
    - Quarter (Q1–Q4)
    - Year-Month (YYYY-MMM)
    - Weekday Number
    - Weekday Name
    - Financial Month (April = FM1, ..., March = FM12)
    - Financial Quarter (FQ1–FQ4 based on Financial Year)
- 💱 **Currency Conversion**:
  - Converted "Average Cost for Two" from local currency to **USD**.
- 🌍 **Restaurant Analysis**:
  - Found the **number of restaurants** based on **City** and **Country**.
  - Analyzed **restaurant openings** by **Year**, **Quarter**, and **Month**.
- ⭐ **Ratings Analysis**:
  - Counted the number of restaurants based on **Average Ratings**.
- 💸 **Price Buckets**:
  - Created **buckets** based on Average Price ranges to categorize restaurants.
- 🍽️ **Booking and Delivery Analysis**:
  - Calculated % of restaurants offering **Table Booking**.
  - Calculated % of restaurants offering **Online Delivery**.
- 📊 **KPI and Chart Creation**:
  - Developed charts based on:
    - Cuisines
    - Cities
    - Ratings
- 🖥️ **Dashboard Development**:
  - Built an interactive **Dashboard** to visualize all KPIs.
- 🎯 **Additional Insights**:
  - Explored and added **new KPIs** beyond the provided ones for deeper analysis.
 

## Dashboard

![View Dashboard](https://github.com/madhu-malapur/assets/raw/main/zomatoss.png)




   

    










