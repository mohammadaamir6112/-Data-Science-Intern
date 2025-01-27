# E-commerce Transactions Analysis

This repository contains the analysis and models for the E-commerce Transactions dataset. It includes exploratory data analysis (EDA), a Lookalike Model, and Customer Segmentation using clustering techniques.

---

## Files in the Repository

### Dataset Files
- **Customers.csv**: Contains customer details (e.g., CustomerID, Region, SignupDate).
- **Products.csv**: Contains product details (e.g., ProductID, Category, Price).
- **Transactions.csv**: Contains transaction details (e.g., TransactionID, TotalValue, Quantity).

### Analysis and Results
- **Mohammad_Aamir_EDA.ipynb**: The Jupyter Notebook containing all analysis and modeling.
- **Mohammad_Aamir_EDA.pdf**: A concise PDF report summarizing the analysis, insights, and clustering results.

### Documentation
- **README.md**: This file contains instructions to use the repository and reproduce the analysis.

---

## Tasks Covered

### Task 1: Exploratory Data Analysis (EDA)
- Performed data cleaning and visualization.
- Derived business insights from the dataset.

### Task 2: Lookalike Model
- Built a recommendation model to find similar customers based on transaction history.
- Generated similarity scores and provided the top 3 similar customers for each user.

### Task 3: Customer Segmentation
- Clustered customers using transaction and profile data.
- Evaluated clustering results with metrics like the DB Index.

---

## How to Use

### Using Google Colab
1. Open the notebook `Mohammad_Aamir_EDA.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Upload the dataset files (`Customers.csv`, `Products.csv`, `Transactions.csv`) to your Colab runtime.
3. Run all the cells sequentially to reproduce the analysis and results.

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-analysis.git
   cd ecommerce-analysis
