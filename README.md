# 🪽 The Little Wings Play School — Preschool Management System ERP

Complete Functional ERP and Administration System for **The Little Wings Play School**. Built according to full functional specifications covering **Students**, **Academics**, **Staff**, **Attendance**, **Fees & Payments**, **Payroll**, **Expenses**, and **15 Core System Reports**.

## 🌟 Key Features

- 👑 **Multi-Role RBAC Support**: Instant live role switching between **Admin**, **HOD (Pre-K / Kindergarten)**, and **Teacher**.
- 👶 **Student & Parent Directory**: Complete student profiles, emergency contacts, medical notes, and authorized pickup instructions.
- 📋 **Class Attendance Register**: Real-time daily student marking (Present, Absent, Leave, Half Day) with batch actions.
- 💰 **Fees & Automated Invoicing**: Payment collection history, overdue fee tracking, and printable PDF/paper fee receipts.
- 💼 **Staff Payroll Engine**: Formula-based calculation (`Basic Salary + Allowances + Overtime − Advances − Deductions = Net Salary`) with financial privacy controls.
- 📊 **Expenditure Logger**: Categorized school expense tracking (Rent, Toys, Food/Snacks, Electricity, Maintenance, Stationery).
- 📈 **Financial Dashboard**: Income vs Expense charts, monthly trends, and net balance indicators.
- 📁 **15 Filterable System Reports**: Exportable to CSV / printable preview.

---

## 🚀 Quick Start (Standalone Dashboard)

1. Clone the repository:
   ```bash
   git clone https://github.com/TheLittleWingsPlayschool/the_little_wings_dashboard.git
   cd the_little_wings_dashboard
   ```

2. Open `index.html` directly in any browser (Chrome, Edge, Firefox, Safari) — no build step required!

---

## 🛠️ Full-Stack Backend & API Setup

To run with the optional Node.js + Express + SQLite backend:

```bash
npm install
npm run server
```
- Backend API running at `http://localhost:5000`
- Dashboard running at `http://localhost:3000`

---

## 👥 Pre-Configured Users (Hardcoded Roster)

| Role | User Name | Scope / Permissions |
| :--- | :--- | :--- |
| **Admin** | Mr. Rajesh Sharma | Full System Access & Financial Authority |
| **HOD** | Mrs. Priya Verma | Playgroup & Nursery Operations (No Salary Numbers) |
| **HOD** | Mrs. Sunita Rao | LKG & UKG Curriculum (No Salary Numbers) |
| **Teacher** | Ms. Sarah Johnson | Lead Teacher — Nursery Section A |
| **Teacher** | Ms. Ananya Sen | Lead Teacher — LKG Section B |
