<!-- Project Banner -->
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/20/Adidas_Logo.svg" alt="Adidas Logo" width="180"/>
</p>

<h1 align="center">🏢 Adidas Valuation — Step 1</h1>

<p align="center">
  <b>Comprehensive Valuation of Adidas AG using DCF-based Methods (FCFF, CCF, and ECF)</b><br>
  <i>Major Project by Vivek Thakur | IIT Kharagpur</i>
</p>

---

## 📘 Project Overview
This repository contains the financial valuation of **Adidas AG**, one of the world’s largest sportswear companies.  
The objective is to estimate the company’s **Enterprise Value (EV)** and derive its **fair stock price** using  
different discounted cash flow (DCF) approaches.

This README currently covers **Step 1: Objective & Basic Understanding**.  
Subsequent steps (like FCFF, WACC, and final valuation) will be added later as updates.

---

## 🎯 Step 1 — Objective & Basic Understanding

### 🧭 Project Objective
To determine the **true value of Adidas AG** by calculating its **Enterprise Value (EV)** and comparing it with  
the company’s **market value**, helping to identify whether the stock is **undervalued or overvalued**.

---

### 💡 What Is Enterprise Value (EV)?
EV represents the **total worth of a company**, including both shareholders’ and debt-holders’ interests.  
It’s the price one would effectively pay to acquire the entire company.

\[
\text{EV} = \text{Market Capitalisation} + \text{Total Debt} - \text{Cash \& Cash Equivalents}
\]

- **Market Cap** = Share price × Number of shares  
- **Total Debt** = Short-term + Long-term debt  
- **Cash & Equivalents** = Company’s liquid funds  

EV gives a **complete picture** of a company’s value — not just what shareholders own,  
but also what lenders are owed.

---

### 🧮 Valuation Methods Used
This project uses three complementary DCF-based valuation approaches:

| Method | Meaning (Simplified) | Focus |
|:--|:--|:--|
| **FCFF** | Free Cash Flow to Firm – cash available to all investors before paying interest | Measures total firm value |
| **CCF** | Capital Cash Flow – variation considering both equity & debt cash flows | Adjusts for tax shields |
| **ECF** | Equity Cash Flow – cash available to equity holders after paying interest & debt | Focuses on shareholder value |

All three methods ultimately lead to an estimated **Enterprise Value** and implied **fair stock price**.

---

## 🧩 Step 2 — Free Cash Flow to Firm (FCFF)

### 💡 Concept

Free Cash Flow to Firm (FCFF) represents the **cash generated from operations that is available to all providers of capital** — both debt and equity holders.
It tells us how much cash the business truly produces after paying for its regular operations and investments in assets.

---

### 🧾 Formula

FCFF} = EBIT*(1 - Tax Rate) + Depreciation - CAPEX - ΔWorking Capital 

---

### 🔍 Step-by-Step Explanation

1. **EBIT (Earnings Before Interest and Tax)**
   Operating profit before financing and tax expenses. Taken directly from the income statement.

2. **(1 − Tax Rate)**
   Adjusts EBIT for taxes to find after-tax operating income.
   → In our model, the effective tax rate used = **27.4 %**

3. **+ Depreciation**
   Non-cash accounting expense added back since it doesn’t reduce cash.

4. **− CAPEX (Capital Expenditure)**
   Cash spent on new plants, machinery, or technology. This is an actual cash outflow.

5. **− Δ Working Capital**
   Measures additional cash locked in day-to-day operations.
   In our project, **change in working capital = 0** was assumed for simplicity.

---

### 🧮 Illustrative Computation (Adidas 2023)

| Item              | Note             |
| ----------------- | ---------------- |
| EBIT              | Operating profit |
| Tax rate          | 27.4 % Given     |
| EBIT after tax    | calculated       |
| Depreciation      | Added back       |
| CAPEX             | Subtracted       |
| Δ Working Capital | Assumed 0        |

---

FCFF(2024) = 1560430.19M
WACC = 0.08
Enterprise Value(2023) = 45220639.85

---

### 📊 Key Inputs Required
Before proceeding to valuation, the following data points are collected:

- **Financial Statements:** Revenue, EBITDA, EBIT, Net Income  
- **Depreciation & Amortisation**  
- **Capital Expenditure (CAPEX)**  
- **Change in Working Capital** (assumed zero in this project)  
- **Total Debt & Cash Balance**  
- **Tax Rate:** 27.4 %  
- **Interest Rate:** 2.48 %  
- **Discount Rate (WACC):** to be calculated later  
- **Shares Outstanding** & any **Buybacks**

---

## 🗂️ Repository Files
| File | Description |
|:--|:--|
| `Adidas_Major_Project.xlsx` | Main financial model and valuation calculations |
| `Copy of MAJOR PROJECT.pdf` | Detailed project report |
| `Copy of MAJOR PROJECT.pptx` | Presentation slides |
| `README.md` | Documentation for Step 1 (current file) |

---

## 👤 Author
**Vivek Thakur**  
📍 IIT Kharagpur | Economics & Finance Major  
💬 *“Turning numbers into stories — valuing businesses beyond the balance sheet.”*

---

<p align="center">
  <b>🔜 Next Step → Step 2: Calculating Free Cash Flow to Firm (FCFF)</b><br>
  <i>(To be added in the next update)</i>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Project-DCF%20Valuation-blue?style=for-the-badge" alt="DCF Badge"/>
  <img src="https://img.shields.io/badge/Language-English-lightgrey?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-Finance%20%26%20Valuation-green?style=for-the-badge"/>
</p>




tep 2 will explain how to compute *Free Cash Flow to Firm (FCFF)* using Adidas’s financial data.
