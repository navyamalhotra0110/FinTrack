## 💎 FinTrack

**Student Personal Finance Manager**

A Gen-Z designed, portfolio-ready personal finance web app built for students to track expenses, manage budgets, set savings goals, and learn investing basics — all without any backend or signup.

## 📌 About The Project
Many students receive pocket money, scholarships, or part-time income but struggle to track where their money goes. FinTrack solves this with a sleek, fully browser-based finance manager — no signup, no server, no cost.
Built as a college project with production-level UI/UX, FinTrack demonstrates real-world skills in vanilla JavaScript DOM manipulation, LocalStorage data persistence, Chart.js data visualization, CSS animations, and responsive design.

## ✨ Features
- **Personalized Onboarding**

First-visit welcome screen with name, avatar selection, college, income source & monthly budget setup
Personalized greeting on dashboard ("Good Morning,[your name]")
Edit profile anytime from the navbar

- **Live Dashboard**

Animated count-up stat cards: budget, spent, remaining, income, estimated savings
Real-time donut chart showing spending distribution across categories
Per-category progress bars with over-budget warnings
Quick-add expense form directly on the dashboard
Recent transactions table with one-click delete

- **Expense Tracker**

Add expenses with description, amount, category, and date
6 categories: Food 🍔, Travel 🚌, Books 📚, Entertainment 🎮, Stationery ✏️, Other 📦
Filter by category, sort by date/amount, live search
Per-category monthly summary cards
Full delete functionality with instant UI update

- **Budget Planner**

Set total monthly budget with a single input
Editable per-category budget limits (inline input fields)
Animated progress bars with colour-coded warnings (green → yellow → red)
Over-budget alerts per category
Built-in budgeting tips (50/30/20 rule, etc.)

- **Savings Goals**

Create goals with custom name, emoji, target amount, deadline & colour theme
Animated progress bars per goal
Add-to-goal feature to incrementally save toward targets
Countdown showing days remaining until deadline
Completion celebration toast when a goal is reached

- **Monthly Reports**

Month selector for historical analysis (last 6 months)
Pie/donut chart for category breakdown
6-month grouped bar chart: Income vs Expenses
Savings trend line chart
Category breakdown table with percentage of total spending
Full transaction list for the selected period

- **Invest & Learn**

Deep-dive cards on Mutual Funds, SIP, Fixed Deposits, Stocks, PPF, and Digital Gold
Embedded YouTube learning videos
Live SIP Calculator with slider — calculates invested amount, returns earned, and final corpus in real time
Curated tips for student investors

- **Profile & Data Management**

Edit profile from any page via the navbar
Reset Data — clears all financial records, keeps profile
Full Reset — wipes everything, restarts onboarding
Both resets have a confirmation modal to prevent accidents

## 🛠️ Tech Stack
- **HTML5:** Semantic page structure across 7 pages
- **CSS3:** Custom design system, animations, transitions, responsive layout
- **JavaScript (ES6):** All app logic, DOM API, event handling, state management
- **LocalStorage API:** Persistent data storage — no backend required
- **Chart.js:** Donut, bar, line, and pie charts with animations
- **Canvas API:** Floating particle background effect
- **Google Fonts:** Syne + Plus Jakarta Sans typography

## 📂 Project Structure
```

fintrack/
│
├── index.html          # 🏠 Landing page — hero, features, CTA
├── dashboard.html      # 📊 Main dashboard with stats & charts
├── expenses.html       # 💸 Expense tracker with filters & search
├── budget.html         # 🎯 Budget planner with category limits
├── savings.html        # 🏦 Savings goals tracker
├── reports.html        # 📈 Monthly analytics & reports
├── learn.html          # 🧠 Investment education & SIP calculator
│
├── styles.css          # 🎨 Complete design system (single CSS file)
└── app.js              # ⚙️ All application logic (single JS file)

```
## 🚀 Getting Started
No installation, no build tools, no dependencies to install. Just clone and open.
Prerequisites

Any modern web browser (Chrome, Firefox, Edge, Safari)
That's it!

## 👩‍💻 Author

**Navya** 
2nd Year B.Tech CSE (AI & ML) Student · Chitkara University, Punjab
Microsoft Certified: Azure AI Fundamentals

## 📄 License
This project is licensed under the MIT License — free to use, modify, and distribute with attribution.

