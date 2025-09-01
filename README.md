# Market-Baskrt-Analysis
This project demonstrates **Market Basket Analysis** using the Apriori algorithm to uncover associations between items frequently bought together.  
By applying **Association Rule Mining**, the project identifies frequent itemsets and generates strong rules with metrics such as **support**, **confidence**, and **lift**.

---

## Analysis  
- The dataset consists of **transaction records**, where each transaction contains multiple items purchased together.  
- The data is **unsupervised** and **categorical**.  
- Preprocessing transforms the transaction list into a format suitable for the **Apriori algorithm**.  
- Rules are evaluated using **support**, **confidence**, and **lift**.  
- Visualization is applied to highlight frequent co-occurring products.  

---

## Summary  
The purpose of this project is to discover **hidden patterns in transaction data**.  

Steps carried out:  
1. Import and clean the transaction dataset.  
2. Transform data into a structured format.  
3. Apply the **Apriori algorithm** to generate frequent itemsets.  
4. Derive **association rules** with support, confidence, and lift.  
5. Visualize frequent itemsets and rules for insights.  

---

## Results  
- Frequent itemsets were successfully generated.  
- Strong association rules identified items that are often purchased together.  
- Customers who purchase **butter** are highly likely to also purchase **other vegetables**.  
- Customers who purchase **fruits or vegetable juice** are highly likely to also purchase **rolls or buns**
---

## Analysis and Insights  
- **High-confidence rules** suggest strong predictive power for product recommendations.  
- **Lift > 1** indicates positive associations between items that occur together more frequently than expected.  
- Businesses can leverage these insights for:  
  - **Product placement**  
  - **Cross-selling strategies**  
  - **Recommendation systems**  

---

## Recommendation  
- Place frequently co-purchased items closer together in stores.  
- Use high-confidence rules to design **"Customers who bought X also bought Y"** systems.  
- Bundle strongly associated products for promotions.  
- Continuously update rules as new transaction data arrives to adapt to customer behavior.
