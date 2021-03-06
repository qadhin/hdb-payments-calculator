# HDB Payments Calculator
## Description
Are you a first-time homeowner? The payments calculator allows you to calculate and compare costs and fees across multiple HDB flats. Make a quick and informed buying decision on flats that meet your budget.
<br />

### Features
- Calculates costs and fees across multiple HDB flats
- Accounts for buyers' income and CPF balances
- Adjusts for HDB grants buyers are eligible for
- Determines cash requirement for deposit and fees and mortgage payments


### Assumptions
1. Buyers are first timers
2. Buyers are aged 35 and below
3. Buyers are engaged or married
   - Additional restrictions apply to single Singapore citizens who purchase HDB flats
4. HDB price is paid with CPF OA (includes deposit) whereas fees and charges are paid with cash
   - Reduces loan amount and interest on interest owed
   - Reduces conveyancing fees for resale flats
5. No cash over valuation for resale flats
   - Cash over valuation must be paid in cash
   - Loan amount will be the lower of sale price and HDB valuation of flat
<br /><br />

## Pre-requisites
- Download and fill out [Housing Information](hdb-information_template.xlsx) file
- Install numpy
  ```py
  pip install numpy
  ```
- Install pandas
  ```py
  pip install pandas
  ```
- Install tkinter
  ```py
  pip install tkinter
  ```
<br />

## Installation
1. Change directory to file save location. Example:
   ```
   cd Downloads
   ```
2. Run python code
   ```
   python hdb-payments-calculator.py
   ```
<br />

## Contribute
- Issue Tracker: tbc
- Source Code: https://github.com/mqadhin/hdb-payment-calculator/blob/main/hdb-payments-calculator.py

### Contact
If you are having issues, please let me know: md.qadhin@outlook.com
<br /><br />

## References
- [Costs and Fees - New flat](https://www.hdb.gov.sg/residential/buying-a-flat/new/finance/costs-and-fees)
- [Costs and Fees - Resale flat](https://www.hdb.gov.sg/residential/buying-a-flat/resale/financing/costs-and-fees)
- [Calculator - Payment Plan](https://homes.hdb.gov.sg/home/calculator/payment-plan)
- [Legal Fees - Enquiry facility](https://services2.hdb.gov.sg/webapp/BB14LFEESENQ/BB14PHomePage.jsp)
