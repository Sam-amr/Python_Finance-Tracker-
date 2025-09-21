# Finance Tracker Using Python

## Description 
It is a user-friendly Streamlit application to analyze, categorize, and visualize personal finance transactions from CSV files. This dashboard helps you understand your expenses and payments, organize transaction categories, and gain actionable insights from your financial data.

## Overview 
Managing personal finances can be challenging without proper tools. This project provides a simple, interactive platform to:

1. Upload bank or finance CSV files.

2. Automatically categorize transactions based on user-defined keywords.

3. Edit and assign categories to transactions.

4. Visualize expenses using pie charts.

5. Summarize payments and expenses effectively.

6. Built using Python, Streamlit, Pandas, and Plotly, the app is lightweight and runs locally without complex setup.

## Technologies Used:

Python: Main programming language.

Streamlit: For creating the interactive web dashboard.

Pandas: For handling and processing CSV data.

Plotly Express: For interactive visualizations.

JSON: To store user-defined categories and keywords.

## Details of the Project

### 1. CSV Upload & Data Handling: -

Users can upload a CSV file containing transactions.

The app automatically reads the file and converts string values into usable formats (e.g., converting amount to numbers, date to proper datetime).

Handles errors in case the file is invalid or formatted incorrectly.

### 2. Automatic Transaction Categorization:- 

Transactions are initially set as “Uncategorized.”

Users can define categories and associate keywords with each category.

The app automatically classifies transactions based on these keywords.

### 3. Dynamic Category Management: -

Users can add new categories at any time.

Keywords are automatically stored for future use.

Prevents duplicate keywords and ensures consistent categorization.

### 4. Expense Analysis: - 

The app displays all expenses (debits) in a table.

Users can edit categories directly in the app using a data editor.

Shows a summary table with total amounts spent per category.

Visualizes spending using interactive pie charts to easily identify major expense areas.

### 5. Payment Analysis: - 

A separate tab displays payments or credits.

Shows the total payments as a large metric.

Provides a table of all credit transactions for detailed analysis.

### 6. Session State Support: -

All user edits, categories, and keyword changes are stored in session state.

Ensures that changes persist across app usage without losing progress.

## How It Works:

1. Upload File: The user uploads a CSV file with columns like Date, Details, Amount, and Debit/Credit.

2. Data Cleaning: The app cleans and converts the data into proper formats.

3. Categorization: Transactions are automatically categorized based on keywords.

4. Editing: Users can edit categories or assign new ones using the interactive table.

5. Visualization: Expenses are summarized by category and displayed in a pie chart.

6. Payment Summary: Payments are summarized separately with total amounts shown.

## Key Insights

1. Visualizes spending patterns clearly.

2. Helps identify major expense categories.

3. Automatically classifies recurring transactions for time-saving.

4. Keeps a record of user-defined keywords for better future categorization.

## Conclusion

The Simple Finance Dashboard is a beginner-friendly finance management tool with an emphasis on ease of use, interactivity, and data visualization. It allows users to understand their spending habits, manage categories efficiently, and gain actionable insights from their financial data.

## Author 

Shrawani M. Amrutkar

https://github.com/Sam-amr
