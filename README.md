# 💸 Expense Tracker Pro

A clean, responsive, and fully client-side **Expense Tracker** web application built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies, no backend required.

---

## 🚀 Live Demo

Just open `Expense_.html` in any modern browser and start tracking!

---

## ✨ Features

- 📈 **Income & Expense Tracking** — Log transactions with a description, amount, category, and optional note
- 💰 **Real-time Balance Dashboard** — Instantly see your total balance, total income, total expenses, and transaction count
- 🌍 **Multi-Currency Support** — Switch between multiple global currencies (USD, PKR, EUR, GBP, and more) with symbol auto-update
- 🔍 **Search & Filter** — Search transactions by description, category, or note; filter by All / Income / Expenses
- 🗂️ **Category System** — Assign categories (Food, Transport, Shopping, Bills, etc.) to each transaction
- 🗑️ **Delete & Clear** — Remove individual transactions or clear all at once with confirmation prompts
- 💾 **Persistent Storage** — All data and currency preferences are saved to `localStorage` — your data survives page refreshes
- 📅 **Smart Date Formatting** — Displays "Today", "Yesterday", or a formatted date for each transaction
- 🎨 **Smooth Animations** — Fade-in animations and hover effects for a polished user experience
- 📱 **Responsive Design** — Works seamlessly on desktop, tablet, and mobile screens

---

## 🖥️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | App structure & layout |
| **CSS3** | Styling, gradients, animations, responsive grid |
| **Vanilla JavaScript** | App logic, DOM manipulation, localStorage |

No libraries. No frameworks. No internet connection required.

---

## 📁 Project Structure

```
Expense_.html      ← The entire application (single file)
README.md          ← Project documentation
```

---

## ⚙️ How to Use

1. **Clone or download** this repository
2. Open `Expense_.html` in your browser (double-click or drag into browser)
3. **Select your currency** from the dropdown at the top
4. **Add a transaction** by filling in the form on the left:
   - Choose Income or Expense
   - Enter a description and amount
   - Pick a category
   - Optionally add a note
   - Click ✅ **Add Transaction**
5. View your **live stats** update at the top
6. **Search or filter** your transactions on the right panel
7. **Delete** any transaction individually or use **Clear All** to reset

---

## 📸 UI Overview

| Section | Description |
|---|---|
| **Header** | App title and tagline |
| **Currency Selector** | Global currency switcher |
| **Stats Cards** | Balance, Income, Expenses, Count |
| **Add Transaction Form** | Input form for new entries |
| **Transaction History** | Searchable, filterable transaction list |
| **Footer** | Credits and copyright |

---

## 🔒 Privacy

All data is stored **locally in your browser** using `localStorage`. No data is ever sent to any server.

---

## 🛠️ Customization

You can easily extend the app by:
- Adding more categories in the `<select id="category">` dropdown
- Adding more currencies in the `<select id="currencySelector">` dropdown
- Tweaking colors by modifying the CSS gradient values

---

## 📄 License

This project is open-source and free to use for personal or educational purposes.

---

## 👤 Author

**Built by Syed Saif Ali**

© 2025 Saif Ali Shah. All rights reserved.
