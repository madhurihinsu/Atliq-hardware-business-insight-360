# Atliq-hardware-business-insight-360 #

**Project overview**

AtliQ Hardware has experienced significant growth in recent years and has now decided to adopt data analytics through Power BI for the first time. The goal is to gain a competitive edge in the market by enabling data-driven decision-making. This project aims to provide valuable insights to stakeholders across key business areas, including finance, sales, marketing, and supply chain operations.

**Tool used**  

SQL   
Power bi Desktop    
Excel    
Dax Language    
Dax studio (optimizing the report)    

**Key Considerations in Power BI Project:**

1) Project Scoping:-Identify all essential questions and business requirements that must be addressed before initiating the project.
2) Creating Calculated Columns: Generate new data fields in your dataset by using custom calculations.
3) Developing Measures with DAX: Build dynamic metrics and KPIs using the DAX (Data Analysis Expressions) language.
4) Designing Data Models: Structure relationships between tables to ensure efficient and accurate data analysis.
5) Using Bookmarks for Visual Switching: Implement bookmarks to toggle between different visual views within a report.
6) Navigating Pages with Buttons: Add interactive buttons to allow users to navigate between report pages seamlessly.
7) Handling Division Errors: Use the DIVIDE function to safely perform division operations and avoid errors from division by zero.
8) Creating a Date Table Using M Language: Develop a comprehensive date table in Power Query using M language for effective time-based analysis.
9) Dynamic Report Titles: Set report and visual titles that automatically adjust based on filters and slicers applied.
10) Using KPI Visuals:Incorporate KPI indicators to track performance against targets in a clear and visual format.
11) Applying Conditional Formatting: Enhance visual appeal and clarity by using icon sets or background colors to highlight values.
12) Data Validation: Ensure the accuracy and consistency of data through validation techniques during the data import and transformation process.
13) Understanding Power BI Service: Get familiar with the cloud-based Power BI Service for sharing and managing reports.
14) Publishing Reports to Power BI Service: Upload and distribute Power BI reports to the cloud for broader access and collaboration.
15) Collaboration & Access Control in Power BI Service: Manage user access, workspaces, and permissions to ensure secure and effective team collaboration.

**Term use in project**   

Retailer   
Ditributer    
Consumer   
Gross price    
Pre invoice deduction    
Post invoice deduction    
Net invoice sale    
Gross margin    
Net profit    
Cost of good sold    
YTD - Year to date    
YTG - year to go     

**Detail of dataset**

1)Dimension table : It will have the static data like details of customer and products.      
2)Fact table : It will have the data about the transactions.   

The dataset contains 11 tables in total, namely:  
• From gdb041 MySQL Server:  
o dim_customer: 209 records | 5 columns    
o dim_market: 27 records | 3 columns   
o dim_product: 397 records | 6 columns    
o fact_forecast_monthly: 1,885,941 records | 4 columns    
o fact_sales_monthly: 1,885,941 records | 4 columns     
• From gdb041 MySQL Server:    
o freight_cost: 135 records | 4 columns     
o manufacturing_cost: 1,197 records | 3 columns    
o post_invoice_deductions: 2,063,076 records | 5 columns    
• Excel Files:    
o market_share: 737 records | 6 columns   
o operational_expense: 113 records | 4 columns   
o ns_gm_target: 321 records | 5 columns     

**Data Modelling**

![image](https://github.com/user-attachments/assets/e06479da-1e60-48e4-b6a6-ac018927eb2d)


**Dashbord designing**

The visuals will be developed in alignment with the mock-ups, and any required measures will be created during the workflow.   

****Home view****

![Screenshot 2025-05-21 211246](https://github.com/user-attachments/assets/7cb1dd27-657d-40d5-bb90-5419081c36f5)



****Finance view****
![Screenshot 2025-05-21 211310](https://github.com/user-attachments/assets/728de4f2-8449-44f0-9945-392ba02f8835)



****sales view****

![Screenshot 2025-05-21 211328](https://github.com/user-attachments/assets/33f5f830-d44e-49c0-8852-a8d5a1729299)


****Marketing view****

![Screenshot 2025-05-21 211353](https://github.com/user-attachments/assets/53d65e21-efac-4aaf-9d0f-4fa3afd18847)  


****Supply chain view****

![Screenshot 2025-05-21 211416](https://github.com/user-attachments/assets/25250321-9d48-4470-a960-2847b93b737f)



****excutive view****
![Screenshot 2025-05-21 211416](https://github.com/user-attachments/assets/0c0036cc-bc92-46b8-9520-375db17ce386)


To view full report 
https://app.powerbi.com/view?r=eyJrIjoiZmM4N2U1NTAtYmYzNC00MGI4LTg3ZWMtZGUwNGJjMzA4OWUxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9












