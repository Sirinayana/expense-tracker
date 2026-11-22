# 💰 ExpenseFlow – Personal Expense Tracker

A modern, responsive personal finance dashboard built with **React.js** that helps users manage income, track expenses, monitor their balance, set a monthly budget, and visualize spending by category.

## ✨ Features

- **Dashboard Overview** – View total income, total expenses, and available balance.
- **Add Transactions** – Record income and expenses with a description, amount, category, and date.
- **Transaction Management** – View and delete transactions.
- **Search Transactions** – Search transactions by description or category.
- **Filter Transactions** – Filter records by all transactions, income, or expenses.
- **Monthly Budget Tracking** – Set a monthly budget and monitor spending with a progress bar.
- **Expense Analytics** – Visualize category-wise spending through a donut chart.
- **Persistent Storage** – Transactions and budget are saved in LocalStorage and remain after page refresh.
- **Responsive UI** – Clean dashboard layout designed for usability.

## 🛠️ Tech Stack

- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Vite
- Lucide React
- Browser LocalStorage

## 📂 Project Structure

```text
expense-tracker-react/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── App.css
    ├── index.css
    ├── pages/
    │   └── Dashboard.jsx
    └── components/
        ├── Sidebar.jsx
        ├── Header.jsx
        ├── SummaryCards.jsx
        ├── ExpenseForm.jsx
        ├── TransactionList.jsx
        ├── BudgetCard.jsx
        └── ExpenseChart.jsx
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/expense-tracker-react.git
```

### 2. Navigate to the project folder

```bash
cd expense-tracker-react
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

### 5. Open in browser

Open the local URL provided by Vite, usually:

```text
http://localhost:5173
```

## 📊 How It Works

- React `useState` manages transactions, budget, search, filters, and navigation.
- React `useEffect` saves transactions and budget changes to LocalStorage.
- React `useMemo` optimizes the filtered and sorted transaction list.
- JavaScript `filter()` and `reduce()` calculate income, expenses, balance, and category totals.
- CSS `conic-gradient()` generates the category spending donut chart.

## 💾 Data Storage

This project uses browser **LocalStorage** to store transaction history and the monthly budget.

No backend server or external database is required. Data is stored locally in the browser.

## 🔮 Future Improvements

- Backend integration using Django or FastAPI.
- Database integration using MySQL or PostgreSQL.
- User authentication and individual accounts.
- Monthly and yearly financial reports.
- Category-specific budget limits.
- Export transactions to CSV.


---

⭐ If you find this project useful, feel free to explore or improve it.
