## Training data should satisfy the below conditions:<br />
Last touched by Merit<br />
Ownership is not Investor Backed, Public or Private Equity<br />
Funding Stage = No Funding<br />
Business Model = Software<br />
Approx. 1046 accounts<br />

Dependant variable is classified as below:<br />
If merit_interest_level is like '%uninteresting%' or '%not interesting%' then 0 (we don't want to pursue similar accounts)<br />
else if merit_interest_level is like '%best %' or '%interesting%' or '%track%' then 1 (we want to pursue similar accounts)<br />


## Predict data should satisfy the below conditions:<br />
Not touched by Merit ever<br />
Ownership is not Investor Backed, Public or Private Equity<br />
Funding Stage = No Funding<br />
Business Model = Software<br />
Location - mailing_address or headquarters indicates that the prospect is a US account<br />
Approx. 9178 accounts<br />

## Current list of 16 variables:<br />
- REVENUE_ESTIMATE<br />
- EMPLOYEE_ESTIMATE<br />
- EMPLOYEES_ON_PROFESSIONAL_NETWORKS<br />
- Employee Growth (Monthly)<br />
- Employee Growth (Quarterly)<br />
- Employee Growth (6 months)<br />
- Employee Growth (Annual)<br />
- TOTAL_REVIEW_COUNT<br />
- AGGREGATE_RATING<br />
- OWNERSHIP<br />
- YEAR_FOUNDED<br />
- NAICS_3<br />
- GRATA_INDUSTRIES<br />
- EXECUTIVE_TITLE<br />
- EXECUTIVE_EMAIL_DELIVERABILITY<br />
- MERIT_CATEGORY_PRIMARY<br />

