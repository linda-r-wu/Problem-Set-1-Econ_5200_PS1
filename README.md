# Average Basket Value Audit: Objections and Evidence

1. **“Why trim legitimate consumer purchases? Will this number reconcile with revenue?”**

   A trimmed mean removes real spending from both ends and measures the middle of the distribution rather than average revenue per transaction.

   **Type:** Statistic.

   **Evidence needed:** After excluding B2B and cancelled orders, compare the trimmed mean with total consumer revenue divided by completed consumer transactions. Quantify the difference.

2. **“Did you fix the logging change, or just hide it through trimming?”**

   Cancelled orders can remain in the middle 80%, so trimming does not guarantee comparable transactions across years.

   **Type:** Data.

   **Evidence needed:** Show counts and basket totals by year, customer type and order status. Apply the same completed-consumer inclusion rule to both years and reconcile the results against finance records.

3. **“What decision is this metric supposed to support?”**

   Typical basket value, revenue per transaction and spending per customer measure different things.

   **Type:** Business definition.

   **Evidence needed:** Agree on the metric’s purpose, numerator, denominator and exclusions. Confirm whether each transaction or each customer should receive equal weight.
