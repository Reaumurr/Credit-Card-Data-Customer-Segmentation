# Credit Card Data Customer Segmentation

This program is made to carry out Customer Segmentation from a bank's credit card data from Google BigQuery.

## Dataset Description
| Feature | Description |
| CUST_ID | The unique identifier for each customer.|
| BALANCE | The total current balance of the customer's account.|
| BALANCE_FREQUENCY | The frequency with which the account balance is updated.|
| PURCHASES | The total amount of purchases made by the customer.|
| ONEOFF_PURCHASES | The total amount of one-time purchases made by the customer.|
| INSTALLMENTS_PURCHASES | The total amount of purchases made in installments.|
| CASH_ADVANCE | The total amount of cash advances taken by the customer.|
| PURCHASES_FREQUENCY | The frequency of purchases made by the customer.|
| ONEOFF_PURCHASES_FREQUENCY | The frequency of one-time purchases made by the customer.|
| PURCHASES_INSTALLMENTS_FREQUENCY | The frequency of purchases made in installments.|
| CASH_ADVANCE_FREQUENCY | The frequency of cash advances taken by the customer.|
| CASH_ADVANCE_TRX | The number of transactions involving cash advances.|
| PURCHASES_TRX | The number of transactions involving purchases. |
| CREDIT_LIMIT | The credit limit assigned to the customer's account.|
| PAYMENTS | The total amount of payments made by the customer. |
| MINIMUM_PAYMENTS | The minimum amount of payments required by the customer.|
| PRC_FULL_PAYMENT | The percentage of payments made in full by the customer.|
| TENURE | The number of months the customer has been with the bank.|


## Business Insight:
### Clusters suggest that customers can be segmented into three groups based on their behavior:

- High-balance, cash-advance users (Cluster 0): These customers tend to have higher balances and use cash advance more frequently. They also make higher minimum payments and have a higher full payment rate.
- High-purchase, installment users (Cluster 1): These customers tend to make more purchases and have higher credit limits. They also make higher payments, but have lower minimum payments and full payment rates compared to Cluster 0.
- Low-activity users (Cluster 2): These customers tend to have lower values across most features, indicating lower activity and engagement with the credit card.

### Recommendations:
- Cluster 0: You can target these customers with offers that encourage them to pay off their balance or switch to a lower interest credit card. Additionally, you can offer financial management tools to help them better manage their spending.

- Cluster 1: They may be good candidates for rewards-based credit cards or promotional offers that encourage them to continue using their card for purchases. You can also offer installment payment plans for big-ticket items to attract these customers.

- Cluster 2: You can target these customers with educational resources and tools to help them better understand and manage their credit. Additionally, you can offer low-interest balance transfer promotions to help them pay off their debt.
