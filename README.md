# 📊 Helpdesk Performance Analytics Dashboard  

## 📌 Overview  
This project analyzes **customer support tickets** to measure efficiency, resolution rates, and escalation trends.  
The dataset was cleaned using **Python**, exploratory data analysis (EDA) was performed, and a **Power BI dashboard** was created for visualization.  

---

## 📂 Data Processing  

✔ **Data Cleaning (Python - Pandas, NumPy):**  
   - Removed duplicates & null values  
   - Standardized ticket status, priority, and dates  
   - Converted date formats for analysis  

✔ **Exploratory Data Analysis (EDA):**  
   - Identified ticket trends, resolution times, and escalation rates  
   - Analyzed ticket distribution by type, priority, and status  

---

## 📊 Power BI Dashboard  

🔹 **KPIs & Metrics:**  
   - **Total Tickets:** 8,469  
   - **Resolved Tickets:** 2,769  
   - **Escalation Rate:** 49.76%  
   - **Resolution Rate:** 32.70%  
   - **Customer Satisfaction Score:** 3  

🔹 **Visuals Used:**  
   - **KPI Cards** → Show key metrics like total tickets, escalation rate, resolution rate  
   - **Doughnut Chart** → Ticket status breakdown (Pending, Open, Closed)  
   - **Gauge Chart** → Unresolved Tickets progress  
   - **Bar Chart** → Resolved tickets by ticket type  
   - **Line Chart** → Ticket trends over time  
   - **Column Chart** → Avg unresolved tickets per month  

---

## 📌 Key Insights  

📌 **High Escalation Rate (49.76%)** → Indicates a large number of tickets requiring manager intervention.  
📌 **Low Resolution Rate (32.70%)** → Suggests inefficiencies in customer issue resolution.  
📌 **Ticket Trends** → Ticket volume is **decreasing over time**, possibly due to improved self-service options.  
📌 **Unresolved Tickets** → Majority of unresolved tickets fall under **Pending Customer Response** status.  

---

## 📦 Tech Stack  

✔ **Python** → Data cleaning & preprocessing  
✔ **Power BI** → Dashboard creation  
✔ **Pandas & NumPy** → Data manipulation  
✔ **Matplotlib & Seaborn** → Exploratory analysis  

---

## 📂 Repository Structure  

│-- 📜 Customer_Tickets_Cleaning.ipynb -> Python script for data preprocessing and Analysis <br>
│-- 📜 Helpdesk-Performance-Dashboard.pbix -> Power BI Dashboard <br>
│-- 📜 README.md -> Project Documentation <br> 
│-- 📂 data  <br>
│ ├── Customer_support_ticket_Dataset.zip -> Raw dataset <br>
│ ├── Cleaned_Customer_Support_Tickets.csv -> Processed dataset <br>
│-- 📂 images <br>
│ ├── Dashboard.png -> Power BI Dashboard Screenshot <br>
![Dashboard](https://github.com/user-attachments/assets/ca2c5059-f2c4-4812-ae3b-11c89d796565) <br>
