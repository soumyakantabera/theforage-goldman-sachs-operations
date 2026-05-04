# Goldman Sachs Operations Virtual Experience Program

<p>
  <img src="https://img.shields.io/badge/Program-Goldman%20Sachs%20Operations-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-The%20Forage-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

---

## 📋 Table of Contents

- [Overview](#overview)
- [Task 1: Controllers Division – Semester Budget Exercise](#task-1-controllers-division--semester-budget-exercise)
  - [What You'll Learn](#what-youll-learn)
  - [What You'll Do](#what-youll-do)
  - [Deliverables](#deliverables)
- [Task 2: Asset & Wealth Management – Fund NAV Calculation](#task-2-asset--wealth-management--fund-nav-calculation)
  - [What You'll Learn](#what-youll-learn-1)
  - [What You'll Do](#what-youll-do-1)
  - [Deliverables](#deliverables-1)
- [Repository Structure](#repository-structure)
- [How to Use This Repository](#how-to-use-this-repository)
- [Author](#author)

---

## Overview
This repository contains the deliverables from the Goldman Sachs Operations Virtual Experience Program, focusing on two key areas within the firm:

- **Part 1: Controllers Division** – Financial management, budgeting, and the role of Controllers in regulatory compliance and risk management.
- **Part 2: Asset & Wealth Management (AWM)** – Net Asset Value (NAV) calculation, financial reporting accuracy, and fund valuation.

The program simulates real-world tasks performed by Analysts at Goldman Sachs, emphasizing analytical skills, attention to detail, and the importance of accurate financial reporting.

---

## Task 1: Controllers Division – Semester Budget Exercise

### What You'll Learn
- The structure and key functions of Controllers at Goldman Sachs
- Key concepts, definitions, and regulatory frameworks (e.g., financial reporting standards, compliance requirements)
- Practical applications for financial analysts in personal and professional contexts

### What You'll Do
- Develop an understanding of the Analyst role within Controllers
- Apply key financial management skills (budgeting, expense tracking, resource allocation) to everyday life as a student
- Create a balanced personal semester budget, mirroring the financial oversight performed by Controllers

### Deliverables
- **Input**: `task1/input/Task 1_Semester Budget.xlsx` – Blank template with income/expense categories for a single semester
- **Output**: `task1/output/My_Semester_Budget.xlsx` – Completed balanced budget ($15,450 total income = total expenses) with:
  - Detailed income sources (salary, parents, loans, scholarships, grants, savings)
  - Categorized expenses (Home & School, Transportation, Daily Living, Entertainment, Health)
  - Formulas for automatic totals and variance tracking
  - Planning notes for ongoing expense monitoring using apps like Mint or YNAB
  - Professional formatting (blue input text, currency formatting, Aptos Narrow font)

**Key Skills Demonstrated**: Financial planning, variance analysis, formula-driven spreadsheets, personal resource allocation – directly transferable to Controller responsibilities like budget vs. actual reporting and regulatory compliance.

---

## Task 2: Asset & Wealth Management – Fund NAV Calculation

### What You'll Learn
- Development of analytical skills crucial for calculating Net Asset Valuation (NAV) for funds
- Importance of financial reporting and valuation accuracy within Asset and Wealth Management (AWM)
- Regulatory and compliance considerations in fund valuation

### What You'll Do
- Analyze provided financial data for the West Street Fund (Class A and Class C shares)
- Calculate History-to-Date amounts and Per-Unit (NAV) values
- Compute Total Assets, Total Liabilities, and Net Asset Value ensuring accuracy and integrity
- Demonstrate understanding of unitization methodology for investor reporting ($10,000 benchmark commitment)

### Deliverables
- **Input**: `task2/input/West Street Fund Data (11.7).xlsx` – Raw fund data with Opening Balances, Quarter-to-Date activity for Contributions, Distributions, Management Fees, and Net Income
- **Output**: `task2/output/West_Street_Fund_Data_Completed.xlsx` – Fully calculated workbook with:
  - History-to-Date formulas (Opening + QTD)
  - Unitized Per-Unit values using formula: `(History-to-Date / 100,000 shares) × $10,000`
  - Total Assets = Contributions Per Unit + Net Income Per Unit
  - Total Liabilities = Distributions Per Unit – Management Fees Paid Per Unit
  - NAV (Net Asset Value) = Total Assets Per Unit – Total Liabilities Per Unit
    - **Class A NAV: $12,121**
    - **Class C NAV: $11,469**
  - All calculations use dynamic Excel formulas (24 formulas, zero errors)
  - Professional formatting matching Goldman Sachs financial modeling standards

**Key Skills Demonstrated**: NAV computation, fund accounting, data integrity validation, formula-based financial modeling – core to AWM valuation and reporting processes.

---

## Repository Structure
```
Goldman_Sachs_Virtual_Experience/
├── README.md
├── docs/
│   └── Goldman_Sachs_Virtual_Experience_Summary.docx
├── task1/
│   ├── input/
│   │   └── Task 1_Semester Budget.xlsx
│   └── output/
│       └── My_Semester_Budget.xlsx
└── task2/
    ├── input/
    │   └── West Street Fund Data (11.7).xlsx
    └── output/
        └── West_Street_Fund_Data_Completed.xlsx
```

---

## How to Use This Repository
1. Clone or download the repository.
2. Review the README for context on each task.
3. Open the input files to understand the starting data/templates.
4. Examine the output files to see completed work with formulas and results.
5. Open the summary document in `docs/` for a consolidated professional report.
6. (Optional) Re-run calculations in Excel to verify formulas update dynamically.

This virtual experience highlights the precision, analytical rigor, and client-focused mindset required at Goldman Sachs across Controllers and AWM divisions.

---

## Author
Completed as part of Goldman Sachs Operations Virtual Experience Program – April 2026

*Note: This is a simulated educational exercise. All data and calculations are for learning purposes only.*
