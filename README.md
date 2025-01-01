# Paginated-Report-in-Power-BI-Report-Builder

Creating a Dynamic Paginated Report in Power BI Report Builder for Superstore Data

Paginated reports in Power BI Report Builder are ideal for generating **pixel-perfect, print-ready documents**. 
I’ll walk you through a paginated report project built for the **Superstore dataset**, focusing on dynamic parameters that filter invoice values based on selected subcategories.

**Project Goal:**
1)Displays detailed invoice data.
2)Allows users to dynamically filter by categories.

![image](https://github.com/user-attachments/assets/7334955a-7722-48f5-b310-d0570c8d5c9d)

**Steps to Build the Report**

**1)Preparing the Data**
The Superstore dataset includes various columns such as ‘Category,’ ‘Product-Name,’ ‘Discount,’ ‘Quantity,’ Sales.
I ensured the dataset was clean and well-structured for reporting purposes.

**2)Setting Up Power BI Report Builder**
Open Power BI Report Builder and connect to the Superstore dataset via a shared dataset or SQL query.

**3)Creating the Report Layout**
Design the header to display the report title: “Superstore Invoice Report.”
Add a table or matrix to display fields such as Sub-Category, Order ID, and Invoice Value.
Include a footer with pagination and date/time stamps.

**4)Implementing Dynamic Parameters**

Go to the Parameters pane and create a parameter named Category.
Populate this parameter dynamically by linking it to the ‘Category’ field in the dataset.

**Key Features of the Report**

**Dynamic Filtering:** Users can select any category from the drop-down menu, and the report dynamically updates to show the relevant invoice data.
**Invoice Value Calculation:** The total invoice value for the selected category is highlighted, offering quick insights.
**Print-Ready Format:** The report’s paginated design ensures it looks professional when exported as a PDF or printed.

![image](https://github.com/user-attachments/assets/75d97c12-ee4f-4688-8c81-abf6cce927a6)

![image](https://github.com/user-attachments/assets/2172b9d8-942e-4dc2-b46e-d40cbc430a72)

![image](https://github.com/user-attachments/assets/56287fa6-7289-40e5-a6ad-50d3cdf9dc62)

