# Branch-expansion-ml-golomt-bank-mongolia
ML-based location optimization for Golomt bank branch placement in Mongolia using public data
# Methodology
1) Feature Engineering
   - Underserved demand indicators (e.g., low account penetration per capita)
   - Opportunity signals (e.g., loan volume in underbanked areas)
   - Saturation & workload metrics (e.g., branch density, account-per-branch load)
   - Risk indicators (e.g., delinquency and overdue loan ratios)
3) Scoring Model
   - Log and square-root transformations for skewed distributions
   - Min-max normalization across features
   - Weighted aggregation of normalized features into a composite score
   - Risk penalization (e.g., halve score for delinquency > 20%)
   - Ranking by cluster 
# Data Disclaimer
This repository contains publicly available data obtained from the [Mongol Bank Open Data Portal](https://stat.mongolbank.mn/finance) and [National Statistics Office of Mongolia](https://www.1212.mn/en). All data is used strictly for educational and non-commercial research purposes. The Mongol Bank and National Statistics Office of Mongolia retains full ownership and rights to the original datasets. If there are any concerns regarding the use of this data, please contact us or the original data provider.

