# Customer Churn — Data Quality and Exploratory Analysis (Task 02)

## 1. Dataset Overview & Profiling
- Source file: `raw_churn.csv`
- Size: 15 rows and 11 columns (`CustomerID`, `Gender`, `Age`, `TenureMonths`, `SubscriptionType`, `MonthlyCharges`, `TotalCharges`, `ContractType`, `SupportTickets`, `PaymentMethod`, `Churn`)
- Missing values: 0 missing values across all columns
- Duplicates: 0 exact duplicate rows

## 2. Cleaning Assumptions & Validation Checks
- Trimmed extra spaces from text columns so labels stay consistent.
- Checked for exact duplicates (0 found) and set median/mode rules for handling any missing values.
- Verified 0 remaining missing values and 0 remaining duplicates after cleaning, then exported `cleaned_churn.csv`.

## 3. Summary Statistics & Initial Patterns
- Age: average ~39.07 years (range 23 to 60)
- TenureMonths: average ~18.80 months (range 2 to 48)
- MonthlyCharges: average ~$84.66 (range $49.99 to $149.99)
- TotalCharges: average ~$2,088.48 (range $99.98 to $7,199.52)
- SupportTickets: average ~2.53 (range 0 to 6)
- Initial patterns: Customers vary widely in tenure (2–48 months) and monthly charges (~$50–$150), with total charges increasing with tenure and monthly rate.
-
