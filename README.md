**# EDA on Sales Data**

## **Project Overview**
This project involves performing **Exploratory Data Analysis (EDA)** on sales data to derive meaningful business insights. The analysis includes data cleaning, visualization, and statistical aggregation to understand product performance, revenue trends, and sales distribution.

---

## **Dataset Description**
The dataset contains the following key columns:
- **Date:** Date of the transaction.
- **Product:** Category of the product sold.
- **Quantity:** Number of units sold.
- **Price:** Price per unit of the product.
- **Revenue:** Total revenue generated.
- **City:** Location where the transaction occurred.
- **Manager:** Manager overseeing the sales.

---

## **Key Insights**
- **Burgers** generate the highest revenue, indicating high profitability.
- **Beverages** and **Fries** lead in terms of quantity sold, suggesting high consumer demand.
- **Lebanon** is the city with the highest total revenue.
- **Joao Silva** is the top-performing manager in terms of revenue.
- Revenue trends show a significant spike in **mid-November**, followed by steady growth in **December**.

---

## **Data Cleaning & Preprocessing**
- Removed extra spaces and standardized text fields.
- Handled missing values and ensured data type consistency.
- Created new columns for total revenue and grouped data for aggregation.

---

## **Visualizations**
- **Bar Plots:** For comparing revenue and quantity across products, cities, and managers.
- **Line Plot:** To observe date-wise revenue trends.
- **Grouped Bar Plot:** To showcase the average quantity and revenue by product.

---

## **Tools & Libraries Used**
- **Python** for data analysis.
- **Pandas** for data manipulation.
- **Matplotlib** & **Seaborn** for data visualization.

---

## **How to Run the Project**
1. Clone the repository.
2. Install required dependencies from **requirements.txt**.
3. Run the Jupyter Notebook.

```bash
pip install -r requirements.txt
python analysis_script.py
```

---

## **Conclusion**
This EDA provided valuable insights into sales performance, identifying top-performing products, cities, and managers. These findings can guide decision-making for marketing strategies and inventory management.

---

## **Contributions**
Contributions are welcome! Feel free to open a pull request or report issues.

---

