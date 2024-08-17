# AdventureWorks-Power-BI-Project

## Overview
This project involves the use of Microsoft Power BI to analyze sales data from the AdventureWorks OLTP database. The project focuses on creating an interactive dashboard using DirectQuery mode, allowing for real-time data analysis. The dashboard includes various measures, visualizations, and features like drill-downs, drill-throughs, and tooltips to provide insights into sales performance.

## Database

**AdventureWorks OLTP**

### Tables Used:
- `Sales.SalesOrderHeader`
- `Sales.SalesOrderDetail`
- `Sales.vSalesPerson` (view)
- `Sales.SalesTerritory`
- `Purchasing.ShipMethod`
- `Production.Product`
- `Production.ProductSubcategory`
- `Production.ProductCategory`

## Modeling

- **Conductivity Mode**: DirectQuery
- **Date Range**: 
  - Start Date: `7/1/2005`
  - End Date: `7/31/2008`
- **Date Table**: Created using DAX with the formula:
  ```DAX
  Dates = CALENDAR(01-01-2005, 31-12-2008)
