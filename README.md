# Real Estate Bookkeeping Portfolio Case Study (QuickBooks Online)

Welcome to my professional real estate bookkeeping portfolio project. This repository contains a comprehensive, end-to-end, 6-month simulated accounting lifecycle for a **4-unit residential rental property** in QuickBooks Online (QBO) [1, 5].

Real estate accounting is highly specialized, requiring strict adherence to trust-fund segregation laws [2], accurate asset capitalization [3], unit-level class tracking [9, 18], and complex journal entries for property acquisitions and disposals [3, 13]. This project serves as a showcase of my ability to maintain clean, audit-ready, and investor-compliant books for real estate professionals globally [1, 15].

---

## 📂 Repository Contents

*   **`real-estate-bookkeeping-portfolio-dataset.xlsx`**: The master Excel workbook containing the complete project data [17].
*   **`Chart_of_Accounts_Import.csv`**: An importable real estate Chart of Accounts with account numbers, types, and detail types mapped for QuickBooks Online [8, 19].
*   **`Checking_Account_Feed.csv`**: A 6-month bank feed (47 transactions) in CSV format ready to import into QuickBooks Online's bank feed tool [12].
*   **`Credit_Card_Feed.csv`**: A 14-transaction credit card registry simulating business overhead and maintenance expenditures [9].
*   **`Readme_&_Portfolio_Guide.pdf`**: A step-by-step masterclass blueprint on how to rebuild this project in your own QBO sandbox [5].

---

## 🏠 Project Scenario: "123 Maple Street"

*   **Property Type**: 4-Unit Residential Apartment Building (Unit A, B, C, and D) [1, 2].
*   **Acquisition Date**: January 15, 2026 [3, 5].
*   **Acquisition Cost**: $850,000 (Allocated: Land $150,000 | Building $700,000) [2, 5].
*   **Financing**: $640,000 Mortgage Loan Payable (6.5% interest, 30-year amortization) [6, 7].
*   **Disposal Date**: June 30, 2026 (Sold for $950,000 with a $40,676.50 capital gain) [1, 5, 13].

---

## 🛠️ Specialized Real Estate Accounting Treatments Showcased

### 1. Land vs. Building Cost Basis Allocation
Buildings depreciate over 27.5 years, but land does not depreciate [2, 20, 21]. Entering the purchase as a single asset is a major tax error. I separated the $850,000 purchase price using a standard 17.65% land allocation ($150,000 Land, $700,000 Building) [2, 3].

### 2. Tenant Escrow Trust Compliance (Zero Co-mingling)
By law, tenant security deposits must be segregated from operational business cash [2]. I established a separate **Tenant Trust checking account** (Asset) to hold the cash and balanced it against a **Tenant Security Deposits Held liability account** [2, 8].

### 3. Class-Based Rental Sub-Ledgers
To evaluate individual unit performance, I configured QBO Class/Location tracking for **Units A, B, C, and D** [9, 10, 22]. Every rent collection and maintenance transaction is tagged to a specific unit, allowing for granular property P&Ls [9, 11].

---

## 📊 Key Property Transactions & Journal Entries

### January 15, 2026: Property Acquisition Journal Entry
To record the property purchase, capitalized acquisition costs, prepaid insurance, mortgage liability, and cash to close from the Closing Disclosure (HUD-1) [3, 4]:

| Account Number | Account Name | Debit | Credit | Description / Memo |
| :--- | :--- | :--- | :--- | :--- |
| **12100** | Fixed Assets: 123 Maple St - Building | $700,000.00 | | Property Acquisition Building Basis [23] |
| **12200** | Fixed Assets: 123 Maple St - Land | $150,000.00 | | Property Acquisition Land Basis [23] |
| **12300** | Fixed Assets: 123 Maple St - Capitalized Costs | $11,000.00 | | Capitalized escrow, title, and lender fees [3] |
| **13100** | Prepaid Property Insurance | $2,400.00 | | 12-month property hazard insurance prepaid at close [15] |
| **23100** | Mortgages Payable: 123 Maple St | | $640,000.00 | Long-Term Commercial Mortgage Loan [6, 8] |
| **31100** | Owner's Capital Investment | | $10,000.00 | Reversing pre-paid earnest money deposit [7, 8] |
| **11100** | Checking - Operating | | $213,400.00 | Final "Cash to Close" wire from operating account [3] |
| **TOTAL** | | **$863,400.00** | **$863,400.00** | **Balanced to the penny** |

### June 30, 2026: Property Disposal Journal Entry
To record the sale of 123 Maple Street for $950,000, payoff of the remaining mortgage, refunding of tenant security deposits, write-off of book value, and booking of the capital gain [1, 13]:

| Account Number | Account Name | Debit | Credit | Description / Memo |
| :--- | :--- | :--- | :--- | :--- |
| **11100** | Checking - Operating | $254,310.00 | | Net sale proceeds wired to operating account [13] |
| **23100** | Mortgages Payable: 123 Maple St | $634,950.00 | | Payoff of the outstanding loan balance [13] |
| **12400** | Accumulated Depreciation: 123 Maple St | $11,676.50 | | Reversing accumulated depreciation to zero [13] |
| **22100** | Tenant Security Deposits Held (Liability) | $7,200.00 | | Refunding deposits to buyer/escrow [8, 13] |
| **12100** | Fixed Assets: 123 Maple St - Building | | $700,000.00 | Writing off building asset basis [13] |
| **12200** | Fixed Assets: 123 Maple St - Land | | $150,000.00 | Writing off land asset basis [13] |
| **12300** | Fixed Assets: 123 Maple St - Capitalized Costs | | $11,000.00 | Writing off capitalized acquisition costs [13] |
| **13100** | Prepaid Property Insurance | | $1,200.00 | Writing off remaining unamortized prepaid insurance [13] |
| **11200** | Checking - Tenant Trust (Security Escrow) | | $7,200.00 | Liquidation of the trust escrow account [13] |
| **52100** | Gain on Sale of Real Estate | | $40,676.50 | Capital gain recorded on property disposal [1, 13] |
| **TOTAL** | | **$908,136.50** | **$908,136.50** | **Balanced to the penny** |

---

## 📈 Strategic Reporting & Financial KPIs

Beyond basic bookkeeping, I generate strategic financial intelligence for real estate investors [14]. This model calculated the following annualized property metrics for 123 Maple Street prior to its sale [14]:

*   **Net Operating Income (NOI)**: **$53,815.00** (Annualized) – Tracks the core profitability of the asset [14].
*   **Capitalization Rate (Cap Rate)**: **6.23%** – Represents the unlevered yield based on the acquisition cost [14].
*   **Debt Service Coverage Ratio (DSCR)**: **1.33** – Essential for confirming bank refinancing suitability (Minimum requirement is typically 1.25) [14, 15].
*   **Cash-on-Cash Return (CoC)**: **5.58%** – Measures the levered return on actual cash equity invested ($240,000 cash-on-hand close) [14].
*   **Operating Expense Ratio (OER)**: **32.73%** – Tracks operational efficiency against gross revenue [14].

---

## 🏁 How to Verify Your Rebuild (The Answer Key)

If you use the CSV feeds in this repository to reconstruct this client file in QuickBooks Online, your financials must match these exact figures to verify your work [24]:

1.  **Profit & Loss (6-Month Operating)**: Net Operating Income must equal **$24,665.00**; Net Income (including mortgage interest and building depreciation) must equal **$3,407.50** [14].
2.  **Pre-Sale Balance Sheet (June 30 Morning)**:
    *   Total Assets = **$886,047.50** (including $28,224.00 Checking Operating, $7,200.00 Checking Tenant Trust, $1,300.00 Prepaid Insurance, and $849,323.50 Net Fixed Assets) [5].
    *   Total Liabilities = **$642,640.00** (including $634,950.00 Mortgage, $7,200.00 Security Deposits Held, and $490.00 Credit Card Payable) [5].
    *   Total Equity = **$243,407.50** (including $240,000.00 Owner Capital and $3,407.50 Net Income) [5].
    *   *Balance Discrepancy = $0.00*
3.  **Post-Sale Balance Sheet (June 30 Evening)**:
    *   Total Assets = **$276,684.00** (fully liquid cash in Checking Operating, after payoff of mortgage, CC, and owner draw of $5,000) [5].
    *   Total Liabilities = **$0.00** (fully liquidated) [5].
    *   Total Equity = **$276,684.00** ($240,000.00 Owner Capital - $5,000.00 Owner Draw + $41,684.00 Cumulative Net Income which includes the $40,676.50 gain on sale) [1, 5, 13].
    *   *Balance Discrepancy = $0.00*

---

## 📩 Contact & Business Inquiries

Are you a real estate investor, property manager, or syndicator looking for a specialized bookkeeper to clean up your books, manage your escrow accounts, and provide executive-level KPI dashboards? [15] 

Let's discuss how I can streamline your bookkeeping so you can focus on scouting your next acquisition [16].

*   **Name**: Mostafa Rafid
*   **Email**: Quickmostafazero@gmail.com
*   **LinkedIn**: https://www.linkedin.com/in/mostafa-rafid-/
*   **Mobile**: +8801781845848
