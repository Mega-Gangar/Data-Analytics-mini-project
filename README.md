# **Data-Analytics-mini-project( Amazon Sales Analysis using Python)**

## **Description**
This project performs Exploratory Data Analysis (EDA) on an Amazon Sales dataset using Python. The objective is to analyze sales performance, customer behavior, product trends, and regional sales to generate actionable business insights.The project uses Pandas, NumPy, Matplotlib, and Seaborn to clean, analyze, and visualize the data.

| Data Set | Collab Link 
|----------|----------|
|  [Link](https://www.kaggle.com/datasets/rohiteng/amazon-sales-dataset/data)| [Link](https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/analysis_ipynbz.ipynb)  | 

---

## **Objectives**
- Analyze overall sales performance
- Identify top-performing states and categories
- Discover the best-selling products
- Analyze customer purchasing behavior
- Study monthly sales trends
- Compare payment methods
- Generate business recommendations based on data
---

## **Dataset**
The dataset contains over 100,000 Amazon sales records with information including:
- Order Details
- Customer Information
- Product Information
- Category & Brand
- Quantity
- Unit Price
- Discount
- Tax
- Shipping Cost
- Total Amount
- Payment Method
- Order Status
- City, State and Country

---

## **Technologies Used**

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Collab
- Scikit-Learn

---

## **Business Insights**

**1. **Focus on High-Revenue States****
  - Increase inventory stocks
  - Launch regional offers in low-performing States
  - For example: States like _TX,CA,NC_

**2. Boost High-Demand Products**
  - Maintain High-Demand Products stocks
  - Promote them on HomePage
  - For example: Products like _LED Desk Lamp, Water Bottle Memory Card 128GB_

**3. Optimize Payment Methods**
  - Promote most-used payment methods _(like Credit Card, Debit Card)_
  - Reduce friction in checkout so that payment methods like _Cash on Delivery_ shifts to most-used payment methods
    
**4. Performance Analysis of Linear Regression Model Using R² and RMSE**
  - Independent Variable: _Quantity, UnitPrice, Discount, Tax, ShippingCost_
  - Dependent Variables: _TotalAmount_
  - Concludion:
    - 91% of the data, predicts TotalAmount quite accurately.
    - The average error is around 217 units.

---

## **Collab Overview:**
### **Import Libraries**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/modules.png">

---

### **Load Dataset**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/load_csv.png">

---

### **Dataset Overview**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/dataset_overview_1.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/dataset_overview_2.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/dataset_overview_3.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/dataset_overview_4.png">

---

### **Filtering "Delivered" Order Status from the dataset**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Valid_Orders.png">

---

### **KPI Analysis**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Orders.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Average_Sales.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Maximum_sales.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Minimun_Sales.png">

---

### **Sales Analysis**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_States.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_City.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_Country.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_Category.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/TotalSales_States_Category.png">

---

### **Brand Performances**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Sales_Brand.png">

---

### **Quantity Analysis**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Quantity_Product.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Total_Quantity_Product_Top_10.png">

---

### **Expensive Product by Unit Price**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Expensive_UnitPrice.png">

---

### **Payment Method Analysis**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Payment_Method_Count.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Payment_Method_Count_Delivered.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Cancelled_Payment_Orders.png">

---

### **Seller Performance**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Top_Sellers_Sales.png">

---

### **Top 5 Customers by Total Sales**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Top_5_Customer_Sales.png">

---

### **Monthly Sales**
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Monthly_Sales.png">

---

### **Visualization**

  - #### **Bar Graph**
This chart shows the total sales generated by each state. _TX_ and _CA_ contribute the highest sales, indicating strong market demand in these regions.

<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/bargraph.png">

---

This chart shows the total sales generated by each products. _T-Shirts_ and _External HDD 2TB_ contribute the highest sales, indicating strong market demand in the products.

<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/barh.png">

---

  - #### **Pie Graph**
This figures shows total sales generated by each category. _Electronics_, _Clothing_ and _Sports & Outdoors_ contribute the highest sales having _17%_ and _16.7%_ respectively

<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/piechart.png">

---

  - #### **Line Graph**
The monthly sales trend shows that August 2020 generated the highest sales in the dataset, with total sales of approximately 1,592,602.08.
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/monthlytrends1.png">
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/monthlytrends2.png">

---

  - #### **Correlation Heat Map**
This figure show that Tax, Unit Price, and Quantity are positively correlated with Total Sales, while Discount shows a weak negative correlation and Shipping Cost has minimal influence on sales.
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/corrgraph.png">

---

  - ### **Performance Analysis of Linear Regression Model Using R² and RMSE**
91% of the data, predicts TotalAmount quite accurately. The average error is around 217 units.
<img src="https://github.com/Mega-Gangar/Data-Analytics-mini-project/blob/main/previews/Linear_Regression.png">
