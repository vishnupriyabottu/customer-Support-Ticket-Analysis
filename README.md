# customer-Support-Ticket-Analysis
An end-to-end Power BI project analyzing customer support ticket data to track resolution efficiency, agent performance, customer satisfaction, and SLA compliance through interactive dashboards.
##  Objectives
- Track total tickets and resolution performance
- Analyze tickets by priority, channel, and issue type
- Evaluate agent performance using KPIs
- Measure customer satisfaction and SLA compliance
- Identify trends and improvement areas

---

## Tools & Technologies
- Power BI
- Power Query
- DAX
- CSV Dataset

---

## 📁 Dataset Information
**Source:** Kaggle (Customer Support / CRM-style dataset)  
**Format:** CSV  

### Key Columns:
- Ticket_ID  
- Created_Date  
- Resolution_Date  
- Priority_Level (Low, Medium, High, Critical)  
- Ticket_Channel (Chat, Email, Web Form)  
- Issue_Category  
- Assigned_Agent  
- Resolution_Time (Hours)  
- Satisfaction_Score  

---

##  Dashboards Included

### 1️⃣ Executive Overview
- Total Tickets
- Average Resolution Time
- Average Customer Satisfaction
- % Tickets Resolved
- Tickets by Priority
- Tickets by Channel
- Monthly Ticket Trends

### 2️⃣ Agent Performance Analysis
- Tickets Handled by Agent
- Average Resolution Time by Agent
- Average Satisfaction Score by Agent
- Agent-wise Performance Table

### 3️⃣ Customer Experience & SLA Analysis
- Satisfaction by Priority
- Resolution Time by Channel
- Resolution Time vs Satisfaction
- High vs Low Satisfaction Tickets by Issue Type

---

##  Key Insights
- High priority tickets have lower satisfaction due to longer resolution times
- Chat channel resolves tickets faster than Email and Web Form
- Balanced workload among agents with minor performance variation
- Technical issues generate the highest number of tickets

---

## 📂 Project Structure

📁 customer-support-ticket-analysis-powerbi
│
├── 📁 Dataset
│ └── customer_support_tickets.csv
│
├── 📁 Dashboard
│ └── Customer_Support_Ticket_Analysis.pbix
