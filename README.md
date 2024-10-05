The Brief

AdventureWorks is a global manufacturing company that produces cycling equipment and accessories. The management team needs a way to track KPIs (sales, revenue, profit, returns), compare regional performance, analyze product-level trends, and identify high-value customers. The only data provided was a folder of raw CSV files, which contain information about transactions, returns, products, customers, and sales territories.

What I Learned

Data Preparation: The data was provided in CSV files for customers, product categories, territory data, sales data, and returns. I checked and cleaned the data for duplicates and errors.

Transformations: Performed transformations to create calculated columns and measures using common functions and formulas.

Data Modeling: Built a relational data model, creating active relationships between tables and understanding cardinality and filter flow.

Dashboard Design: Designed an interactive dashboard to visualize data using various charts and visuals, including KPI cards, matrices, slicers, bar charts, line and clustered column charts, gauges, and maps.

Interactivity: Added bookmarks, drill-through filters, and page-level and report-level filters to enhance interactivity.


Executive Dashboard – A high level summary of the entire data set. 
I started with executive level KPIs, which shows total revenue, profit orders and return rate of products. I also added three more KPI cards to give idea about how company manages to achieve monthly target compared to the previous month. I set monthly target 10% more than last month for revenue, orders and returns. Here we can see that only orders category fell short to achieve its monthly target. I tried to highlight this achievement using conditional formatting. 
I was able to include some drill through functionality after introducing the table with the top 10 products and the orders, revenue, and return rate linked to them. This indicates that you may examine more information about a single product by clicking on it to access a different dashboard (the Product Detail Dashboard).
Introduction of the filter at top right corner allows user to filter through different years and continent. Here is the result of dashboard showing numbers for Year 2021 and North America continent.


2) Map – A visual to learn about using geospatial data & tooltips.


3) Product Details Dashboard: This dashboard is drill through Type, Which shows more details for particular products shown in the top 10 table of executive dashboard.
One of the key things in this dashboard is the inclusion of gauge bars to show KPI numbers against the target for selected products.
Also, there is adjusted price displayed using numeric parameters to compare weekly profit and adjusted profit.
Lastly, I added different product metrics using field parameters to showcase the weekly trend of selected metric.

4)Customer Details: This dashboard displays customer level KPIs.

5) Decomposition Tree: I added decomposition tree using AI features available in Power Bi to show data (total orders) across different categories and subcategories.

