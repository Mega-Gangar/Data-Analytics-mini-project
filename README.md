# Data-Analytics-mini-project
| Data Set | Collab Link 
|----------|----------|
|  [Link](https://www.kaggle.com/datasets/rohiteng/amazon-sales-dataset/data)| [Link](https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/analysis_ipynbz.ipynb)  | 
---
## Collab Overview:
### Import Libraries
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/modules.png">

---

### Load Dataset
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/load_csv.png">

---

### Dataset Overview
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/dataset_overview_1.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/dataset_overview_2.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/dataset_overview_3.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/dataset_overview_4.png">

---

### Filtering "Delivered" Order Status from the dataset
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Valid_Orders.png">

---

### KPI Analysis
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Orders.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Average_Sales.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Maximum_sales.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Minimum_sales.png">

---

### Sales Analysis
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_States.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_City.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_Country.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_Category.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/TotalSales_States_Category.png">

---

### Brand Performances
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_Brand.png">

---

### Quantity Analysis
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Quantity_Product.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Quantity_Product_Top_10.png">

---

### Expensive Product by Unit Price
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Expensive_UnitPrice.png">

---

### Payment Method Analysis
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Payment_Method_Count.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Payment_Method_Count_Delivered.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Cancelled_Payment_Orders.png">

---

### Seller Performance
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Top_Sellers_Sales.png">

---

### Top 5 Customers by Total Sales
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Top_5_Customer_Sales.png">

---

### Monthly Sales
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Monthly_Sales.png">

---

### Visualization

#### Bar Graph
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/bargraph.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/barh.png">

#### Pie Graph
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/piechart.png">

#### Line Graph
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/monthlytrends1.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/monthlytrends2.png">

#### Correlation Heat Map
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/corrgraph.png">

---

### #Performance Analysis of Linear Regression Model Using R² and RMSE
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Linear_Regression.png">

---

## Business Insights

**1. **Focus on High-Revenue States****
  - Increase inventory
  - Launch regional offers in low-performing States
  - For example: States like TX,CA,NC

**2. Boost High-Demand Products**
  - Maintain High-Demand Products stocks
  - Promote them on HomePage
  - For example: Products like LED Desk Lamp, Water Bottle Memory Card 128GB

**3. Optimize Payment Methods**
  - Promote most-used payment methods (like Credit Card, Debit Card)
  - Reduce friction in checkout so that payment methods like Cash on Delivery shifts to most-used payment methods
    
**4. Performance Analysis of Linear Regression Model Using R² and RMSE**
  - Independent Variable: Quantity, UnitPrice, Discount, Tax, ShippingCost
  - Dependent Variables: TotalAmount
  - Concludion:
    - 91% of the data, predicts TotalAmount quite accurately.
    - The average error is around 217 units.
