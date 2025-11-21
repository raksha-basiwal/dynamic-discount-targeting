# dynamic-discount-targeting
Uplift modeling for smart discounts on the Online Retail (UK) dataset — two-model approach (P(buy|discount) vs P(buy|no-discount)) to target high-uplift customers. Python + scikit-learn.
Two-model uplift: P(buy|discount) − P(buy|no-discount) to target only customers who change behavior.
Dataset: Online Retail (UK). Features: total_spend, num_invoices, num_unique_items, recency_days, country.
See notebook: dynamic_discount_targeting.ipynb • Preview: img/top_uplift_table.png
Outputs: discount_targeting_scored.csv, top_uplift_sample.csv
