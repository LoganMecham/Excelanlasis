# Basic analytics for je_samples (1).xlsx

## Sheet: JELineItems

- Rows (including header): 37906
- Columns: 30

### Headers

JEEntryKey, JENumber, JEIdentifier, GLAccountNumber, BLANK, EffectiveDate, Period, EntryDate, PreparerID, Source, BusinessUnit, JEDescription, Debit, Credit, Amount, AbsoluteAmount, SysManInd, UserDefined1, UserDefined2, UserDefined3, PeriodFlag, AccountType, AccountClass, GLAccountStartingBalance, GLAccountEndingBalance, SortOrder, GLAccountName, Category, Marked, MarkedInReport

### Sample rows (first 5 data rows)

- 20151, 20151, 20151, 11845, , 41822, 2015-01, 41816, POS, CREDIT CARD RECEIPT        , HOTEL PANTRY, CREDIT CARD RECEIPTS, 10.19, , 10.19, , , , , , , Assets, Cash, , , , Operating Bank Account, , , 
- 20151, 20151, 20151, 43440, , 41822, 2015-01, 41816, POS, CREDIT CARD RECEIPT        , HOTEL PANTRY, CREDIT CARD RECEIPTS, , -10.19, -10.19, , , , , , , Revenue, Sales-Other, , , , Sales - Other, , , 
- 20152, 20152, 20152, 11845, , 41822, 2015-01, 41816, POS, CREDIT CARD RECEIPT        , HOTEL PANTRY, CREDIT CARD RECEIPTS, 20.95, , 20.95, , , , , , , Assets, Cash, , , , Operating Bank Account, , , 
- 20152, 20152, 20152, 43440, , 41822, 2015-01, 41816, POS, CREDIT CARD RECEIPT        , HOTEL PANTRY, CREDIT CARD RECEIPTS, , -20.95, -20.95, , , , , , , Revenue, Sales-Other, , , , Sales - Other, , , 
- 20153, 20153, 20153, 11845, , 41822, 2015-01, 41816, POS, CREDIT CARD RECEIPT        , FOOD SERVICE, CREDIT CARD RECEIPTS, 23.91, , 23.91, , , , , , , Assets, Cash, , , , Operating Bank Account, , , 

### Missing values (top 10 columns)

- BLANK: 37905
- AbsoluteAmount: 37905
- SysManInd: 37905
- UserDefined1: 37905
- UserDefined2: 37905
- UserDefined3: 37905
- PeriodFlag: 37905
- GLAccountEndingBalance: 37905
- SortOrder: 37905
- Category: 37905

### Numeric column stats

- Debit: count=18951, min=-160918.46, max=318505.8, mean=2287.7508071176535
- Credit: count=18954, min=-318505.8, max=160918.46, mean=-2287.3887066416924
- Amount: count=37905, min=-318505.8, max=318505.8, mean=0.0
- AbsoluteAmount: count=0, min=None, max=None, mean=None
- GLAccountStartingBalance: count=0, min=None, max=None, mean=None
- GLAccountEndingBalance: count=0, min=None, max=None, mean=None
