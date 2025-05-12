
# Wholesale Sales Net Revenue Analysis (SQL)

This project analyzes wholesale sales data to calculate net revenue by product line, month (June to August), and warehouse.

## 📌 Objective

To extract insights about revenue performance across different product lines and locations by calculating:
- **Net Revenue** = Total - Payment Fee
- Filtered by client type: Wholesale

## 🛠️ Technologies Used
- PostgreSQL (or your SQL flavor)
- SQL aggregate functions (SUM)
- CASE statements
- Filtering and grouping

## 📊 Output Example
| product_line | month  | warehouse | net_revenue |
|--------------|--------|-----------|-------------|
| Electronics  | July   | A         | 12450.00    |

## 📁 File Structure
- `sales_wholesale_analysis.sql`: The main query script
- *(Optional)* `sample_data.csv`: Sample data if available

## 🚀 How to Use
1. Load your sales data into a SQL database.
2. Run the query from `sales_wholesale_analysis.sql`.
