# Customer Retention Analysis - Identifying Patterns Associated With Customer Churn

## Project Context

I analyzed customer data for a retail business that is experiencing a significant level of customer churn. Management wants to understand how well the business is retaining customers and identify customer characteristics and purchasing-related patterns associated with retention and churn.


> **Dataset note:** The dataset used in this project was generated with AI for analytical practice. The findings demonstrate the analytical approach and should not be interpreted as evidence about a real retail business.

## Problem Statement

The business is acquiring customers, but it does not have a clear understanding of how well it is retaining them or what patterns are associated with customers remaining active or becoming churned.

## Key Findings

1. Customer churn is high - The analysis found that **55.5% of customers were classified as churned**. This indicates a substantial customer-retention challenge and provides a basis for investigating where churn is concentrated.

2. Customer retention differs across acquisition channels - Customers acquired through **in-store sign-up and referrals** had more active customers, while customers acquired through **organic search, social media, paid advertising, and email campaigns** had more churned customers. This suggests that customer retention may differ depending on how customers are acquired.

3. Loyalty members show stronger retention - Most customers without loyalty membership were churned, while most customers with loyalty membership remained active. This indicates an association between loyalty-program membership and customer retention.

4. Product-related complaints are prominent among churned customers - The three most common complaints among churned customers were return requests, product quality, and damaged items. The concentration of these complaints led me to investigate whether product-related issues were connected to refund activity.

5. Refund activity is concentrated in specific products - The products with the highest refund activity were Outdoor Recreation, Fresh Foods, Men's Wear, and Footwear, providing specific areas for the business to investigate further.

## Tools

* Excel (Power Query, Data cleaning and preparation)
* Tableau (Data modelling, analysis and visualization)
* Artificial Intelligence (Claude, Data sourcing)

## Analysis Process

### 1. Measuring Customer Churn

I first calculated the proportion of customers classified as active and churned to establish the overall retention situation. The analysis showed a **55.5% customer churn rate**.

<img width="619" height="559" alt="Churn Rate" src="https://github.com/user-attachments/assets/c4a1a1cf-3217-4cdb-832f-465fa5924269" />

---

### 2. Investigating Acquisition Channels

I compared customer retention across acquisition channels to determine whether some acquisition sources were associated with stronger customer retention than others. Customers acquired through **in-store sign-up and referrals** had more active customers, while **organic search, social media, paid advertising, and email campaigns** had more churned customers.

<img width="619" height="559" alt="CR_by_AC" src="https://github.com/user-attachments/assets/721948c9-e9bb-40e9-b21e-e9e764f1966a" />
<img width="619" height="559" alt="CR_by_AC (2)" src="https://github.com/user-attachments/assets/37edecb6-aafd-4007-9116-aada058031b3" />

---

### 3. Examining Loyalty Membership

I then compared customer status between loyalty-program members and non-members. Most customers without loyalty membership were churned, while most loyalty members remained active.

<img width="619" height="559" alt="membership-churn" src="https://github.com/user-attachments/assets/cd2c4117-8797-4139-9494-2684f07f70be" />

---

### 4. Investigating Complaints Among Churned Customers

After identifying the overall churn pattern, I looked at the complaints reported by churned customers. The most common complaints were **return requests, product quality, and damaged items**. Because these complaints were largely product-related, I investigated refund activity to determine where these issues were concentrated.

<img width="619" height="559" alt="complaints" src="https://github.com/user-attachments/assets/67f483bd-8682-463d-8e47-e3b9b513053c" />

---

### 5. Investigating Refunds by Product

I compared refund activity across individual products to identify where refunds were most concentrated. The products with the highest refund activity were Outdoor Recreation, Fresh Foods, Men's Wear, and Footwear.

<img width="719" height="559" alt="products_refund" src="https://github.com/user-attachments/assets/3e137363-7ff4-4f66-b639-8c2ead21124b" />

## Main Takeaways

* The analysis showed that customer churn is substantial, with **55.5% of customers classified as churned**.

* Retention patterns differed across acquisition channels, with in-store sign-ups and referrals showing more active customers than several digital acquisition channels.

* Loyalty membership was also associated with stronger customer retention, suggesting that the loyalty programme may be an important area for further investigation.

* Refund activity was concentrated in Outdoor Recreation, Fresh Foods, Men's Wear, and Footwear, narrowing the potential product-related issues to specific areas that management can investigate.

* These findings suggest that customer retention should not be viewed only as a marketing problem. **Acquisition strategy, loyalty engagement, and product experience may all be relevant areas for the business to investigate.**

## Recommendations

1. Increase focus on non-digital acquisition channels - The business should consider increasing its focus on **non-digital acquisition channels, particularly in-store sign-ups and referrals**, which showed stronger customer retention patterns in the analysis.

2. Strengthen the loyalty programme - Because loyalty members showed stronger retention, the business should investigate ways to increase loyalty-program participation and encourage repeat purchasing among eligible non-members.

3. Investigate product-related customer complaints - The concentration of return requests, product-quality complaints, and damaged-item complaints among churned customers warrants further investigation. Management should examine product quality, packaging, handling, fulfillment, and supplier-related issues in the affected product areas.
