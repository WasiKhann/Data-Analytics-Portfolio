# E-commerce Order Cancellation and Refund Analysis

This project analyzes order data from a Pakistani e-commerce company to identify the root causes behind a high rate of cancellations and refunds and propose targeted solutions.

## Business Problem
[cite_start]A significant portion of orders, 45.1%, were being canceled or refunded, which directly impacts profitability and customer trust[cite: 196]. My objective was to move beyond the top-line number and find specific, actionable drivers of this problem.

## My Analytical Approach
I hypothesized that the issue was not uniform across the business. My analysis focused on segmenting the data to confirm this, specifically by:
1.  **Time-Series Analysis:** To check for seasonality or event-driven spikes.
2.  **Categorical Analysis:** To identify if specific product types were more problematic.
3.  **Payment Method Analysis:** To see if the payment process contributed to cancellations.

## Key Findings & Dashboard
![Activity 3 Dashboard](https://i.imgur.com/uR0J48d.png)

* [cite_start]**High Cancellation Rate:** Confirmed that canceled and refunded orders made up 45.1% of all statuses[cite: 196].
* [cite_start]**Category-Specific Issues:** "Mobiles & Tablets" and "Men's Fashion" had disproportionately high cancellation rates, pointing towards issues with product expectations or quality control in these areas[cite: 200].
* [cite_start]**Payment Method Impact:** Cash on Delivery (COD) showed a strong correlation with higher cancellation rates, suggesting a lack of customer commitment at the point of order[cite: 198].
* [cite_start]**Ineffective Discounts:** The analysis showed that the existing discount strategy was not working, as increasing discounts did not lead to a higher average order value[cite: 202].

## Files in this Folder
* `Business Intelligence Assignment 3.docx`: The full project write-up.
* `Assignment 3 BI.pbix`: The interactive Power BI dashboard file.
* `Reduced_Pakistan_Ecommerce_Dataset.csv`: The cleaned dataset used.
