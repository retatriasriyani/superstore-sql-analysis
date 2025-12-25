# Customer Transaction Analysis (SQL Portfolio)

## Project Overview
This project analyzes customer purchasing behavior using SQL to uncover insights related to revenue, customer value, subscription impact, discount effectiveness, and potential churn risk.

The dataset represents customer-level transaction summaries, not order-level data.

## Objectives
- Understand overall customer and revenue distribution
- Identify top-performing product categories and seasonal trends
- Segment customers based on value and purchase behavior
- Evaluate the effectiveness of subscription and discount strategies
- Detect high-value customers with potential satisfaction risks

## Dataset Description
**Table:** customer_transactions_final  
Each row represents a customer record with attributes such as:
- Demographics (age, gender, age_group)
- Purchase behavior (purchase_amount, previous_purchases, frequency_of_purchases_days)
- Product attributes (category, season)
- Business factors (subscription_status, discount_applied, review_rating)

⚠️ Since the dataset is customer-level, transaction frequency is analyzed using behavioral proxies instead of raw order counts.

## 🛠 Tools
- SQL (CTE, Window Function, Aggregation)
- SQLite / PostgreSQL
- GitHub

---

## 📊 Key Analysis & Insights

### 1️⃣ Overall Customer & Revenue Overview
**Insight:**  
The dataset represents a moderate customer base with consistent average purchase values.

**Business implication:**  
Revenue growth is likely driven by increasing purchase frequency rather than increasing transaction size.

---

### 2️⃣ Top Product Categories by Revenue
**Insight:**  
A small number of product categories contribute the majority of total revenue.

**Business implication:**  
Focusing inventory and promotion on top categories can improve profitability.

---

### 3️⃣ Best-Selling Category by Season
**Insight:**  
Customer preferences vary across seasons, with different categories dominating sales.

**Business implication:**  
Seasonal marketing strategies should be category-specific.

---

### 4️⃣ Subscription vs Non-Subscription Performance
**Insight:**  
Subscribed customers generate higher total revenue and transaction volume.

**Business implication:**  
Subscription programs are effective in increasing customer lifetime value.

---

### 5️⃣ Customer Value Segmentation (High / Mid / Low)
**Insight:**  
Revenue distribution is highly skewed, with high-value customers forming a small but critical segment.

**Business implication:**  
Retention strategies should prioritize high-value customers.

---

### 6️⃣ Frequency-Based Customer Segmentation
**Insight:**  
Most customers fall into occasional or one-time buyer segments.

**Business implication:**  
There is strong potential for upselling and loyalty campaigns.

---

### 7️⃣ Discount Impact on Purchase Behavior
**Insight:**  
Discounted purchases show changes in transaction volume but not always higher average purchase value.

**Business implication:**  
Discounts should be targeted rather than applied broadly.

---

### 8️⃣ Discount vs Repeat Purchase Behavior
**Insight:**  
Customers receiving discounts tend to have slightly higher repeat purchase indicators.

**Business implication:**  
Discounts may help customer retention when used selectively.

---

### 9️⃣ High-Value but Low-Satisfaction Customers
**Insight:**  
Some high-revenue customers report below-average satisfaction ratings.

**Business implication:**  
These customers pose a churn risk and should be prioritized for service improvement.

---

## 📌 Conclusion
This analysis demonstrates how SQL can be used not only for data extraction, but also for customer segmentation and strategic decision-making.  
The project emphasizes analytical thinking, data awareness, and business-oriented insights.

## 👤 Author
**Reta Tri Asriani**  
Background: Mathematics | Data & Financial Analysis  

