# Python Personal Finance Tracker with Data Visualization

## Overview

This project is a personal finance tracker built entirely in Python, utilizing the power of Pandas for data manipulation and Matplotlib/Seaborn for creating insightful visualizations. It allows users to log income and expense transactions, categorize them, and gain a clear understanding of their financial health through various charts.

**Note:** This project was developed with step-by-step guidance from **Google's Gemini AI**. Leveraging AI tools in the learning process significantly accelerated understanding of concepts and best practices in data handling and visualization.

## Features

* **Transaction Logging:** Easily add new income or expense transactions with details like date, type, category, description, and amount.
* **Persistent Storage:** All transactions are saved to and loaded from a `transactions.csv` file, ensuring your financial history is preserved across sessions.
* **Data Cleaning & Preparation:** Automated data type conversion (dates to datetime, amounts to numeric) and chronological sorting for accurate analysis.
* **Insightful Visualizations:**
    * **Expense Distribution Pie Chart:** See a clear breakdown of where your money is going by category.
    * **Monthly Income vs. Expenses Bar Chart:** Compare your cash flow month-by-month.
    * **Cumulative Balance Line Graph:** Track your overall financial balance trend over time.

## Technologies Used

* **Python:** The core programming language.
* **Pandas:** For powerful data manipulation and analysis.
* **Matplotlib:** For creating static, animated, and interactive visualizations.
* **Seaborn:** Built on Matplotlib, providing a high-level interface for drawing attractive statistical graphics.
* **Google Colaboratory (Colab):** Used as the development environment, offering free access to computing resources and easy sharing.
* **CSV (Comma Separated Values):** Simple file format for persistent data storage.

## How to Use/Run This Project

1.  **Clone the Repository (Optional):** You can clone this repository to your local machine using `git clone https://github.com/Dinu-Sreekumar/Python-Finance-Tracker.git` or simply download the `.zip` file.
2.  **Open in Google Colab:** The easiest way to run this project is directly in Google Colab.
    * Go to `colab.research.google.com`.
    * Click `File` > `Open notebook`.
    * Go to the `GitHub` tab.
    * Enter this repository URL: `https://github.com/Dinu-Sreekumar/Python-Finance-Tracker` and press Enter.
    * Select `Personal_Finance_Tracker.ipynb` to open it.
3.  **Mount Google Drive:** In the Colab notebook, run the first code cell to mount your Google Drive. This is crucial for accessing the `transactions.csv` file. Follow the on-screen prompts for authorization.
4.  **Data File:** Ensure you have a `transactions.csv` file in your Google Drive at the path `/content/drive/My Drive/Colab Notebooks/FinanceTracker/transactions.csv`. The repository includes a sample `transactions.csv` with rich data for demonstration. You can use this directly or replace it with your own data.
5.  **Run Cells:** Execute each code cell sequentially (using Shift + Enter) to load data, add new transactions, clean data, and generate the visualizations.
6.  **Add Your Own Transactions:** Modify the `add_transaction` calls in Step 3 of the notebook to input your personal financial data. Remember to re-run the `to_csv()` command to save changes.

## Project Screenshots

![Expense Distribution Pie Chart](https://github.com/Dinu-Sreekumar/Python-Finance-Tracker/blob/main/screenshots/expense_pie_chart.png?raw=true)

![Monthly Income vs. Expenses Bar Chart](https://github.com/Dinu-Sreekumar/Python-Finance-Tracker/blob/main/screenshots/monthly_summary_bar_chart.png?raw=true)

![Cumulative Balance Over Time Line Graph](https://github.com/Dinu-Sreekumar/Python-Finance-Tracker/blob/main/screenshots/cumulative_balance_line_graph.png?raw=true)

## Future Enhancements (Ideas for further development)

* Implement a simple command-line interface (CLI) for easier transaction input.
* Add functionality for setting and tracking budgets.
* Integrate with a small local database (e.g., SQLite) instead of a CSV file for more robust data management.
* Develop more advanced financial metrics (e.g., savings rate, debt-to-income ratio).
* Explore interactive visualization libraries like Plotly or Bokeh.

## Author

Dinu Sreekumar
www.linkedin.com/in/dinu-sreekumar
