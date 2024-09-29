Online Retail Recommendation System

 Project Overview
This project is my first attempt at creating an Online Retail Recommendation System. The system is designed to recommend products to customers based on purchasing patterns from a retail dataset. The dataset contains transaction details, such as invoice number, stock code, product description, quantity, invoice date, unit price, customer ID, and country of purchase. The goal is to help online retailers offer personalized product recommendations to their customers.

Dataset
The dataset used in this project can be found on Kaggle and includes:

   - Invoice Number
   - Stock Code
   - Description
   - Quantity
   - Invoice Date
   - Unit Price
   - Customer ID
   - Country

#Data Analysis Steps
1. Data Cleaning:
   - Handled missing values by dropping rows with missing `CustomerID` and `Description`.
   - Converted `InvoiceDate` to a date-time format for easier time-based analysis.

2. Data Transformation:
   - Created a pivot table for product quantities purchased by each customer.
   - Computed the similarity matrix using cosine similarity to identify purchasing behavior similarities between customers.

3. Data Visualizations:
   - **Global Popular Items**: Bar plot showing the top 10 most sold items globally.
   - **Country-wise Popular Items**: Visualized the top-selling item in each country.
   - **Monthly Popular Items**: Showcased the most sold item each month across the dataset.

4. Product Recommendation:
   - Developed a function that provides product recommendations based on customer purchase history and similar customer behavior.

Key Features
- Collaborative Filtering: Recommendations are based on the purchasing patterns of similar customers.
- Global and Local Insights: Visualizations highlight popular items globally, by country, and by month.
- Cosine Similarity: Measures customer similarity to recommend relevant products.

How to Run
1. Clone the repository:
  
2. Install the required dependencies:
   
   pip install pandas seaborn matplotlib scikit-learn
   
3. Upload the dataset and run the code in your Python environment or Jupyter Notebook.

 Technologies Used
- Python: Data analysis and recommendation system development.
- Pandas: Data manipulation and analysis.
- Seaborn & Matplotlib: Data visualization.
- Scikit-learn: Implementing cosine similarity for recommendations.


Author
Kavya Krishna  
Electronics and Computer Engineering Student | Aspiring Data Analyst
