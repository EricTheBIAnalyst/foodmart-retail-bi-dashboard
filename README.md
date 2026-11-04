FOODMART RETAIL BI DASHBOARD

A Power BI retail analytics project that turns Foodmart grocery sales data into a four-page KPI dashboard covering performance against target, store and regional results, customer behaviour, and product and brand returns.

Business problem

Foodmart is a multi-store grocery business. Management needs one place to answer four questions: are we on target, which stores and formats earn the most, who is buying and how much are they worth, and which brands and products earn the most and get returned.

Dashboard pages

1. Executive Summary: Are we on target, and which brands and stores lead?

![Executive Summary](image-executive-summary.png)

- Headline KPIs: $1.8M revenue, $1.1M profit, 59.7% profit margin, 270K transactions, $6.5 average order value (AOV)
- Revenue trend from Jan 1997 to the end of 1998, with filters for year, region and store type
- Monthly revenue, profit and transactions compared with target. In the latest month, all three sat about 4% below target (revenue $120,161 vs $125,167 target)
- Top 5 brands: Hermanos ($57K), Tell Tale ($52K), Ebony ($50K), Tri-State ($49K), High Top ($47K)
- Top 5 stores: Store 13 ($170K), Store 17 ($158K), Store 15 ($116K), Store 11 ($115K), Store 24 ($111K)

2. Store and Regional Performance: Which stores, cities and formats earn the most?

![Store and Regional Performance](images-store-regional-performance.png)

- Revenue by city, led by Salem ($170K) and Tacoma ($158K)
- Revenue by store type: Supermarket ($0.79M) and Deluxe Supermarket ($0.67M) bring in roughly 83% of revenue, while Small Grocery adds only $0.03M
- Store table with transactions, revenue, profit and AOV. Store 13 leads with 25,865 transactions, $170,399 revenue and $101,715 profit
- AOV stays between $6.6 and $6.7 across stores, so differences in store revenue come mainly from transaction volume, not basket size
- Map of revenue by district

3. Customer Insights: Who is buying and how much are they worth?

![Customer Insights](image-customer-insights.png)

- 8,842 unique customers and $200 revenue per customer
- Unique customers grew from about 1,400 in early 1997 to about 2,700 by late 1998, in step with the rise in monthly revenue
- Transactions by member card: Bronze 61%, Normal 25%, Golden 14%
- Transactions by occupation: Professional 39%, Skilled Manual 32%, Manual 29%
- Top 100 customers by revenue, with transactions and AOV, and a map of customers by city

4. Product and Brand Performance: Which brands and products earn the most, and which get returned?

![Product and Brand Performance](images-product-brand-performance.png)

- Profit trend rising from about $27K a month in early 1997 to about $72K by the end of 1998
- Revenue by brand, led by Hermanos
- Top 15 products by revenue, with average retail price, transactions, profit and return rate. Hermanos Green Pepper leads with $2,490 revenue and a 1.2% return rate
- Return rates among top products range from 0.3% (Horatio Frosted Cookies) to 1.8% (Horatio Fudge Cookies), which flags where quality or stock issues may sit

Key insights

1. The business earned $1.8M revenue at a 59.7% profit margin, but the latest month finished about 4% below target on revenue, profit and transactions.
2. Revenue roughly doubled from about $50K to about $100K a month between late 1997 and early 1998, and unique customers rose over the same period.
3. Supermarket and Deluxe Supermarket formats generate most of the revenue. Small Grocery and Mid-Size Grocery add little.
4. AOV is almost flat across stores at $6.6 to $6.7, so growth depends on bringing in more transactions and customers.
5. Return rates differ across the top products, which makes them a useful follow-up metric for category managers.

Tools and skills

Power BI, Power Query, data modelling, DAX, KPI dashboard design, retail analytics, data visualization

How it was built

1. Data prepared and cleaned in Power Query
2. Data model built for reporting. Tables: [list your fact and dimension tables]
3. DAX measures for revenue, profit, profit %, transactions, AOV, targets, unique customers and return rate. See [dax/measures.md](dax/measures.md)
4. Four report pages with slicers, trend lines, KPI cards with target comparison, maps and ranked tables

Data source

Foodmart sample dataset. Source: [add link]. The raw data is not included in this repository. See [data/README.md](data/README.md).

Live project

[View the project on Maven Showcase](https://mavenshowcase.com/project/58198)

About me

Eric Kyuma, Business Intelligence and Data Analyst focused on retail analytics.
Nairobi, Kenya | [LinkedIn](add your LinkedIn link) | [Maven Showcase portfolio](https://mavenshowcase.com/profile/0841f340-7091-70d6-4153-097ec33884f7)
