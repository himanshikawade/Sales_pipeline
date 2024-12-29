** Power BI Dashboard - Sales Pipeline Overview** 📊✨  

---

### **Project Overview** 🚀  
This Power BI dashboard provides a comprehensive overview of sales performance and pipeline metrics. The goal was to present actionable insights through well-structured KPIs and visuals, ensuring clarity and professionalism.  

---

### **Key Features of the Dashboard** 🛠️  
1. **KPIs (Key Performance Indicators):**  
   - **Total Revenue:** Displays the total revenue generated from closed-won deals.  
   - **Total Monthly Recurring Revenue (MRR):** Shows the total recurring revenue generated monthly.  
   - **Average Contract Duration:** Highlights the average duration of contracts in months.  
   - **Number of Deals Closed:** Counts the total deals that were either won or lost.  

2. **Visualizations:**  
   - **Bar Chart:** Revenue distribution by deal stage to track pipeline efficiency.  
   - **Line Charts:**  
     - Monthly revenue trend to observe performance over time.  
     - Active deals trend for deal momentum analysis.  
   - **Pie Charts:**  
     - Distribution of closed-lost reasons to identify areas of improvement.  
     - Proportion of deals by stage to understand pipeline distribution.  
   - **Table:** Top 5 high-value deals by Total Contract Value (TCV).  
   - **Scatter Plot:** Analysis of contract duration versus revenue for trend insights.  

---

### **How KPIs Were Calculated** 🧮  
- **Total Revenue:** Summed up the `amount` field filtered for `closedwon` deals.  
- **Total MRR:** Aggregated the `hs_mrr` field across all records.  
- **Average Contract Duration:** Used the average of the `Contract Duration` field.  
- **Number of Deals Closed:** Counted `dealstage` values filtered for `closedwon` and `closedlost`.  

---

### **Dataset Used** 📁  
The dataset includes key fields like:  
- `amount`: Revenue generated.  
- `dealstage`: Deal progression stages.  
- `hs_mrr`: Monthly recurring revenue.  
- `createddate`: Deal creation date.  
- `closedate`: Deal closure date (handled missing values appropriately).  

---

### **How to Use the Dashboard** 🖱️  
1. Open the attached `.pbix` file in Power BI Desktop.  
2. Navigate through the visuals to explore insights.  
3. Use filters to customize views and focus on specific aspects of the sales pipeline.  

---

### **Why This Dashboard Matters** 🌟  
This dashboard empowers decision-makers to:  
- Monitor key sales metrics at a glance.  
- Identify strengths and weaknesses in the sales pipeline.  
- Make data-driven decisions to optimize performance.  

---  

Thank you for reviewing my project! Feel free to reach out if you have any questions. 😊  

---  
