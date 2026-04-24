**Project:** Customer & Revenue Analytics for a UK Online Gift Retailer
**Business context:** A UK-based online retailer sells giftware and homeware across Europe, serving both individual consumers and small wholesale buyers. The business is highly seasonal, with Q4 driving a disproportionate share of annual revenue. Growth depends on acquiring new customers during peak season and retaining them through the following year.
**Stakeholder:** Head of Growth & Marketing. They own customer acquisition, retention, and marketing spend allocation, and report to the CEO on revenue performance.
**The problem:** Marketing spend has grown year-over-year but the team lacks visibility into which customer segments, products, and geographies are actually driving profitable growth. They need a single source of truth to answer revenue, customer, and product performance questions without waiting on ad-hoc analyst requests.

**Key business questions:**

1. How is revenue trending month-over-month and year-over-year, and what's driving the change?
2. Which products generate the most revenue, and which are under-performing relative to their order volume?
3. Which countries represent our largest markets, and where is there untapped potential?
4. What's the split between new and returning customer revenue, and is our customer base growing?
5. Who are our highest-value customers and how concentrated is revenue among them?
6. Are there seasonal patterns we should plan marketing spend around?

**Headline KPIs:**

1. Total Revenue (with YoY delta)
2. Total Orders
3. Average Order Value (AOV)
4. Active Customers
5. Repeat Customer Rate
6. Revenue from Top 20% of Customers (Pareto check)

**Scope & assumptions:**

**Analysis period:** December 2009 to December 2011 (full two years)
Excludes cancelled orders (InvoiceNo starting with 'C') and transactions with negative quantities from revenue calculations, but tracks returns separately as a data quality metric
Transactions with missing CustomerID are included in revenue/product analysis but excluded from customer-level analysis (roughly 25% of rows — a known limitation)
Revenue calculated as Quantity × UnitPrice in GBP; no currency conversion applied
"Active customer" defined as any customer with ≥1 purchase in the period being analyzed

**Deliverable:** Interactive Tableau dashboard published on Tableau Public, with a GitHub repository containing data cleaning notebook, processed dataset, data dictionary, and a case study README documenting findings and recommendations.
