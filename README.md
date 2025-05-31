# Marketing_Insights
Marketing Insights for E-commerce Company

To get marketing insights from the data to define marketing strategies going forward. Also, expecting to build an analytical dashboard to monitor various KPI’s & business metrics.

**Available Data:**
Transaction data has been provided for the period of 1st Jan 2019 to 31st Dec 2019. The below data
sets have been provided.
**Online_Sales.csv:** This file contains actual orders data (point of Sales data) at transaction level with
below variables.
    CustomerID: Customer unique ID
    Transaction_ID: Transaction Unique ID
    Transaction_Date: Date of Transaction
    Product_SKU: SKU ID – Unique Id for product
    Product_Description: Product Description
    Product_Cateogry: Product Category
    Quantity: Number of items ordered
    Avg_Price: Price per one quantity
    Delivery_Charges: Charges for delivery
    Coupon_Status: Any discount coupon applied
**Customers_Data.csv:** This file contains customer’s demographics.
CustomerID: Customer Unique ID
    Gender: Gender of customer
    Location: Location of Customer
    Tenure_Months: Tenure in Months
**Discount_Coupon.csv:** Discount coupons have been given for different categories in different
months
    Month: Discount coupon applied in that month
    Product_Category: Product category
    Coupon_Code: Coupon Code for given Category and given month
    Discount_pct: Discount Percentage for given coupon
**Marketing_Spend.csv:** Marketing spend on both offline & online channels on day wise.
    Date: Date
    Offline_Spend: Marketing spend on offline channels like TV, Radio, NewsPapers, Hordings etc…
    Online_Spend: Marketing spend on online channels like Google keywords, facebook etc..
**Tax_Amount.csv:** GST Details for given category
    Product_Category: Product Category
    GST: Percentage of GST

**Objective:**
1. Calculate Invoice amount or sale_amount or revenue for each transaction and item level
    Invoice Value =(( Quantity*Avg_price)*(1-Dicount_pct)*(1+GST))+Delivery_Charges
2. Perform Detailed exploratory analysis
3. Performing Customer Segmentation
4. Predicting Customer Lifetime Value (Low Value/Medium Value/High Value)
5. Cross-Selling (Which products are selling together)
6. Predicting Next Purchase Day(How soon each customer can visit the store (0-30 days, 30-60
days, 60-90 days, 90+ days)
7. Perform cohort analysis by defining below cohorts
