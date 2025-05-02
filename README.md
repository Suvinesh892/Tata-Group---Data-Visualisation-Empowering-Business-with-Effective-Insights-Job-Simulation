# Tata Group-Data Visualisation Empowering Business with Effective Insights-Job Simulation 

## **Why I Did It !**

As part of the Tata Group's job simulation on data visualization, I developed an interactive dashboard that empowers businesses with actionable insights. The project focused on transforming complex datasets into intuitive visuals, helping decision-makers identify customer trends and optimize strategies for revenue growth.

## *Quick Access to Sections*

🔗[Line Chart for Revenue](#Line-Chart-for-Revenue-by-Year-2011)      
🔗[Country Wise Performance By Sales](#Country-Wise-Performance-By-Sales)     
🔗[Top 10 Countries By Revenue & Quantity](#Top-10-Countries-By-Revenue-&-Quantity-(Excluding-UK))        
🔗[Product-wise Sales Revenue vs Quantity Analysis](#Product-wise-Sales-Revenue-vs-Quantity-Analysis)       
🔗[Product Performance Analysis](#Product-Performance-Analysis)     
🔗[Sales Trend Analysis](#Sales-Trend-Analysis-(2011))      

## *Business Impact & Questions*
[🔗Question Interest to CEO & CMO](#Question-Interest-to-CEO-&-CMO)       
[🔗Key Analytical Questions & Visual Findings](#❓Key-Analytical-Questions-&-Visual-Findings❓)       
[🔗Business Impact & Key Takeaways](#Business-Impact-&-Key-Takeaways)     
[📌Understanding Customer Loyalty](##🧷1.-Understanding-Customer-Loyalty-&-Repeat-Purchases)        
[📌Revenue from Returning Customers](##🧷2.-Revenue-from-Returning-Customers-–-A-Key-Driver-of-Business-Success)        
[📌Evaluating Product Performance](##🧷3.-Evaluating-Product-Performance-–-What’s-Selling-&-What’s-Struggling)      
[📌Market Trends](##🧷4.-Market-Trends-–-How-Three-Key-Countries-Performed)     
🔗[The Bigger Picture – Why This Matters⁉️](##🧷The-Bigger-Picture-–-Why-This-Matters)


## **Skills Applied In This Simulation**

**DAX Calculations    
RFM Segmentation** - (Classified customers based on Recency, Frequency, and Monetary value to identify high-value segments).  
**Pareto Analysis (80/20 Rule)**    
**Data Storytelling & Executive-Level Reporting**   
**strategic recommendations**

### **Tool**
**Microsoft Power Bi** 

## **Methodology & Approach**

- **Data Cleaning**: Removed duplicates, handled missing values in using Power querys       
![Image](https://github.com/user-attachments/assets/2df36816-ea7d-47ad-9be3-7957725c5229)

- **Segmentation:**         
    **(1) Repeat Customer Analysis** – Segmented first-time vs. repeat buyers to measure engagement and understand loyalty patterns.    
    **(2) Customer Purchasing Behavior** – Classified customers based on their **order frequency, preferred products, and revenue contribution** to uncover trends.     
    **(3) Revenue-Based Segmentation** – Determined the impact of repeat buyers on total revenue compared to first-time customers       
    **(4) Alternative Customer Segmentation** (Without Calculated Columns) – Explored ways to categorize customers dynamically within Power BI for flexible analysis.

- **Visualization**: Built interactive charts for executive reporting.      
        -Bar charts     
        -Clustered Column Chart     
        -Line charts    
        -Pie charts     
        -Tables     
        -scatter Chart





# Report Analysis   

# **Line Chart for Revenue by Year 2011**     

![Image](https://github.com/user-attachments/assets/8bda0585-677f-40a0-a4ae-f2539de58c7c)

#### Revenue Trends (2011) – Line Chart Analysis
🗒️Lowest Revenue: February recorded the lowest revenue at **523,631K**, indicating a seasonal dip in sales.     
🗒️ Peak Revenue: November saw the highest revenue at **1,509,496M**, highlighting a strong sales period—possibly due to holiday or promotional activities.      
🗒️Sharp Decline: Following the peak, revenue dropped significantly to **638,792K** in December, suggesting post-peak season slowdown or end-of-year sales adjustments.      
🗒️ Overall Trend: The visualization helped identify seasonal performance shifts, guiding business strategies for revenue optimization.


# **Country Wise Performance By Sales**

![Image](https://github.com/user-attachments/assets/15e9b820-09d6-4b61-b20d-fab2f37910b0)

I analyzed country-wise sales performance using multiple visualizations to uncover global sales insights. **Excluding the UK**, I created a bar chart showcasing the top 5 countries by unit sales, where the **Netherlands ranked first with 200,937K units** sold, highlighting its strong market presence. On the other end, another bar chart represented the bottom 5 countries, with **Saudi Arabia** recording the lowest sales, at just **80 units sold**.

To provide a broader perspective, I built a total sales revenue by country chart, helping visualize how revenue varied across different regions. Additionally, I implemented a **map chart**, where **bubble sizes** dynamically represented **unit sales per country**, offering a geographic overview of sales distribution. These insights helped identify high-performing markets, regions with growth potential, and areas requiring strategic intervention to optimize business decisions.




# **Top 10 Countries By Revenue & Quantity (Excluding UK)**

![Image](https://github.com/user-attachments/assets/dc78851c-d37d-4461-a9e6-fac13e55c38e)

In this analysis, I examined the Top 10 Countries by Revenue & Quantity **(Excluding UK)** to highlight global sales performance. The Netherlands ranked first, generating **285K** in revenue and **200,937 units sold**, showcasing strong market dominance.

The visualization provided a clear comparison of revenue and quantity across multiple countries, helping identify high-performing markets and potential areas for strategic focus. By excluding the UK, the analysis emphasized other regions contributing significantly to overall sales, offering valuable insights into geographic sales distribution.


#  **Product-wise Sales Revenue vs Quantity Analysis**

 I examined **product sales trends** using various Power BI visualizations to uncover key insights into revenue contribution and stock performance.

 ![Image](https://github.com/user-attachments/assets/b391b2f3-b3f4-4e3c-a6d4-2fe1d4b77de0)  

### 🧷 **Bar Chart – Revenue by Customer ID**  
I created a **bar chart displaying revenue by Customer ID**, focusing on the **top 10 customers**, while excluding blank customer information.  
- *Customer ID "14646" generated approximately 280K in revenue, highlighting their strong purchasing power.*  
- This visualization helped identify **high-value customers** contributing significantly to total revenue.  

### 🧷 **Scatter Chart – Quantity vs Sales Revenue**  
To explore stock performance, I developed a **scatter chart comparing total quantity sold vs. revenue**, which exposed the **highest revenue-generating stock** relative to unit sales.  
- *StockCode "23843" had the highest revenue at 168K, despite selling only 80,995 units.*  
- This analysis helped determine which products drive revenue **effectively, even with lower unit sales**.  

### 🧷 **Table – Highest Selling StockCodes**  
For a structured breakdown, I incorporated a **table listing stock codes with total quantity sold and sales revenue**, enabling detailed insights.  
- This helped pinpoint **high-demand products** that play a key role in overall business performance. ASC & DECS 



# **Product Performance Analysis**

I identified the **Top 10 Products by Sales Revenue** and **Bottom 10 Products by Sales Revenue** to assess performance variations. To improve readability, I applied conditional formatting with a **color gradient**, visually distinguishing high and low revenue values for quick interpretation.

![Image](https://github.com/user-attachments/assets/da0ec243-94c1-4cab-924d-fa9951a2cc03)

### **RFM Segmentation in Power BI**
I utilized DAX to segment customers based on Recency, Frequency, and Monetary (RFM) scores to enhance data-driven decision-making.

#### DAX Calculation

    RecencyScore = 
    RANKX(ALLSELECTED('Online Retail'[CustomerID]), [Recency], , ASC, DENSE)             
   
   
    FrequencyScore = 
    RANKX(ALLSELECTED('Online Retail'[CustomerID]), [Frequency], , DESC, DENSE)     

    
    MonetaryScore = 
    RANKX(ALLSELECTED('Online Retail'[CustomerID]), [Monetary], , DESC, DENSE)  

#### Customer segmentation DAX      

    CustomerSegment =
    SWITCH(TRUE(),
    [RecencyScore] <= 20 && [FrequencyScore] >= 80 && [MonetaryScore] >= 80, "1 - Best Customer",
    [RecencyScore] <= 50 && [FrequencyScore] >= 60 && [MonetaryScore] >= 60, "2 - Big Spender",
    [RecencyScore] <= 80 && [FrequencyScore] >= 40 && [MonetaryScore] >= 40, "3 - Loyal Customer",
    [RecencyScore] >= 80 && [FrequencyScore] <= 20 && [MonetaryScore] <= 20, "4 - Lost Cheap Customer",
    [RecencyScore] >= 60 && [FrequencyScore] <= 40 && [MonetaryScore] <= 40, "5 - Occasional Buyer",
    [RecencyScore] <= 40 && [FrequencyScore] >= 50 && [MonetaryScore] >= 50, "6 - Lookout Buyer",
    [RecencyScore] <= 30 && [FrequencyScore] >= 70 && [MonetaryScore] >= 70, "7 - Potential Best Customer",
    "8 - Regular Customer"
    )



Customer Segments
- Best Customer  – Frequent, high-spending, and recent buyers.
- Big Spender  – High spenders with fewer transactions.
- Loyal Customer  – Frequent purchasers with moderate spending.
- Lost Cheap Customer  – Previously engaged but low-spending customers.
- Occasional Buyer  – Infrequent shoppers with moderate purchases.
- Lookout Buyer  – Moderate spenders with potential for retention.
- Potential Best Customer  – Strong candidates for loyalty programs.
- Regular Customer  – Consistent but moderate buyers.



# **Sales Trend Analysis (2011)**
I analyzed sales trends across **EIRE, Netherlands, and Germany** using line charts to capture performance variations across three key metrics:

![Image](https://github.com/user-attachments/assets/b5131ccc-0be1-4613-9a5b-dd9a204fee69)

- Quantity by Month & Country – Tracking the number of units sold from January to December.
- Sales Revenue by Month & Country – Analyzing financial performance across the three regions.
- Count of Invoices by Month & Country – Measuring transactional volume to assess market activity.

By limiting the scope to EIRE, Netherlands, and Germany, the analysis focused on how these markets performed throughout 2011, identifying trends in seasonal demand, revenue shifts, and customer purchasing behavior.

#### Key Insights
- **Peak Sales Periods** – Notable increases in quantity sold and revenue during specific months.
- **Country-Specific Variations** – Differences in market performance across regions, highlighting competitive positioning.
- **Invoice Trends & Customer Activity** – Correlation between high transaction counts and stronger revenue flow.

This analysis enables data-driven decision-making, helping optimize sales strategies, inventory management, and targeted marketing efforts for the three countries.


# **Question Interest to CEO & CMO**

***What is the percentage of customers who are repeating their orders? Are they ordering the same products or different?***

![Image](https://github.com/user-attachments/assets/b1ec768e-112f-494f-a54b-c3b413be26c1)

#### **Repeat Purchase Analysis**
I analyzed customer order behavior to determine the percentage of repeat customers and whether they repurchase the same products or different ones.
Key Insights from the Visuals

- Pie Chart: Represents the Top 10 Unique Products by Customer to highlight repeat purchases.- **Customer ID "14911"** stands out, having **17.07%** of purchases attributed to unique products repeatedly.
- Other customers demonstrate diverse purchasing behavior across different items.

- Card Visualization: Displays the total count of repeat customers, **amounting to 398K**, which corresponds to **43.4% of** the overall customer base.

#### **Business Impact**
This analysis helps:
- Identify loyal customers who repeatedly purchase unique products.
- Understand repeat purchase behavior—whether customers prefer the same items or explore different products.
- Optimize retention strategies by targeting customers who show high engagement through repeated orders.

This structured approach provides valuable customer insights to refine marketing, inventory, and personalized engagement strategies.

***What revenue is being generated from the customers who have ordered more than once?***

#### **Revenue from Repeat Customers**
I analyzed the revenue generated from customers who have placed more than one order to assess their contribution to total sales.

![Image](https://github.com/user-attachments/assets/4a81cf1f-c613-42c2-9f8c-a7811762ea66)

#### Visualizations Used
- Table Format: Displays columns for **Customer, Total Revenue, and Revenue from Repeat Customers**, allowing direct comparisons between individual spending patterns.
- Card Visualization: Represents the total revenue from customers who ordered more than once, amounting to **10.57 million**, emphasizing their significant role in overall business performance.
- Pie Chart: Highlights the Top 10 Repeat Customers and their Revenue, providing insights into the highest-value returning customers.
- Tooltip Feature: Shows which customer segment each top repeat customer belongs to, linking them to the **RFM segmentation** to better understand their purchasing behavior.


#### **Key Business Takeaways**
- **High Contribution from Repeat Customers**: A substantial portion of revenue comes from returning buyers, reinforcing their importance in retention strategies.
- **Segment-Based Insights**: Identifying customer behavior trends helps tailor engagement tactics for different groups.
- **Optimizing Sales Strategies**: Understanding repeat purchase habits supports inventory planning and targeted promotional efforts.


# **❓Key Analytical Questions & Visual Findings❓**

#### For the CEO (Business Strategy & Revenue)      
-    Which products generate the most revenue? (Stock code  & Quantity)✅
-    Which country has the highest sales volume? (Country & Total Sales)✅
-    What percentage of customers are repeat buyers? (Customer ID & Purchase Frequency)✅
-    Are there seasonal trends affecting revenue growth? (Invoice Date & Sales Patterns)✅  
- Which region is generating the highest revenue, and which region is generating the lowest?✅
- What is the monthly trend of revenue, which months have faced the biggest increase/decrease?✅
- Which months generated the most revenue? Is there a seasonality in sales?✅
- Who are the top customers and how much do they contribute to the total revenue? Is the business dependent on these customers or is the customer base diversified?✅


#### For the CMO (Marketing & Customer Behavior)
-   Which customer segment spends the most? (Customer ID & Purchase Trends)✅  
-   Which products are frequently purchased together? (Stock code & Invoice No)✅
-   Does pricing impact purchase frequency? (Unit Price vs. Quantity Bought)✅
-   Which country shows the highest demand for our products? (Country & Purchase Behavior)✅
-  What is the percentage of customers who are repeating their orders? Are they ordering the same products or different?✅
- For the repeat customers, how long does it take for them to place the next order after being delivered the previous one?✅
- What revenue is being generated from the customers who have ordered more than once?✅
- Who are the customers that have repeated the most? How much are they contributing to revenue?✅


# **✔️Business Impact & Key Takeaways✔️**



### **How This Analysis Strengthens Business Performance**

Data-driven decisions can make a huge impact, and this analysis provides **clear insights into customer behavior, sales trends, and revenue opportunities** that will directly improve business strategies.

---

## 🧷**1. Understanding Customer Loyalty & Repeat Purchases**
- **43.4% of customers (398K) have placed more than one order**, proving a strong customer retention rate.
- Customer **14911** is a standout, **purchasing unique products repeatedly at a rate of 17.07%**.
- Repeat purchases are a **clear sign of trust and satisfaction**, and knowing what customers reorder helps shape inventory decisions and personalized recommendations.

 **Business Value**: By **identifying loyal customers and their purchasing habits**, companies can focus on nurturing relationships with them through loyalty programs, personalized discounts, and targeted marketing.

---

## 🧷**2. Revenue from Returning Customers – A Key Driver of Business Success**
- The total revenue **from customers who have placed more than one order is 10.57 million**, showing **returning buyers significantly contribute to overall sales**.
- A **pie chart showcases the top 10 repeat customers**, visually highlighting who drives the most revenue.
- A **tooltip feature identifies which customer segment each repeat buyer belongs to**, connecting their behavior to segmentation strategies.

 **Business Value**: Recognizing **repeat customers as a high-value group** enables smarter retention efforts—keeping them engaged with exclusive benefits or tailored offerings can boost revenue further.

---

## 🧷**3. Evaluating Product Performance – What’s Selling & What’s Struggling**
- By ranking the **Top 10 and Bottom 10 products by revenue**, it’s easy to **pinpoint the strongest sellers** and spot **underperforming items** that may need adjustments.
- **Color gradient formatting** highlights revenue levels clearly, allowing leadership to quickly assess trends and take action.

 **Business Value**: **Best-selling products can be promoted aggressively**, while underperforming products may need price adjustments, marketing refreshes, or discontinuation to optimize profitability.

---

## 🧷**4. Market Trends – How Three Key Countries Performed**
- Sales trends in **EIRE, Netherlands, and Germany** were analyzed from **January to December 2011** to see how they fluctuated throughout the year.
- **Line charts visualized quantity sold, revenue, and invoice count by month and country**, revealing **seasonal trends and market variations**.
 **Business Value**: Understanding **which months drive peak sales and which markets perform best** allows businesses to **adjust inventory, promotions, and regional sales strategies** effectively.

---

## 🧷**The Bigger Picture – Why This Matters**
These findings help businesses make **data-backed decisions** instead of relying on assumptions.

✔ **Boosting retention** – Engage repeat buyers with tailored promotions.      
✔ **Revenue optimization** – Focus efforts on high-performing products & loyal customers.      
✔ **Better forecasting** – Understand peak periods and adjust supply chain accordingly.        
✔ **Targeted marketing** – Different strategies for different customer groups based on buying habits.

# 🔗Connect with Me

📄[Get Resume]()  

ℹ️[LinkedIn](hhttps://www.linkedin.com/in/suvinesh5)          
    
📧[email](msuvinesh7@gmail.com)     

☎️[+91 8940 579892]()
