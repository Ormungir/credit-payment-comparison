#Credit Payment Comparison: Annuity vs Differentiated (with Inflation Discounting)

##Project Overview
This project compares annuity and differentiated loan repayment schemes in nominal terms and in real (discounted) terms, taking inflation into account.
While differentiated payments usually appear more profitable for borrowers in nominal values, this project shows that after discounting cash flows, the economic outcome depends critically on the relationship between the nominal interest rate and inflation.
The analysis is implemented in Excel and follows a DCF (Discounted Cash Flow) logic commonly used in finance and banking.

##Problem Statement
In most loan comparisons, payments are evaluated only in nominal terms.
However, money paid today is more valuable than the same amount paid in the future.

This raises a key question:
Which repayment scheme is economically more beneficial when the time value of money and inflation are taken into account?

This question is relevant for:
	banks designing credit products,
	borrowers choosing loan structures,
	analysts studying real returns under inflationary conditions.

##Methodology
The project follows these steps:

Loan modeling
	Annuity payment schedule
	Differentiated payment schedule

Nominal comparison
	Total nominal payments
	Payment dynamics over time

Discounting cash flows
	Each payment is discounted using expected inflation
	Real value of each payment is calculated

Scenario analysis
	Different nominal interest rates
	Different inflation assumptions
	Identification of break-even conditions

All calculations are done transparently in Excel, without black-box tools.

##Key Results
The analysis leads to several important conclusions:
	In nominal terms, differentiated payments always result in lower total repayment.
	After discounting for inflation, the difference between the two schemes shrinks significantly.
	When inflation exceeds the nominal interest rate, differentiated payments may become more profitable for the bank, despite lower 	nominal totals.
	The relative advantage depends primarily on:
		the gap between interest rate and inflation,
		the timing of cash flows.


These results highlight why nominal comparisons alone can be misleading.

## Step 2: Default Risk and Expected Cash Flows

In Step 2, the analysis is extended by introducing default risk.
Instead of assuming that all scheduled payments are received with certainty,
each payment is weighted by the probability that the loan survives up to that period.

This transforms discounted cash flows (DCF) into expected discounted cash flows (EDCF).

Key features of Step 2:
- Annual probability of default (PD) is converted to a monthly PD.
- Survival probability is calculated for each payment period.
- Expected cash flows are computed as Payment × Survival Probability.
- Sensitivity of default risk to payment burden (DTI) is analyzed.

Within the tested range of default probabilities and DTI sensitivity parameters,
the differentiated repayment scheme remains economically preferable for the bank
when the nominal interest rate is below expected inflation.

This result highlights the robustness of Step 1 conclusions
to the inclusion of default risk under reasonable assumptions.
