# Customer-Segmentation-in-E-commerce

## Problem Statement
Identify customer clusters based on purchasing habits and browsing behavior using real-world e-commerce transaction data.

---

## Introduction
In the highly competitive e-commerce landscape, understanding customer behavior is essential for business success.  
This project focuses on accurately segmenting customers based on their buying patterns and browsing activities to assist businesses in creating personalized marketing strategies, improving customer experience, and boosting overall profitability.

---

## Methodology

1. **Data Upload:**  
   Uploaded the transaction dataset containing fields like InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

2. **Data Preprocessing:**  
   - Dropped records with missing CustomerIDs.
   - Removed negative quantities indicating product returns.
   - Created a new feature: `TotalPrice = Quantity × UnitPrice`.

3. **Feature Aggregation:**  
   Grouped data at the customer level to calculate:
   - Number of orders
   - Total quantity purchased
   - Total amount spent

4. **Feature Scaling:**  
   Applied StandardScaler to normalize the feature space.

5. **Clustering:**  
   - Used the Elbow Method to determine the optimal number of clusters.
   - Implemented KMeans clustering with the optimal number of clusters (4).

6. **Visualization:**  
   Visualized the customer clusters using a scatter plot with spending and quantity axes.

---

## Output/Result

- **Optimal clusters found:** 4
- **Customer groups segmented** based on spending and purchase quantity.
- **Visualization:** Scatter plot clearly showing distinct customer clusters.

---

## Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## References/Credits

- Dataset: Provided by course instructor during the exam.
- Algorithms: KMeans Clustering (from Scikit-learn library).
- Tools: Google Colab for implementation and visualization.

---

## Author

- **Name:** Yashi Kesarwani
- **Roll No:** 202401100400219

