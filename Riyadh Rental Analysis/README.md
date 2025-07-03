# Riyadh Short-Term Rental: Weekday Occupancy Optimization

This project analyzes booking data for Livedin, a short-term rental company in Riyadh, to solve the business problem of low weekday occupancy and inconsistent revenue.

## Business Problem
[cite_start]Weekday (Sunday-Thursday) occupancy levels were consistently falling below 50%, impacting revenue[cite: 9]. [cite_start]The goal was to identify the causes of this underperformance and deliver data-driven strategies to boost weekday bookings and Average Daily Rate (ADR)[cite: 10].

## My Analytical Approach
My strategy was to avoid a one-size-fits-all solution by segmenting the data to find specific patterns. I broke down the analysis into three key areas:
1.  **District-Wise Trends:** To see if location was a key factor.
2.  **Property-Type Performance:** To understand if business travelers (1-2BR) behaved differently from leisure travelers (3BR, Chalets).
3.  **Booking Channel Effectiveness:** To determine which OTA (e.g., Airbnb, Booking.com) was best suited for each property type.

## Key Findings & Visualizations

### District-Wise Performance
Analysis of weekday trends by district showed two distinct behaviors. [cite_start]Business-centric districts like **Al Olaya** and **Al Sulimaniyah** saw demand drop sharply on Thursday, the end of the workweek[cite: 38]. [cite_start]In contrast, other districts like **Al Falah** and **Al Malqa** saw stable or rising Thursday demand, indicating a shift to pre-weekend leisure traffic[cite: 39].

# (Instruction: Insert screenshot of the "Weekday Occupancy Trends by District" line chart here)

### Thursday Occupancy by Property Type
[cite_start]Drilling down into Thursday performance, it became clear that smaller, business-focused units (1BR and 2BR) saw an occupancy decline[cite: 55]. [cite_start]However, larger units like 3BRs and Chalets, which underperformed early in the week, stabilized on Thursday, confirming the shift toward leisure and group stays ahead of the weekend[cite: 55, 56].

# (Instruction: Insert screenshot of the "Thursday Occupancy Distribution by Property Type" box plot here)

### Booking Channel (OTA) Effectiveness
The data showed a strong alignment between OTA and property type. [cite_start]**Booking.com** and **Direct bookings** were the top channels for 1BR and 2BR units, aligning with business travel[cite: 104]. [cite_start]Conversely, **Al Mosafir** was the best platform for Chalets, and **Airbnb** excelled for 3BR apartments, reinforcing their use for leisure and group bookings[cite: 104, 105].

# (Instruction: Insert screenshot of the "Avg Weekday Occupancy by Property Type & OTA Channel" heatmap here)

## Strategic Recommendations
Based on these findings, I proposed a set of targeted actions instead of generic discounts:
* [cite_start]**Promote Larger Units on Thursdays:** Market Chalets and 3BRs on Al Mosafir and Airbnb as "pre-weekend getaways"[cite: 137].
* [cite_start]**Optimize Business Listings:** Focus marketing for 1BR/2BR units on Booking.com and Direct channels from Sunday to Wednesday[cite: 139].
* [cite_start]**Implement Dynamic Pricing:** Introduce "Stay Thursday, Get Friday 50% Off" bundles for larger units to capture the leisure market[cite: 144].
* [cite_start]**Improve Low-Rated Listings:** Audit all properties rated below 4.2, as the data clearly shows that guest satisfaction directly impacts weekday occupancy[cite: 120, 141].

## Files in this Folder
* `Livedin Data Analytics Case Study - Wasi Khan.pdf`: The complete project report.
* `Source-Data.csv`: The source CSV file used for the analysis.
* `[Your-Screenshot-1.png]`, `[Your-Screenshot-2.png]`: Images of the charts from the report.
