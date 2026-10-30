# Olist Delivery & Customer Satisfaction Analysis (Power BI)
End-to-end Power BI analysis of 96K orders from Olist, a Brazilian e-commerce marketplace: Power Query cleaning, star-schema data model, DAX measures and a 3-page dashboard linking delivery delays to customer ratings.

# Business question: Do late deliveries hurt customer ratings, and where should Olist fix delivery first?

| Metric | Value |
|---|---|
| Revenue | R$13.18M (Jan 2017 – Aug 2018) |
| Delivered orders | 96,203 |
| On-time delivery | 93.2% (6,531 late orders) |
| Average rating | 4.29★ on time vs 2.27★ late |

## Key findings
- Late deliveries cut ratings by 2 stars, falling to 1.70★ when an order is 8+ days late
- On-time delivery dipped to *~87% in Nov 2017* (the sales peak) and fell to *~80% in Mar 2018*
- *Ceará, Bahia and Rio de Janeiro* have about *3x* Paraná's late rate (13.8% vs 4.1%)
- *São Paulo* generates *38%* of revenue and is among the best for delivery (4.5% late)

## What I did
- *Power Query:* cleaned and joined 5 tables; removed undelivered orders and 8 delivered orders with no delivery date; fixed duplicate orders caused by multiple reviews per order
- *Data model:* star schema with a Date table
- *DAX:* measures for revenue, on-time %, late rate and rating by delivery status
- *Report:* 3 pages (Overview, Delivery & Satisfaction, Insights & Recommendations) with synced slicers and page navigation

  ## Files
| File | Description |
|---|---|
| Olist_Delivery_Analysis.pbix | Power BI report |
| overview.png, delivery.png, insights.png | Page screenshots |

Open the .pbix in Power BI Desktop (free). In Desktop, use *Ctrl + click* on the navigation buttons.

*Data:* [Olist Brazilian E-Commerce Public Dataset (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) · values in Brazilian Real (R$)

*Author:* Arushi Vaishnav · [LinkedIn](https://linkedin.com/in/arushivaishnav)






