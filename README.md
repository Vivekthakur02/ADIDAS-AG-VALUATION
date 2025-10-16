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

EV} = Market Capitalisation + Total Debt - Cash & Cash Equivalents

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

### 🧾 Step-by-Step Process (Explained in Words)

1. **Start with EBIT (Earnings Before Interest and Tax):**
   This represents the company’s operating profit from its core business before paying any interest or tax.

2. **Adjust for Taxes:**
   Multiply EBIT by *(1 − Tax Rate)* to obtain the after-tax operating profit — the profit that actually remains with the company after government obligations.

3. **Add Back Depreciation:**
   Depreciation reduces accounting profit but does not involve any real cash outflow.
   Therefore, it is added back to reflect the true cash position.

4. **Subtract Capital Expenditure (CAPEX):**
   These are actual cash investments made in machinery, technology, buildings, or R&D.
   Since cash goes out of the company, it is subtracted.

5. **Adjust for Change in Working Capital:**

   * If working capital increases → cash gets tied up in operations → subtract it.
   * If working capital decreases → cash is released → add it.
     *(In our project, this change was assumed to be zero for simplicity.)*

6. **Final Result – FCFF:**
   The resulting figure after these adjustments represents the **Free Cash Flow to the Firm**,
   i.e., the cash flow available to all capital providers (both shareholders and lenders).


## 🧮 Step 4 — Weighted Average Cost of Capital (WACC) Calculation

### 🎯 Objective

To determine Adidas AG’s **average cost of capital** — i.e., the minimum return required by both **equity investors** and **debt holders**.
This rate is then used to **discount future Free Cash Flows (FCFF)** to their present value.

---

### ⚙️ Understanding WACC

> **WACC** represents the average rate a company must pay to finance its assets, considering both **debt** and **equity** sources.
> It tells us how expensive it is for Adidas to raise and use capital.

WACC = (E/V × Ke) + (D/V × Kd × (1 – Tax Rate))

Where:

* ( K_e ) = Cost of Equity
* ( K_d ) = Cost of Debt
* ( E/V ) = Proportion of Equity in total capital
* ( D/V ) = Proportion of Debt in total capital

---

### 📊 Input Summary

| Parameter                              | Description                        | Value  |
| -------------------------------------- | ---------------------------------- | ------ |
| **Tax Rate**                           | Corporate tax rate                 | 27.4%  |
| **Risk-free Rate (Rf)**                | German government bond yield       | 4.00%  |
| **Market Return (Rm)**                 | Average market return              | 8.50%  |
| **Market Risk Premium (Rp = Rm − Rf)** | Excess return over risk-free rate  | 4.50%  |
| **Beta (Asset)**                       | Business risk excluding leverage   | 1.11   |
| **Beta (Equity)**                      | Risk after accounting for leverage | 2.02   |
| **Cost of Equity (Ke)**                | ( 4% + 2.02 × 4.5% = 13.09% )      | 13.09% |
| **Cost of Debt (Kd)**                  | Average borrowing rate             | 5.98%  |
| **Debt-to-Value (D/V)**                | Debt portion in total capital      | 53.04% |
| **Equity-to-Value (E/V)**              | Equity portion in total capital    | 46.96% |

---

### 🧩 Stepwise Computation

1. **Calculate Cost of Equity (Ke)** using CAPM:
   [
   K_e = R_f + \beta_e (R_m - R_f) = 4 + 2.02 × 4.5 = 13.09%
   ]

2. **Calculate After-tax Cost of Debt (Kd):**
   [
   K_d = 5.98 × (1 - 0.274) = 4.34%
   ]

3. **Combine using capital structure weights:**
   [
   WACC = (0.4696 × 13.09) + (0.5304 × 5.98 × 0.726) = 8.45%
   ]

---

### Final Result

| Type              | WACC      |
| ----------------- | --------- |
| **Pre-Tax WACC**  | **9.32%** |
| **Post-Tax WACC** | **8.45%** |

---

## 🧩 Verification of FCFF Valuation (Your Table Explanation)

### 🔹 1️⃣ FCFF Row

**FCFF:** 2397518 | 2055383 | 1737864 | 1443313 | 1560430

➡️ These values represent the forecasted Free Cash Flow to Firm (FCFF) for 2024–2028, projected for the next 5 years (as discussed in Step 3).

These figures are in million €, and they show slight year-to-year variations — consistent with realistic growth assumptions. 

---

### 🔹 2️⃣ Enterprise Value Row (per year TV base)

**Enterprise Value:** 72953067 | 69479112 | 59564187 | 50362627 | 41826651

➡️ These are intermediate enterprise value projections derived from each year’s FCFF and discount factor.
Basically, they indicate each year’s discounted cash flow component and terminal-linked values.

---

### 🔹 3️⃣ Total Free Cash Flow (2024–2028)

**Total Free Cash Flow = 9194510**

➡️ The total FCFF for 2024–2028 equals approximately €9.19B.
This is the unadjusted (undiscounted) cash flow sum. 

---

### 🔹 4️⃣ DCF (Discounted Cash Flow)

**DCF:** 1598085 | 1485810 | 1362444 | 1227145 | 1438838

➡️ These are the same FCFFs, but now discounted at WACC = 8% (0.08).
Each year’s future cash flow is converted to its present value — known as the *present value of FCFFs*.

---

### 🔹 5️⃣ DCF 2024–2028 (total)

**DCF 2024–2028 = 7112324**

➡️ This represents the sum of all discounted FCFFs, i.e., the *present value* of forecast period (2024–2028) cash flows. 

---

### 🔹 6️⃣ Terminal Value Added
Terminal Value = the value of the company’s business after the forecast period, representing all future years in one number.

**Enterprise Value (2023) = 45220639.85**

➡️ Meaning:

* Discounted FCFFs (2024–2028) ≈ €7.11 billion
* Discounted Terminal Value ≈ €38.11 billion
* Added together → Total Enterprise Value ≈ €45.22 billion

---
















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
