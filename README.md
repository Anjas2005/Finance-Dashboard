# 💰 Personal Finance Management Dashboard

A simple, interactive personal finance dashboard built with **Streamlit** to help you **categorize, analyze, and visualize** your financial transactions without manually editing Excel sheets every month.

If you’re tired of repeatedly tagging the same expenses and struggling to make sense of raw CSVs, this tool fixes that.

---

## 🚀 What This Project Solves

- Manual expense categorization in Excel is repetitive and error-prone
- Financial data is hard to visualize without extra effort
- Same vendors appear every month but still need manual tagging

This dashboard:
- Learns from your categorizations
- Automatically categorizes future transactions
- Gives instant visual insights into spending and income

---

## 🧠 How It Works (High-Level)

1. Upload your **bank transaction CSV**
2. The app:
   - Parses dates and amounts
   - Separates **Debits (Expenses)** and **Credits (Payments)**
   - Auto-categorizes transactions using saved keywords
3. You can:
   - Edit categories inline
   - Add new categories
   - Persist categorization logic across sessions
4. Visual summaries update instantly

All category rules are stored locally in a JSON file.

---

## ✨ Key Features

- 📂 CSV upload support
- 🧾 Automatic transaction categorization
- ✏️ Editable categories with persistence
- 📊 Expense summary table
- 🥧 Interactive pie chart (Plotly)
- 💾 Category memory using `categories.json`
- 💳 Separate views for Debits and Credits

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **Plotly**
- **JSON (local persistence)**

---

## 📁 Project Structure

```text
├── app.py                 # Main Streamlit application
├── categories.json        # Persistent category-keyword mapping
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

https://github.com/user-attachments/assets/5a97da02-6abe-4c6e-83c3-f524f160675a

