# **Hotel Booking Cancellation Analysis - Booking.com**

**Industry**: Hospitality / Travel & Tourism  
**Tools Used**: Python, Pandas, Seaborn, Matplotlib  
**Dataset**: Booking.com Hotel Booking Dataset (119,390 records, 32 columns)

---

### 🔍 **Project Overview**

This project analyzes **hotel booking** and **cancellation behavior** using historical data from **Booking.com**. The goal is to identify the key factors contributing to cancellations and provide data-driven recommendations to improve **hotel operations**, **increase bookings**, and **reduce cancellations**.

---

### 🎯 **Objective**

- **Analyze hotel booking and cancellation behavior** using historical data.
- Identify the key drivers of cancellations, including booking time, customer type, deposit type, and more.
- Recommend **strategies** for reducing cancellations and improving operational planning.

---

### 🗂 **Dataset Overview**

- **Source**: Booking.com
- **Records**: 119,390 bookings
- **Columns**: 32 (including key features like `lead_time`, `deposit_type`, `customer_type`, `is_canceled`, `adr`, etc.)
- **Time Period**: Data spans multiple years and various customer segments
- **Hotel Types**: City hotels and resort hotels

---

### 🛠 **Data Preprocessing**

1. **Missing Value Handling**:
   - Imputed or removed missing values in columns like `children`, `country`, `agent`.

2. **Outlier Treatment**:
   - Applied **IQR (Interquartile Range)** method to remove extreme values in `lead_time` and `adr` (Average Daily Rate).

3. **Feature Engineering**:
   - **Stay Duration**: Created a new feature by summing `weekend_nights` and `weekday_nights`.
   - **Family Booking**: Added a new feature `is_family_booking` based on the presence of children or babies.
   - **Booking Month & Season**: Extracted booking month and season from the `date` fields.

4. **Encoding & Transformation**:
   - Encoded categorical variables like `customer_type` and `deposit_type` using one-hot encoding.
   - Converted and processed date fields for time-based analysis.

---

### 💡 **Key Insights**

1. **Cancellation Trends**:
   - ~37% of bookings were canceled.
   - Cancellations were most frequent in **City Hotels** and for **No Deposit** bookings.
   - **Recommended Action**: Introduce **partial prepayment** options and offer **loyalty perks** to encourage confirmed bookings.

2. **Lead Time vs Cancellation**:
   - **Longer lead times** correlated with higher cancellation rates.
   - **Recommended Action**: Implement **flexible rebooking policies** and send **targeted reminders** to customers.

3. **Customer Type Behavior**:
   - **New and transient customers** had the highest cancellation rates.
   - **Recommended Action**: Focus on converting **returning customers** by offering **loyalty programs** or **verification incentives**.

4. **Booking Month Patterns**:
   - Highest cancellation rates were observed between **June and August**.
   - **Recommended Action**: Adjust for **seasonal pricing**, **staffing**, and offer **seasonal promotions** to maintain booking rates.

5. **Deposit Type Impact**:
   - **Prepaid (non-refundable)** bookings showed much lower cancellation rates.
   - **Recommended Action**: Promote **prepaid booking options** with incentives to secure higher booking retention.

---

### 📊 **Business Impact**

This analysis provides actionable insights for hotels and booking platforms to:
- Reduce booking cancellations by introducing strategic deposit policies and customer retention programs.
- Optimize operational planning by understanding seasonal trends and peak cancellation periods.
- Enhance marketing strategies to target high-value customers with personalized offers and loyalty programs.

---

### 🧠 **Use Cases**

1. **Hotel Operations Teams**:
   - Utilize insights to adjust booking policies, staffing levels, and seasonal promotions.
   
2. **Marketing Teams**:
   - Leverage customer segmentation to create targeted campaigns aimed at reducing churn and increasing customer retention.

3. **Revenue Management Teams**:
   - Use booking data to forecast cancellations and adjust pricing strategies for high-demand periods.

---

### 📂 **Repository Contents**

- **Data**: Raw and processed data files (including cleaned datasets).
- **Code**: Python scripts for data cleaning, feature engineering, analysis, and visualization.
- **Notebooks**: Jupyter Notebooks with detailed analysis steps and insights.
- **Visualizations**: Charts, plots, and graphs generated using **Seaborn** and **Matplotlib** for key insights.

---

### 📬 **Contact Information**

For any questions or feedback, feel free to reach out to me via GitHub or email: [chandrakanth.chethu@gmail.com](mailto:chandrakanth.chethu@gmail.com).

---
