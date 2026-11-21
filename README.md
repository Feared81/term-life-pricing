# Term Life Pricing
 
A profit test for a level term life insurance policy, built in Excel with VBA.
 
> **Status:** In progress.
 
## Overview
 
This project prices a level term life policy by projecting its cash flows year by year and measuring whether the premium earns an acceptable profit for the insurer. The model uses an industry-standard mortality table and will be built step by step in Excel, with VBA used to automate repeated calculations.
 
## Planned features
 
- Year-by-year projection of policies in force, deaths, and lapses
- Cash flows for premiums, death benefits, and expenses
- Profit measures: present value of profits, profit margin, and internal rate of return (IRR)
- Inputs for issue age, term length, face amount, and assumptions, so different policies can be tested
## Data
 
Mortality rates come from the **2015 Valuation Basic Table (VBT)**, Male, Non-Smoker, select and ultimate, developed by the American Academy of Actuaries along with the Society of Actuaries.
 
- Source: [mort.soa.org](https://mort.soa.org/)
- Background: [SOA 2015 Valuation Basic Tables](https://www.soa.org/resources/experience-studies/2015/2015-valuation-basic-tables/)
## Project structure
 
```
term-life-pricing/
├── data/                    # Mortality table from mort.soa.org
├── vba/                     # VBA modules exported as .bas text files
├── term-life-pricing.xlsm   # The pricing model
└── README.md
```
 
The VBA code is stored inside the workbook, which Git can't show as readable changes. Each module is also exported to `vba/` as a plain text file so the code can be reviewed and its history tracked on GitHub.
 
## Tools
 
- Microsoft Excel
- VBA
- Git and GitHub
