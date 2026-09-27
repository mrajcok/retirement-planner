# Retirement Planner for Roth Conversions and Healthcare Costs

Download retirement-planner.html and open it in a browser. It will run entirely locally, with no data sent to any server. The model is based on the assumptions below, but you can change them in the input form. The model is intended for educational purposes only; it is not financial or tax advice.
 
Last updated: Sept 27, 2026. All dollar amounts are in today's dollars unless noted. This is an educational model, not financial or tax advice.
 
## Opportunities identified while still working
 
- Work 401k plan allows after-tax contributions with in-plan Roth conversion (mega backdoor Roth). $72,000 total limit. Turn on automatic conversion. Ask HR whether the plan has ever failed nondiscrimination (ACP) testing.
- Backdoor Roth IRAs for both spouses: up to $8,600 each in 2026. Works cleanly only with no existing pre-tax traditional IRA balances. It also starts the Roth IRA five-year clock. Stop in the year the 401(k) is rolled to an IRA.

## Retirement plan
 
- Model allows for paying off any mortgage at the start of retirement from the brokerage account.
- Living expenses taking into account rising with inflation, not including healthcare. Survivor spending assumed at 75% of that.
- Healthcare (added on top of living expenses; starting costs in today's dollars, rising 5% per year against 3% general inflation):
  - Before 65: $15,000 per person per year for ACA coverage (premiums plus out-of-pocket). No ACA subsidies assumed.
  - From 65, per person per month in today's cost: Part B $185, Part D $15, Medigap Plan G $300. Part A premium-free. No Part C.
  - Dental insurance: $40 per person per month, every year.
  - Medicare surcharges (IRMAA) shown separately from federal tax.
- The model allows for an HSA to pay Medicare Part B and D premiums and Medicare surcharges. Plan G and dental insurance premiums are not HSA-qualified expenses.
- Funding order each year: brokerage account first (up to $100k per year sold), then Social Security, then pre-tax withdrawals. Taxes are paid from pre-tax withdrawals.

## Social Security
 
- Replace estimated benefit with actual figures from ssa.gov.

## Roth conversion strategy
 
- Retirement to 64 (before Medicare): convert up to the top of a bracket or select a custom max to convert.
- 65 until RMDs start: convert up to the top of a bracket or select a custom max to convert.
- RMDs start at 75 (born 1960 or later under SECURE 2.0). Confirm with the plan administrator.

## Modeling assumptions
 
- Return: 3% per year after inflation. General inflation 3%.
- Everything is in today's dollars, so living expenses, Social Security, contributions, brackets and the standard deduction keep pace with inflation. Amounts fixed in law (the $250k net investment income tax threshold and Social Security taxation thresholds), brokerage cost basis and the mortgage balance lose value with inflation and are adjusted for it. Brokerage account has a 0.6% annual tax drag.
- Tax: 2026 federal brackets, standard deduction ($32,200 married filing jointly, plus $1,650 per spouse age 65 or older), long-term capital gains at 0/15/20%, 3.8% net investment income tax above $250k, actual Social Security taxation formula. Brackets are assumed to rise with inflation.
- Medicare surcharges (IRMAA): 2026 thresholds, based on income from two years earlier.
- Mortality: I die first; my wife survives and files single until the plan ends at my age 95.
- Heirs pay about 30% on inherited pre-tax money over the 10-year rule.

## Not modeled
 
- State income tax, including any plan to move states.
- ACA premium subsidies before 65. Large conversions at 62 to 64 will make us ineligible, so full premiums are assumed to be inside spending (or covered by COBRA or retiree coverage).
- Itemized deductions, market volatility, sequence-of-returns risk, and future changes to tax law.

## Open items
 
- Confirm Social Security estimates at ssa.gov for both spouses.
- Confirm brokerage cost basis.
- Confirm RMD age (75) with the plan administrator.
- Check the 401(k) match true-up and set up the mega backdoor Roth with automatic conversion.
- Decide on backdoor Roth IRAs for 2026.
- Plan health insurance for 62 to 64.
- Review conversion amounts each year with a CPA, ideally in November or December.
