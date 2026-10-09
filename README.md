Markdown
# 💼 WorkPulse HR - Attendance & Payroll Management System

**WorkPulse HR** is a modern, responsive single-page web application designed to streamline human resource workflows, employee attendance tracking, leave request management, and automated payroll calculations.

---

## 📌 Project Overview

Managing employee operations, attendance logs, and payroll deductions can be complex and error-prone. **WorkPulse HR** unifies administrative HR controls and self-service employee features into a clean, centralized portal.

The application includes real-time salary breakdown computations (tax, provident fund/PF, allowances, bonuses), interactive clock-in/out logging, leave balance tracking, dynamic visual analytics, and printable payslip generation.

---

## ✨ Core Features

### 👤 Dual-Role Interface
- **HR Admin Mode**: Access full employee directory, manage leave approvals, run monthly payroll processing, and view organization-wide attendance analytics.
- **Employee Mode**: Perform daily clock-in/out actions, view personal leave balances, submit leave applications, and view individual payslips.

### ⏱️ Attendance Management
- Real-time digital clock-in / clock-out simulation with attendance status auto-detection (Present, Late, Absent, On Leave).
- Manual attendance logging and daily status distribution counters.

### 🌴 Leave Management Engine
- Interactive leave application form with automatic total day calculation based on start and end dates.
- Visual leave quota balance progress meters (Casual Leave, Sick Leave, Earned Leave).
- Actionable leave request queue for HR approvals or rejections.

### 💰 Automated Payroll & Payslip Engine
- Automated deduction calculation model:
  - **PF (Provident Fund)**: 12% of basic base salary.
  - **Taxes**: Tiered progressive tax estimate based on gross income.
  - **Bonuses & Allowances**: Dynamic additions to calculate accurate Net Pay.
- One-click bulk payroll run for all active employees.
- Interactive payslip modal drawer with detailed itemized breakdown and printable layout.

### 📊 Reports & Visual Analytics
- Visual charts powered by **Chart.js**:
  - Monthly Attendance Rate Trends (Line Chart).
  - Departmental Salary Distribution (Doughnut Chart).

---

## 📂 File Structure

To run the application, ensure your workspace has the following structure:

```text
attendance-payroll-system/
├── index.html        # Main Web Application (HTML5, Tailwind CSS, JavaScript)
└── README.md         # Project documentation and setup guide
🛠️ Tech Stack & Dependencies
Structure & Logic: HTML5, ES6+ Vanilla JavaScript

Styling: Tailwind CSS (via CDN)

Icons: Font Awesome 6 (via CDN)

Data Visualization: Chart.js (via CDN)

🚀 How to Run Locally
Option 1: Direct File Launch
Clone or download this repository.

Open index.html directly in any modern web browser (Chrome, Firefox, Edge, Safari).

Option 2: Live Server in VS Code
Open Visual Studio Code and open the project directory.

Install the Live Server extension (ms-vscode.live-server).

Right-click index.html and click Open with Live Server.

📤 Push to GitHub (VS Code Terminal)
To push this project to GitHub from your VS Code terminal, execute:

Bash
# 1. Initialize git repository
git init

# 2. Stage all files
git add index.html README.md

# 3. Create initial commit
git commit -m "Add Attendance & Payroll System web application"

# 4. Rename main branch
git branch -M main

# 5. Link your GitHub repository (Replace with your actual repo URL)
git remote add origin [https://github.com/YOUR_USERNAME/attendance-payroll-system.git](https://github.com/YOUR_USERNAME/attendance-payroll-system.git)

# 6. Push code to GitHub
git push -u origin main
📄 License
This project is open-source and available under the MIT License.