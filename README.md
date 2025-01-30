# excel_file_reader

Recurring Payments and Spending Analysis

Overview:

This Jupyter Notebook reads data from an Excel file using openpyxl, processes recurring payments, and visualizes spending habits using pandas and matplotlib. The goal is to provide insights into recurring expenses and overall financial trends.

Features:

 - Reads data from an Excel file (.xlsx) using openpyxl

 - Identifies recurring payments and categorizes expenses

 - Uses pandas for data manipulation and aggregation

 - Generates visualizations of spending habits with matplotlib



Prerequisites:

Ensure you have the following dependencies installed in your Python environment:

pip install pandas openpyxl matplotlib jupyterlab



Usage:

Open the Jupyter Notebook.

Ensure the Excel file containing financial data is in the correct directory.


Example Excel Data File below:

![example excel file]([example_excel_data.png](https://github.com/CallumJones98/excel_file_reader/blob/15f24a4eb3907c614ea7a0036f23a47ccc708b39/example_excel_data.png))




Run the notebook cells to:

Load the data from the Excel file

Process data (in this instance a comparison for recurring payments)

Generate visualizations of spending trends


![example of analysis from file]([recurring_payment_example.png](https://github.com/CallumJones98/excel_file_reader/blob/15f24a4eb3907c614ea7a0036f23a47ccc708b39/recurring_payment_example.png))




The notebook generates various graphs, such as:

Bar Chart: Monthly spending per category

Pie Chart: Distribution of expenses

Line Graph: Trends in recurring payments

Example Graph:

![pie chart example of payment trends]([payment_graph.png](https://github.com/CallumJones98/excel_file_reader/blob/15f24a4eb3907c614ea7a0036f23a47ccc708b39/payment_graph.png)) 






You can modify the notebook to:

 - Use different date ranges

 - Change spending categories

 - Filter specific transactions
   

License:

This project is open-source under the MIT License.
