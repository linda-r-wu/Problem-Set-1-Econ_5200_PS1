# Average Basket Value Audit — Objections and Evidence

## Objective

I reviewed the basket-value recommendation to check whether it measures the right thing and whether the evidence supports it.

## 1. Why trim legitimate consumer purchases?

**Type:** Statistic.

A trimmed mean removes spending from both ends of the distribution. After excluding B2B and cancelled orders, it can still remove legitimate consumer purchases.

**Evidence needed:** Compare the trimmed mean with total completed consumer basket value divided by transaction count, using the same eligible transactions.

**Finding:** In both simulated years, the consumer mean was $42.15 and the trimmed consumer mean was $36.53. Trimming lowered the reported basket value by $5.62.

**Conclusion:** I kept my Phase 2 recommendation: use the untrimmed mean of completed consumer baskets. It matches revenue per transaction in the simulation. I chose it because it matches the metric’s definition, not because it shows zero growth.

## 2. Did we fix the logging change or hide it through trimming?

**Type:** Data.

Cancelled orders can remain in the middle 80% of baskets. Trimming alone does not ensure that both years include comparable transactions.

**Evidence needed:** Compare transaction counts and basket totals by year, customer type and order status. Apply the same completed-consumer inclusion rule to both years, then check the resulting totals and counts against independent finance records.

**Current status:** The simulation identifies cancelled orders through their status labels. Actual finance records have not been provided, so independent reconciliation remains outstanding.

## 3. What decision should this metric support?

**Type:** Business definition.

Typical basket value, revenue per transaction and spending per customer answer different questions.

**Evidence needed:** Agree with the client on the metric’s purpose, numerator, denominator and exclusions. Confirm whether transactions or customers should receive equal weight.

**Recommendation:** For revenue per completed consumer transaction, use the arithmetic mean after excluding B2B and cancelled orders. A median or trimmed mean can be shown separately as a measure of typical basket size.

## Most Important Remaining Check

Check that consumer sales totals and completed order counts match finance’s records, and agree on how to handle refunds, discounts and taxes.

The results establish what happened in the controlled simulation. They do not establish the retailer’s actual growth.
