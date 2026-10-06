# Excel Data Entry Portfolio Projects

Three Excel projects demonstrating accurate data capture, validation, reconciliation, and quality reporting. All records, people, vendors, and organizations are fictional and were created for portfolio practice.

## Projects

### 1. CRM Customer Record Cleanup

**Workbook:** [01_CRM_Customer_Record_Cleanup.xlsx](01_CRM_Customer_Record_Cleanup.xlsx)

An intake-to-import workflow for **120 customer records**. The workbook separates source entry, normalized output, quality checks, and field rules so exceptions can be reviewed before a mock CRM import.

- Captures customer and account details in a structured entry queue with approved-value dropdowns.
- Standardizes names, organizations, email casing, phone formatting, and country labels in a formula-driven import sheet.
- Checks required fields, email and phone formats, duplicate IDs, duplicate emails and phones, and reference values.
- Sample dashboard: **104 ready**, **16 needing review**, and **18 individual check flags**.

**Sheets:** Start Here, Entry Queue, Import Ready, QC Checks, Field Rules.

### 2. AP Invoice Entry and Reconciliation

**Workbook:** [02_AP_Invoice_Entry_Reconciliation.xlsx](02_AP_Invoice_Entry_Reconciliation.xlsx)

A fictional accounts-payable workflow for invoice capture and three-way checks against purchase orders and receipt status.

- Captures invoice IDs, vendors, PO numbers, dates, totals, taxes, terms, and entry owners.
- Compares vendor, approved PO amount, and receipt status across linked sheets.
- Flags duplicate or missing invoice IDs, missing POs, vendor differences, receipt holds, and amount variances.
- Sample queue: **22 invoice rows**, including one row with a deliberately blank invoice ID; **14 ready** and **8 requiring review**.

**Sheets:** Start Here, Invoice Entry, PO & Receipt Log, AP Review, Field Rules.

### 3. Data Entry Quality and Productivity Tracker

**Workbook:** [05_Data_Entry_Quality_Tracker.xlsx](05_Data_Entry_Quality_Tracker.xlsx)

A batch-level tracker for data-entry volume, sampled accuracy, corrections, throughput, and follow-up status.

- Summarizes records entered, weighted sample accuracy, records per hour, and batches needing follow-up.
- Uses a 98% sample-accuracy target to flag batches for review.
- Records field-level exceptions with source values, entered values, correction notes, and disposition.
- Sample dashboard: **3,282 records entered**, **97.7% weighted sample accuracy**, **254.4 records per hour**, and **7 batches needing follow-up**.
- The sample Error Log contains **11 exceptions**, including **2 open** items.

**Sheets:** Start Here, Batch Log, Error Log.

## How to review the workbooks

1. Open a workbook in Excel and begin on **Start Here** for the workflow and sample metrics.
2. Review the entry or batch sheet, then follow the instructions to the formula-driven review sheets.
3. Use filters to focus on records marked Ready, exceptions, or items requiring follow-up.
4. In a portfolio walkthrough, explain one clean record and one exception, including how the workbook identifies and tracks the issue.

## Skills demonstrated

- High-volume spreadsheet data entry and consistent field formatting
- Data validation, dropdowns, sorting, filtering, and structured tables
- Formula-based cleaning, lookups, duplicate detection, and exception checks
- Invoice, PO, and receipt reconciliation
- Accuracy and productivity reporting
- Audit-friendly correction notes and status tracking

## Resume-ready project entries

**Excel CRM Data Cleanup and Validation | Portfolio Project**

- Built a 120-record CRM intake workflow with dropdown validation, standardized import output, duplicate detection, and row-level quality checks; categorized 104 records as ready and 16 for review.

**Excel Accounts Payable Invoice Reconciliation | Portfolio Project**

- Created a fictional invoice-entry and three-way reconciliation workbook that checks vendor, PO amount, and receipt status, and tracks 8 review exceptions across a 22-row sample queue.

**Excel Data Entry Quality Tracker | Portfolio Project**

- Developed a batch tracker for weighted sample accuracy, records per hour, correction status, and audit notes; summarized 3,282 sample records at 97.7% weighted accuracy.

> These are practice projects using synthetic data. Describe them as portfolio projects, not as paid work or production systems.
