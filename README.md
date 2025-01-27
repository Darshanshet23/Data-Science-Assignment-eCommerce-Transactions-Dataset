# Data-Science-Assignment-eCommerce-Transactions-Dataset

## Overview
This project analyzes an eCommerce dataset containing customer, product, and transaction data. It involves performing exploratory data analysis (EDA), building a lookalike model to recommend similar customers, and performing customer segmentation using clustering techniques.

## Dataset Description
The dataset consists of three CSV files:

### 1. Customers.csv
- **CustomerID**: Unique identifier for each customer.
- **CustomerName**: Name of the customer.
- **Region**: Continent where the customer resides.
- **SignupDate**: Date when the customer signed up.

### 2. Products.csv
- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **Category**: Product category.
- **Price**: Product price in USD.

### 3. Transactions.csv
- **TransactionID**: Unique identifier for each transaction.
- **CustomerID**: ID of the customer who made the transaction.
- **ProductID**: ID of the product sold.
- **TransactionDate**: Date of the transaction.
- **Quantity**: Quantity of the product purchased.
- **TotalValue**: Total value of the transaction.
- **Price**: Price of the product sold.

## Project Structure
This project consists of three tasks:
1. **Task 1: Exploratory Data Analysis (EDA) and Business Insights**
    - Perform EDA to understand the dataset.
    - Derive 5 actionable business insights from the analysis.
    - Deliverables:
      - `FirstName_LastName_EDA.ipynb`: Jupyter Notebook with EDA code.
      - `FirstName_LastName_EDA.pdf`: PDF report with business insights.

2. **Task 2: Lookalike Model**
    - Build a recommendation system to find 3 similar customers for each input customer.
    - Use customer and transaction data to compute similarity scores.
    - Deliverables:
      - `FirstName_LastName_Lookalike.ipynb`: Jupyter Notebook with model development code.
      - `FirstName_LastName_Lookalike.csv`: CSV file with recommendations for the first 20 customers (C0001-C0020).

3. **Task 3: Customer Segmentation/Clustering**
    - Perform customer segmentation using clustering techniques.
    - Evaluate the clustering results using metrics such as DB Index.
    - Visualize the clusters.
    - Deliverables:
      - `FirstName_LastName_Clustering.ipynb`: Jupyter Notebook with clustering code and visualizations.
      - `FirstName_LastName_Clustering.pdf`: PDF report with clustering results and evaluation metrics.

## Instructions
1. **Run the Notebooks**:
    - Install required Python libraries:
      ```
      pip install pandas numpy matplotlib seaborn scikit-learn
      ```
    - Open each `.ipynb` file in Jupyter Notebook or any compatible IDE.
    - Follow the instructions in each notebook to reproduce the results.

2. **View Reports**:
    - Open the PDF files for a summary of insights and results.

3. **Check Recommendations**:
    - The `Lookalike.csv` file contains the recommended similar customers and their similarity scores for the first 20 customers in `Customers.csv`.

## Files
- **Task 1**:
  - `Darshan_Shet_EDA.ipynb`
  - `Darshan_Shet_EDA.pdf`
- **Task 2**:
  - `Darshan_Shet_Lookalike.ipynb`
  - `Darshan_Shet_Lookalike.csv`
- **Task 3**:
  - `Darshan_Shet_Clustering.ipynb`
  - `Darshan_Shet_Clustering.pdf`

## Evaluation Criteria
- **EDA and Business Insights**: 25%
- **Lookalike Model**: 30%
- **Customer Segmentation**: 30%
- **Business Insights**: 15%

## Contact
For any questions or clarifications, feel free to contact:  
**Darshan Shet** 
