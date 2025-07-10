# 💼 Budget Tracker

A simple web app built with **Streamlit** to track income, expenses, savings, and visualize your financial data.

## 🚀 Features

- Upload and parse your monthly transactions
- Filter by month and category
- View key metrics: total income, expenses, and net savings
- Line chart for monthly expense trends
- Bar and pie charts for category-wise expense breakdown
- View raw transaction data
- Bonus: Potential savings analysis (via utils)

## 📊 Technologies Used

- Python 🐍
- Streamlit 📈
- Pandas 🧮
- Matplotlib & Seaborn 🎨

## 🧾 How to Run Locally

```bash
git clone https://github.com/bansalch/budget_tracker.git
cd budget_tracker
python -m venv venv
venv\Scripts\activate  # On Windows
pip install -r requirements.txt
streamlit run app/dashboard.py

