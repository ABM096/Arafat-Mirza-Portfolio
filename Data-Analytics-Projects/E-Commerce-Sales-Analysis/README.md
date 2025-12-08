# E-Commerce Sales & Customer Insights Dashboard (Power BI)

This project is something I built to practice working with a realistic dataset and to improve my skills in Power BI, data modeling, and interpreting business trends. The dataset comes from the Brazilian E-Commerce Public Dataset (Olist), which includes over 100,000 orders. I chose this dataset because it covers many areas of an online business—sales, customers, logistics, and reviews—so it gave me a chance to analyze different parts of the customer experience.

---

## Why I Built This Project

Coming from a Business Analytics background, I wanted to take on a project that goes beyond simple charts and actually tries to answer business questions. My goal wasn’t just to visualize data, but to understand:

- How sales change over time  
- Which product categories drive most of the revenue  
- How delivery performance affects customer satisfaction  
- Which regions contribute the most to sales  
- Where operations slow down, especially around shipping  

This project helped me understand how different factors in e-commerce connect with each other.

---

## Dataset Overview

The dataset includes multiple CSV files such as:

- Orders  
- Order items  
- Customers  
- Payments  
- Reviews  
- Sellers  
- Products  

Since the data is spread across different tables, I connected them using a star-schema model in Power BI. This was a good exercise in understanding relationships and building a structured model.

---

## Tools I Used

- **Power BI** for modeling and dashboards  
- **Power Query** for cleaning the data  
- **DAX** for calculations  
- **Excel** for quick checks  
- **GitHub** for version control and documentation  

---

## What I Modeled in Power BI

I created relationships between the orders, customers, sellers, products, payments, and review tables. This allowed me to calculate metrics such as:

- Total Sales  
- Total Orders  
- Average Order Value  
- Total Customers  
- Late Delivery %  
- Average Review Score  

I also created a few calculated columns to help with the analysis, such as:

- Shipping time in days  
- Delivery delay in days  
- Total order value  

---

## What I Focused on in the Dashboard

### **Sales Performance**
- Monthly sales patterns  
- Top revenue-generating product categories  
- Changes in average order value  

### **Customer Insights**
- Where customers are located  
- Which regions spend the most  
- Customer review behavior  

### **Operational Metrics**
- How long deliveries actually take  
- How often deliveries arrive late  
- How delays affect customer satisfaction  

---

## Key Takeaways

Here are a few things that stood out to me while working on this dataset:

1. **Delivery delays clearly impact review scores.**  
   Customers who receive their orders late tend to give lower ratings.

2. **A handful of product categories drive most of the total revenue.**  
   This is useful for choosing where to focus marketing efforts.

3. **Some states consistently experience longer shipping times.**  
   This could be an opportunity for logistics improvements.

4. **Major cities generate a large portion of sales.**  
   These areas could be targeted for promotions or localized campaigns.

---

## What I Would Recommend (If I Were Presenting This Internally)

- Focus on improving delivery times in specific regions  
- Monitor product categories with consistent demand  
- Review seller performance, especially those with lower ratings  
- Build customer segments to personalize marketing or offers  

---

## Files Included in This Project

- Power BI file (`E-Commerce-Dashboard.pbix`)  
- Dataset CSVs  
- Dashboard screenshots  
- Supporting documentation  

---

## A Little About the Project

This was one of the first large datasets I worked with seriously, and it helped me gain confidence in building dashboards that tell a clear story. It also helped me understand how analysts connect numbers to practical business decisions.

I plan to continue improving this project as I learn more, but this version represents where I currently am in my analytics journey.
