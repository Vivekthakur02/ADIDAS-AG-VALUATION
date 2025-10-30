<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/20/Adidas_Logo.svg" alt="Adidas Logo" width="180"/>
</p>

<h1 align="center">🏢 Adidas Valuation </h1>

<p align="center">
  <b>Comprehensive Valuation of Adidas AG using DCF-based Methods (FCFF, CCF, and ECF)</b><br>
  <i>Major Project by Vivek Thakur | IIT Kharagpur</i>
</p>

---

##  Project Overview
This repository contains the financial valuation of **Adidas AG**, one of the world’s largest sportswear companies.  
The objective is to estimate the company’s **Enterprise Value (EV)** and derive its **fair stock price** using  
different discounted cash flow (DCF) approaches.

This README currently covers **Step 1: Objective & Basic Understanding**.  
Subsequent steps (like FCFF, WACC, and final valuation) will be added later as updates.
Canva link: https://www.canva.com/design/DAGBodMupWU/AAZ-W5qio8MaYhGXVLchTw/edit?utm_content=DAGBodMupWU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

---

##  Objective & Basic Understanding

###  Project Objective
To determine the **true value of Adidas AG** by calculating its **Enterprise Value (EV)** and comparing it with  
the company’s **market value**, helping to identify whether the stock is **undervalued or overvalued**.

---

###  What Is Enterprise Value (EV)?
EV represents the **total worth of a company**, including both shareholders’ and debt-holders’ interests.  
It’s the price one would effectively pay to acquire the entire company.

EV} = Market Capitalisation + Total Debt - Cash & Cash Equivalents

- **Market Cap** = Share price × Number of shares  
- **Total Debt** = Short-term + Long-term debt  
- **Cash & Equivalents** = Company’s liquid funds  

EV gives a **complete picture** of a company’s value — not just what shareholders own,  
but also what lenders are owed.

---

###  Valuation Methods Used
This project uses three complementary DCF-based valuation approaches:

| Method | Meaning (Simplified) | Focus |
|:--|:--|:--|
| **FCFF** | Free Cash Flow to Firm – cash available to all investors before paying interest | Measures total firm value |
| **CCF** | Capital Cash Flow – variation considering both equity & debt cash flows | Adjusts for tax shields |
| **ECF** | Equity Cash Flow – cash available to equity holders after paying interest & debt | Focuses on shareholder value |

All three methods ultimately lead to an estimated **Enterprise Value** and implied **fair stock price**.

---

#  Method 1: Free Cash Flow to Firm (FCFF)

### 💡 Concept

Free Cash Flow to Firm (FCFF) represents the **cash generated from operations that is available to all providers of capital** — both debt and equity holders.
It tells us how much cash the business truly produces after paying for its regular operations and investments in assets.

---

###  Formula

FCFF = EBIT*(1 - Tax Rate) + Depreciation - CAPEX - ΔWorking Capital 

---

###  Step-by-Step Explanation

###  Illustrative Computation (Adidas 2023)

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
##   Weighted Average Cost of Capital (WACC) Calculation

###  Objective

To determine Adidas AG’s **average cost of capital** — i.e., the minimum return required by both **equity investors** and **debt holders**.
This rate is then used to **discount future Free Cash Flows (FCFF)** to their present value.

---

###  Understanding WACC

> **WACC** represents the average rate a company must pay to finance its assets, considering both **debt** and **equity** sources.
> It tells us how expensive it is for Adidas to raise and use capital.

WACC = E/V × Ke + D/V × Kd × (1 – Tax Rate)

Where:

* K_e = Cost of Equity
* K_d = Cost of Debt
* E/V = Proportion of Equity in total capital
* D/V = Proportion of Debt in total capital

---

###  Input Summary

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

###  Stepwise Computation

1. **Calculate Cost of Equity (Ke)** using CAPM:
   
   K_e = R_f + beta_e (R_m - R_f) = 4 + 2.02 × 4.5 = 13.09%
   

2. **Calculate After-tax Cost of Debt (Kd):**
   
   K_d = 5.98 × (1 - 0.274) = 4.34%
   

3. **Combine using capital structure weights:**
   
   WACC = (0.4696 × 13.09) + (0.5304 × 5.98 × 0.726) = 8.45%
   

---

### Final Result

| Type              | WACC      |
| ----------------- | --------- |
| **Pre-Tax WACC**  | **9.32%** |
| **Post-Tax WACC** | **8.45%** |

---

##  Verification of FCFF Valuation 
Top row: forecast of the yearly cash the business generates.
DCF row: those yearly amounts converted to today’s money using your WACC.
DCF 2024–2028 = present value of the forecast window.
Then you compute a Terminal Value (value of all future cash beyond the forecast) using the last-year FCFF and a perpetuity growth assumption, discount it to today, and add it to the DCF sum. That final sum is Enterprise Value.

###  1️⃣ FCFF Row

**FCFF:** 2397518 | 2055383 | 1737864 | 1443313 | 1560430

➡️ These values represent the forecasted Free Cash Flow to Firm (FCFF) for 2024–2028, projected for the next 5 years (as discussed in Step 3).

These figures are in million €, and they show slight year-to-year variations — consistent with realistic growth assumptions. 

---

###  2️⃣ Enterprise Value Row (per year TV base)

**Enterprise Value:** 72953067 | 69479112 | 59564187 | 50362627 | 41826651

➡️ These are intermediate enterprise value projections derived from each year’s FCFF and discount factor.
Basically, they indicate each year’s discounted cash flow component and terminal-linked values.

---

###  3️⃣ Total Free Cash Flow (2024–2028)

**Total Free Cash Flow = 9194510**
➡️ The total FCFF for 2024–2028 equals approximately €9.19B.
This is the unadjusted (undiscounted) cash flow sum. 

---

###  4️⃣ DCF (Discounted Cash Flow) 
       _We discount FCFF by WACC_

**DCF:** 1598085 | 1485810 | 1362444 | 1227145 | 1438838

➡️ These are the same FCFFs, but now discounted at WACC = 8% (0.08).
Each year’s future cash flow is converted to its present value — known as the *present value of FCFFs*.

---

###  5️⃣ DCF 2024–2028 (total)

**DCF 2024–2028 = 7112324**

This represents the sum of all discounted FCFFs, i.e., the *present value* of forecast period (2024–2028) cash flows. 

---
###  6️⃣ Terminal Value Added
Terminal Value = the value of the company’s business after the forecast period, representing all future years in one number.
Terminal Value (TV)= **(FCFF of last year​×(1+g)) ​/ (WACC−g)**

EV = PV(FCFFs)
**Enterprise Value (2023) = 45220639.85**

➡️ Meaning:

* Discounted FCFFs (2024–2028) ≈ €7.11 billion
* Discounted Terminal Value ≈ €38.11 billion
* Added together → Total Enterprise Value ≈ €45.22 billion

2️⃣ Adjusting for Net Debt

To determine the value available solely to shareholders, Net Debt (Debt – Cash & Equivalents) was subtracted from the Enterprise Value:

Equity Value (FCFF) = €41,08,86,39,846 ≈ €41.09 billion

Thus, after accounting for all obligations, the value attributable to equity holders stands at approximately €41 billion.

3️⃣ Deriving the Predicted Share Price

The fair value per share was computed by dividing the total Equity Value by the number of shares outstanding (as of Dec 2023):

Predicted Share Price= €41.09 billion / 17,85,49,084 shares

Predicted (Fair) Share Price = € 230.13

---

# Method 2: CCF Valuation

Both FCFF (Free Cash Flow to Firm) and CCF (Capital Cash Flow) methods are used to value the entire firm, but they treat the tax benefit from debt differently.

🔹 FCFF (Free Cash Flow to Firm)

FCFF represents the cash generated from operations that is available to all capital providers — both debt and equity holders.

It does not explicitly include the interest tax shield (the tax saving due to interest expense).

The after-tax WACC is used to discount these cash flows since the tax benefit is already embedded in the cost of capital.


🔹 CCF (Capital Cash Flow)
CCF takes the same FCFF base, but it adds back the interest tax shield explicitly to account for the tax advantage from debt financing.

Since the tax benefit is directly added to the cash flows, these are discounted at the pre-tax WACC.

Formula:
CCF = FCFF + (Interest × Tax Rate)
CCF Valuation: 42,182,864,965B
Stock Price: €236.25

---

# Method 3: ECF Valuation (Equity Cash Flow Method)

The **Equity Cash Flow (ECF)** method focuses solely on the cash available to *equity shareholders* after servicing all debt obligations (interest + principal repayments).
Unlike the FCFF and CCF models, which measure total firm value, ECF directly estimates the **Equity Value** by discounting equity-specific cash flows using the **cost of equity**.

---

###  Formula

ECF = FCFF − Interest Payments − Principal Repayments + New Debt Issued

---

###  Step-by-Step Approach

1. **Calculate Available Cash Flow:**
   Begin with the *cash flow available* from operations (same base as FCFF).

2. **Subtract Principal Repayments and Interest:**
   Reduce the available cash by yearly debt repayments and interest expenses to determine the residual cash for shareholders.

3. **Obtain Equity Cash Flows for Each Year:**
   These are the actual cash inflows to equity holders after all financing obligations.

4. **Determine Terminal Value for Equity:**
   Compute the terminal value of assets and subtract the terminal value of debt:
   
  TV Equity ​= TVAssets ​− TVDebt​

6. **Discount the Equity Cash Flows:**
   Use the **cost of equity**, derived from CAPM, to discount all future equity cash flows and the terminal equity value back to the present.
---

###  Key Results (from Excel model)

| Year | Cash Flow Available (€ mn) | Principal Payment | **Equity Cash Flow** |
| ---- | -------------------------: | ----------------: | -------------------: |
| 2024 |                  1 560 430 |        –1 560 430 |                 0.00 |
| 2025 |                  1 443 314 |        –1 443 314 |                 0.00 |
| 2026 |                  1 737 865 |        –1 737 865 |                 0.00 |
| 2027 |                  2 055 383 |         – 821 391 |            1 233 992 |
| 2028 |                  2 397 518 |                 0 |            2 397 518 |

**Terminal Value (Assets):** € 59.56 million
**Terminal Value (Equity):** € 58.74 million (= Assets – Debt)

---

**Discounted Equity Cash Flows + Terminal Value** = € 45.07 billion <br> 
**Actual Market Equity Value (2023)**             = € 40.93 billion <br> 
**Predicted Share Price (ECF Model)**             = € 229.29 vs € 176.12 (actual)

---

##  Final Comparison & Conclusion

After performing all three valuation methods — **FCFF**, **CCF**, and **ECF** — we can now compare the results to evaluate Adidas AG’s fair value.
Each method provides a different lens to assess the company’s worth, depending on how debt and tax effects are treated.

---

###  Comparison Table

| Method   | Concept                                                   | Discount Rate Used     | Enterprise Value (EV) | Equity Value | Fair Share Price (€) | Market Price (€) | Inference   |
| :------- | :-------------------------------------------------------- | :--------------------- | --------------------: | -----------: | -------------------: | ---------------: | :---------- |
| **FCFF** | Cash available to both debt & equity holders              | After-tax WACC (8.45%) |             € 45.22 B |    ~€ 41.2 B |               ~€ 220 |           176.12 | Undervalued |
| **CCF**  | Firm cash flow + interest tax shield                      | Pre-tax WACC (9.3%)    |             € 46.31 B |   ~€ 42.18 B |             € 236.25 |           176.12 | Undervalued |
| **ECF**  | Cash available only to shareholders (after debt payments) | Cost of Equity (≈ 9%)  |                     — |    € 45.07 B |             € 229.29 |           176.12 | Undervalued |

---

###  Summary Table (All Methods Together)

| Method   | EV (Billion €) | Fair Share Price (€) | % Difference vs Market |
| :------- | -------------: | -------------------: | ---------------------: |
| **FCFF** |          45.22 |               220.00 |                  +25 % |
| **CCF**  |          46.31 |               236.25 |                  +34 % |
| **ECF**  |          45.07 |               229.29 |                  +30 % |

---
Therefore, based on DCF-based valuation approaches, **Adidas AG was undervalued and represented a long-term buying opportunity**.

---

##  Repository Files
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
  <img src="https://img.shields.io/badge/Project-DCF%20Valuation-blue?style=for-the-badge" alt="DCF Badge"/>
  <img src="https://img.shields.io/badge/Language-English-lightgrey?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-Finance%20%26%20Valuation-green?style=for-the-badge"/>
</p>
