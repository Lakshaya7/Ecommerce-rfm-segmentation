# E-Commerce Customer Segmentation (RFM Analysis)

## 📌 Objective
The goal of this project is to analyze transactional data from a UK-based online retailer and segment customers based on their purchasing behavior. By applying the RFM (Recency, Frequency, Monetary) framework, the customer base is divided into actionable cohorts to drive targeted marketing strategies.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas (Data manipulation), Matplotlib & Seaborn (Data visualization)
* **Environment:** Jupyter Notebook / Google Colab

## 📊 Methodology
1. **Data Cleaning:** Handled missing Customer IDs and filtered out cancelled orders (negative quantities).
2. **Feature Engineering:** Calculated Total Revenue per line item.
3. **RFM Calculation:** 
   * **Recency:** Days since the customer's last purchase.
   * **Frequency:** Total number of unique orders.
   * **Monetary:** Total amount spent by the customer.
4. **Segmentation:** Scored customers from 1-4 across all three metrics and combined them to create 5 distinct groups: Champions, Loyal Customers, Potential Loyalists, At Risk, and Lost.

## 💡 Key Business Insights
* **Champions:** [Insert the number/percentage from your chart] of customers are highly engaged and drive the most revenue. Recommendation: Enroll in early-access product programs.
* **At-Risk:** A significant cluster of historical high-spenders have not returned in over [X] days. Recommendation: Deploy targeted win-back email campaigns with discount incentives.

## 🚀 How to Run
This project pulls data dynamically from the UCI Machine Learning Repository. No local datasets are required.
1. Clone the repository.
2. Open `Customer_Segmentation_RFM.ipynb` in Jupyter Notebook or Google Colab.
3. Run all cells sequentially.
