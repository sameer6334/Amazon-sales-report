# Amazon-sales-report
This project analyzes Amazon sales data using Python, providing insights into sales distribution, top-performing states, courier statuses, and other key metrics. The analysis is accompanied by various visualizations to enhance understanding and presentation.

---

## Key Features

### 1. **Sales Distribution by State**
- Visualized the distribution of sales across different states.
- Identified trends and disparities in regional sales performance.

### 2. **Top 10 States by Sales**
- Ranked the top 10 states contributing the highest sales.
- Highlighted key drivers for these states' performance.

### 3. **Visualizations**
- **Scatter Plot**: Explored relationships between variables such as sales and size.
- **Pie Chart**: Illustrated percentage contributions of sales categories.
- **Histogram**: Analyzed frequency distributions of sales data.

### 4. **Courier Status Analysis**
- Grouped sales data by courier status (e.g., shipped, in transit, delivered).
- Evaluated operational efficiency and delivery trends.

### 5. **Product Size Analysis**
- Analyzed sales distribution based on product size classifications.

### 6. **Interactive Insights**
- Generated actionable insights to optimize operations and identify growth opportunities.

---

## Tools and Libraries Used
- **Python**
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For advanced and aesthetic visualizations.

---

## How to Run the Project

### Prerequisites
- Python 3.x
- Jupyter Notebook (or any compatible IDE)
- Install the required libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn
  ```

### Steps
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd amazon-sales-report
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook amazon_sales_analysis.ipynb
   ```
4. Run the cells in the notebook sequentially to generate the analysis and visualizations.

---

## Dataset
The dataset used for this project contains the following key columns:
- **Order ID**: Unique identifier for each order.
- **Date**: Date of the order.
- **Status**: Current status of the order.
- **Fulfilment**: Type of fulfilment (e.g., FBA or seller-fulfilled).
- **Sales Channel**: Channel through which the sale was made.
- **Ship-Service-Level**: Shipping service level used.
- **Category**: Product category.
- **Size**: Classification of products by size.
- **Courier Status**: Tracks the delivery status of orders.
- **Quantity**: Number of items in the order.
- **Currency**: Currency in which the transaction was made.
- **Amount**: Total sales amount.
- **Ship-City**: City of the shipment.
- **Ship-State**: State of the shipment.
- **Ship-Postal-Code**: Postal code of the shipment location.
- **Ship-Country**: Country of the shipment.
- **B2B**: Indicates if the order is a business-to-business transaction.
- **Fulfilled-By**: Entity responsible for fulfilling the order.

*Note: The dataset used for this analysis is simulated for academic purposes.*

---

## Insights and Outcomes
- Identified the states contributing the most to sales revenue.
- Visualized courier statuses to assess delivery trends and efficiency.
- Highlighted sales trends through scatter plots, pie charts, and histograms.

---

## Future Enhancements
- Incorporate time-series analysis for sales trends over time.
- Analyze customer behavior based on product categories.
- Add machine learning models for predictive analytics.

---

## Author
- **[Your Name]**  
  Data Analyst | Python Developer  
  [LinkedIn Profile](https://linkedin.com/in/yourprofile)  

---

## Acknowledgments
This project was developed as part of my journey to strengthen data analysis and visualization skills. Special thanks to the open-source
