Online Retail Dataset One-Page Summary Report Prepared by Allen Niyonzima | AnalystLab Africa — Data Analytics Internship Dataset Overview
The Online Retail dataset contains 541,909 transaction records across 8 columns, capturing UK-based ecommerce sales including invoice details, product descriptions, quantities, unit prices, customer IDs, and country of purchase.
Cleaning Challenges Encountered
A substantial number of records were missing CustomerID values and were removed, since transactions could not be reliably attributed without them. The dataset also contained negative and zero values in Quantity and UnitPrice, largely representing cancelled orders (identifiable by invoice numbers starting with "C"), which were separated from valid sales. Several non-product stock codes (e.g., postage, bank charges) were identified and excluded to keep the analysis focused on genuine product sales. Column names and text fields were also standardized for consistency before analysis.
Key EDA Findings
❖ The United Kingdom accounts for approximately 89.5% of total revenue, making it by far the dominant market.
❖ Monthly revenue shows strong seasonality, rising sharply from September and peaking in November at roughly £860,000.
❖ The average unit price sits well under £5, reflecting a catalogue of small, affordable items rather than premium goods.
❖ Customer spending is highly uneven — average spend (£1,368) is far above the median (£575), indicating a small number of high-value customers.
❖ “White Hanging Heart T-Light Holder” and “Assorted Colour Bird Ornament” are consistently among the top-selling products by both quantity and order frequency.
Top Insights
Heavy market concentration: the business is almost entirely reliant on UK sales, suggesting both risk (overdependence on one market) and opportunity (room for international growth in Germany, Eire, and France). Strong seasonal demand: Q4, especially November, represents the clearest window for inventory and marketing investment ahead of holiday shopping. Uneven customer value: a small segment of high-spending customers drives a disproportionate share of revenue, making retention strategies for this group a priority. Décor-focused product strategy: core demand comes from small, frequently repurchased gift and homedecor products, which should remain a stocking priority
