# Wexford & Rowan Data Dictionary

| Field | Description | Type |
|---|---|---|
| Order_ID | Unique identifier for each order | Text |
| Product_Category | Product department associated with the order | Text |
| Order_Date | Date the order was placed | Date |
| Time_Slot | Order timing band: Morning, Afternoon, Evening, or Night | Text |
| Customer_Age_Group | Customer age band: 18–25, 26–40, 41–60, or 60+ | Text |
| Items_in_Order | Number of items included in the order | Number |
| Price_per_Item | Average price per item in US dollars | Currency |
| Total_Order_Value | Total value of the order | Currency |
| Payment_Method | Card, Digital Wallet, Buy Now Pay Later, Gift Card, or Cash | Text |
| Customer_Region | US state associated with the customer | Text |
| Month | Helper field derived from Order Date for monthly analysis | Text |
| Weekday | Helper field derived from Order Date for weekday analysis | Text |

## Dataset Scope

- **Period:** Q3 2025
- **Unique orders:** 2,000
- **Items sold:** 4,179
- **Revenue:** $263,641
- **US states:** 12
- **Product categories:** 8
- **Business domain:** Omnichannel Retail
