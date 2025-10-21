# Sales and Profit Analysis

## 📊 Project Overview

This project performs an **exploratory data analysis (EDA)** on a sample sales dataset to uncover **sales and profit trends** across various dimensions — including **time**, **product categories**, and **customer segments**.

The workflow involves **data loading, cleaning, transformation, and visualization** to generate actionable insights that can guide strategic decision-making.

---

## 🧾 Data

The analysis uses the dataset **`Sample data.csv`** containing detailed sales transaction records.

### Key Columns:

| Column         | Description                                               |
| -------------- | --------------------------------------------------------- |
| `Order Date`   | Date of the order                                         |
| `Ship Date`    | Date of shipment                                          |
| `Ship Mode`    | Mode of shipment                                          |
| `Customer ID`  | Unique identifier for each customer                       |
| `Segment`      | Customer segment (Consumer, Corporate, Home Office)       |
| `Country`      | Country where the order was placed                        |
| `City`         | City of the order                                         |
| `State`        | State of the order                                        |
| `Postal Code`  | Postal code of the customer                               |
| `Region`       | Geographical region                                       |
| `Product ID`   | Unique identifier for each product                        |
| `Category`     | Product category (Furniture, Office Supplies, Technology) |
| `Sub-Category` | Product sub-category                                      |
| `Product Name` | Name of the product                                       |
| `Sales`        | Sales amount                                              |
| `Quantity`     | Quantity ordered                                          |
| `Discount`     | Discount applied                                          |
| `Profit`       | Profit amount                                             |

---

## 🔍 Analysis Steps

1. **Data Loading and Inspection**

   * Imported the dataset into a pandas DataFrame
   * Checked data structure, missing values, and summary statistics

2. **Date Conversion**

   * Converted `Order Date` and `Ship Date` columns into datetime format

3. **Feature Engineering**

   * Extracted month, year, and day of week from `Order Date`

4. **Monthly Sales Analysis**

   * Calculated and visualized total monthly sales using a **line plot**

5. **Sales by Category**

   * Summarized and visualized total sales per category using a **pie chart**

6. **Sales by Sub-Category**

   * Analyzed total sales by sub-category using a **bar chart**

7. **Monthly Profit Analysis**

   * Calculated and visualized monthly profit trends using a **line plot**

8. **Profit by Category**

   * Visualized total profit by category using a **pie chart**

9. **Profit by Sub-Category**

   * Analyzed profit distribution across sub-categories using a **bar chart**

10. **Sales and Profit by Customer Segment**

    * Compared total sales and profit across customer segments using a **grouped bar chart**

11. **Sales-to-Profit Ratio**

    * Calculated ratio to assess profitability efficiency for each customer segment

---

## 📈 Key Findings

* **Seasonality:** Distinct monthly trends highlight peak sales and profit periods.
* **Category Insights:**

  * *Technology* generated the highest sales.
  * *Furniture* achieved the highest total profit.
* **Profitability Gaps:**

  * Certain sub-categories recorded consistent losses, suggesting pricing or cost issues.
* **Customer Segments:**

  * The *Home Office* segment demonstrated the strongest **sales-to-profit ratio**, making it the most profitable relative to sales volume.

---

## 🖼️ Visualizations

The project includes several visualizations created with **Matplotlib** and **Seaborn**, such as:

* Line plots for **monthly sales and profit trends**
* Pie charts for **category-level comparisons**
* Bar charts for **sub-category and segment analysis**
* Grouped bar charts for **sales vs. profit by segment**

---

## ⚙️ Tools & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📁 Project Structure

```
Sales_Profit_Analysis/
│
├── Sample data.csv
├── Sales_Profit_Analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Sales_Profit_Analysis.git
   cd Sales_Profit_Analysis
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Sales_Profit_Analysis.ipynb
   ```

4. Run the notebook cells to reproduce the analysis and visualizations.

---

## 📚 Conclusion

This project provides valuable insights into sales and profit distribution across time, products, and customer segments. It highlights key profitability drivers and areas requiring strategic improvements, supporting data-driven decision-making for business growth.

---
