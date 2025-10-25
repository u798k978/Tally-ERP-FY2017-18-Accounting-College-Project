## Tally-ERP-FY2017-18-Accounting-College-Project

**Project Overview:**
This repository contains a complete, simulated accounting dataset for the Fiscal Year 2017-2018 (Apr 2017 – Mar 2018) for a fictional company, Aarav Foods Private Limited (Karnataka).

The project is designed to simulate a full-year accounting cycle using Tally ERP 9, covering the transition from the Pre-GST regime (VAT/CST for Apr-Jun 2017) to the GST regime (from Jul 2017 onward).

The dataset is comprehensive, including master data, high-volume transactions across various voucher types, and final statutory financial statements. It serves as an excellent resource for practicing Tally data import, report generation, and financial analysis.

**File Structure:**

The files are organized into four main categories: Project Documentation, Tally XML Import Files, Raw Dataset (CSV), and Final Financial Statements (CSV).

1. Project Documentation & Tally Customization-

   Tally_Project_FY2017-18_Report.docx:The main project report containing the company's background, scope, tax assumptions, ledger/item setup instructions, and key financial summaries (Top Customers/Suppliers, etc.).
   
   Tally_XML_Notes.txt: Detailed instructions and usage notes for importing the provided XML files into Tally ERP 9, including required ledger names and assumptions.

   Aarav_Project_Summary.tdl:A Tally Definition Language (TDL) file designed to create a custom report in Tally (named "Aarav Project Summary") to show a quick summary of Sales, Purchases, and Net GST liability.

2. Tally XML Import Vouchers - These XML files are formatted for direct import into Tally ERP 9 to create transactions.

   Tally_GST_All_Vouchers.xml: Contains all GST-era Sales and Purchase vouchers (Jul 2017 – Mar 2018) combined into a single file for bulk import.
   
   Tally_Purchases_GST_All.xml: Contains all GST-era Purchase vouchers only.
   
   Tally_Sales_GST_All.xml: Contains all GST-era Sales vouchers only.

   Tally_Purchases_Sample_Import.xml: A small sample of GST-era Purchase vouchers (approx. 50) for testing the import process.

   Tally_Sales_Sample_Import.xml: A small sample of GST-era Sales vouchers (approx. 50) for testing the import process.

3. Raw Dataset (Extracted from Tally ERP 9) - These CSV files contain the underlying raw master and transaction data, typically exported from Tally's daybooks and masters. They are grouped by their original Excel sheet name (Tally_ERP9_FY2017-18_Project_Dataset.xlsx).

   Company Info.csv: Company's statutory details (Aarav Foods Pvt Ltd), including PAN, GSTIN, and financial year dates.
   
   Ledgers.csv: List of all General Ledger accounts (Customers, Suppliers, Tax, Expenses, etc.) with opening balances.
   
   Stock Items.csv: Details of all inventory items (products) with their base units and opening stock quantities/rates.
   
   Units.csv: List of Units of Measure used for inventory (e.g., kg, ltr, pcs).

   Godowns.csv: List of Stock Locations/Godowns (e.g., Bengaluru WH, Mumbai WH).
   
   Cost Centers.csv: List of Cost Centers used to track sales profitability (Retail, Wholesale, Online).
   
   Sales.csv: Detailed data for all Sales vouchers for the entire FY 2017-18.
   
   Purchases.csv: Detailed data for all Purchase vouchers for the entire FY 2017-18.
   
   Receipts.csv: All Receipts (money coming in, mostly from customers).
   
   Payments.csv: All Payments (money going out, mostly to suppliers and expenses).
   
   Journal.csv: All Journal vouchers (adjustments, provisions, depreciation, etc.).
   
   Contra.csv: All Contra vouchers (cash to bank, bank to cash transfers).
   
   Credit Notes.csv: All Credit Notes (e.g., sales returns, rate adjustments for sales).
   
   Debit Notes.csv: All Debit Notes (e.g., purchase returns, rate adjustments for purchases).
   
   Stock Journals.csv: All Stock Journal vouchers (e.g., inter-godown stock transfers).
   
   Bills of Entry.csv: Details of Import Bills of Entry (BOE), used for recording import transactions.
   
   Bank Statement.csvSimulated Bank Statement for HDFC Bank, used for Bank Reconciliation.

4. Final Financial Statements - These CSV files contain the final, computed financial reports, grouped by their original Excel sheet name (Financial_Statements_FY2017-18.xlsx).

   Inputs.csv: Key figures and metrics used as inputs or intermediate steps for report generation.
   
   Trial Balance.csv: The final Trial Balance for the company as of March 31, 2018.
   
   Trading Account.csv: The Trading Account showing Gross Profit/Loss calculation.
   
   Profit & Loss.csv: The Profit & Loss Account showing Net Profit/Loss calculation.
   
   Balance Sheet.csv: The final Balance Sheet showing the Assets and Liabilities position.
   
   Cash Flow.csv: The Cash Flow Statement (Indirect Method) for the financial year.




