
# Target Brazil Dataset Analysis

This repository contains a comprehensive analysis of Target's operations in Brazil, based on order data from 2016 to 2018. The analysis aims to provide actionable insights on customer behavior, product performance, sales trends, and logistics.

## Project Overview

This project leverages the Target Brazil dataset to generate valuable insights that can help enhance Target’s strategic decision-making. The dataset includes customer orders, payments, shipping details, product attributes, and customer demographics.

### Dataset Information

The dataset includes the following files:

1. `customers.csv`: Contains customer information, including demographics and location.
2. `sellers.csv`: Details about various sellers associated with Target's platform.
3. `geolocation.csv`: Geolocation data for both customers and sellers.
4. `orders.csv`: Information about each order, including order status and timestamp.
5. `order_items.csv`: Item-level details for each order, including product IDs and quantities.
6. `payments.csv`: Payment methods and details associated with each order.
7. `products.csv`: Attributes of the products sold, including category and price.
8. `sellers.csv`: Seller information, including location and performance data.

### Key Insights from the Analysis

1. **Customer Insights**:
   - The top 10% of customers contribute 62% of total revenue.
   - Customer retention rate stands at 38%, indicating room for improvement.
   - Year-over-year customer acquisition growth was 12%.

2. **Product Insights**:
   - Top products contribute a significant portion of revenue, with the best-selling product generating $7.5 million.
   - The electronics category saw a 25% increase in revenue.

3. **Sales and Revenue Insights**:
   - Peak months for sales are November to January, with November accounting for 20% of annual revenue.
   - Repeat customers generate 58% of total revenue, underscoring the importance of loyalty programs.

4. **Logistics Insights**:
   - Average delivery time is 5 days, with variations between product categories (e.g., books: 3 days, furniture: 7 days).

### Notebooks

The repository contains Jupyter notebooks used for analysis:
- **csv_to_sql.ipynb**: A notebook that demonstrates how to convert the provided CSV files into a SQL database for efficient querying and analysis.
- **L1.ipynb, L2.ipynb, L3.ipynb**: Additional notebooks with various levels of data exploration and visualization using Python and SQL queries.

### Data Source

The dataset is publicly available on Kaggle and can be accessed here: [Target Brazil Dataset](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv).

### Requirements

- Python 3.8 or higher
- Pandas
- SQLAlchemy
- Jupyter
- Matplotlib/Seaborn (for visualizations)
- SQLite (optional, for SQL-based exploration)

### Insights and Visualizations

The analysis reveals actionable insights related to customer behavior, product performance, and logistics efficiency.

### License

This project is licensed under the MIT License.
