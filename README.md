# Hi, I'm Mahesh

**Junior data engineer / analytics engineer in Sydney.** I build tested, documented pipelines in **SQL · Python · dbt · Databricks** and dashboards in **Tableau · Power BI**, and I check my own numbers.

Master of Data Science (Macquarie University). Previously part-time at Optus, monitoring production Databricks and dbt pipelines, investigating failed loads and reconciling source and destination tables in SQL.

maheshsaikandula@gmail.com · [LinkedIn](https://www.linkedin.com/in/mahesh-kandula-data/) · [Portfolio](https://www.maheshsaikandula.com/)

### Tools I work with

`SQL` `Python (pandas)` `PostgreSQL` `Databricks (Delta Lake)` `dbt Core` `GitHub Actions` `Tableau` `Power BI` `Excel` `Git` `Jupyter`

---

### Featured project: Sydney Transit Intelligence Platform

**Live TfNSW rail data → Databricks lakehouse → dbt → Tableau** · `Python` `Databricks` `dbt` `SQL` `GitHub Actions` `Tableau`

- Ingests TfNSW GTFS static and realtime feeds every 15 minutes into a Bronze/Silver/Gold Delta lakehouse on Databricks
- dbt Core models (8 staging views, 8 marts, 1 incremental fact table, 31 tests); CI runs ruff, pytest and `dbt build` on every PR; dbt docs deployed to GitHub Pages
- Across 57,363 reconciled stop events on 5 days, trains ran 96.2% on time, and 4 of 17 lines (T8, T2, T4, T1) caused 54% of delay-minutes
- The evening peak (5-7pm) ran 87-88% on time against 97-99% in the morning
- Found and fixed two silent pipeline failures, then added a health check so every run ends `done OK` or `done FAILED`
- Small sample, so the findings are indicative only. The limits are written up in the repo.

➡️ [View the project](https://github.com/MSkandula/sydney-transit-intelligence-platform)

### PayScope: Payments Risk & Merchant Analytics

**Data-quality pipeline for a synthetic payments processor** · `PostgreSQL` `SQL` `Python` `Tableau`

- Raw → clean → mart pipeline across 3 PostgreSQL schemas: 138K records over 6 tables (100K transactions)
- About 4,000 deliberately injected defects, caught by SQL and Python checks. Bad records are flagged, never deleted.
- Audited the pipeline against its own answer key and documented 9 findings, including a validity cascade that wrongly excluded about 29,700 sound transactions
- 7 SQL marts, an explainable rule-based risk engine and 3 Tableau dashboards. Merchants are segmented by behaviour, because the source risk tier showed little link to actual chargebacks.

➡️ [View the project](https://github.com/MSkandula/PAYscope) · 📈 [Live dashboards on Tableau Public](https://public.tableau.com/app/profile/mahesh.sai.kandula7753/viz/Transaction_monitoring/Dashboard3?publish=yes)

### E-Commerce Delivery & Retention Review

**Marketplace analysis taken from Excel → Python → SQL → Power BI** · `PostgreSQL` `SQL` `Python` `Power BI`

- 99K orders, $13.6M revenue, 3,095 sellers, 9 relational tables loaded into PostgreSQL
- Orders 4+ days late score 1.85/5 against 4.29/5 for early orders, and lateness clusters in a few states (up to 3.5x the national rate)
- Reproduced every pandas result in SQL, which caught 2 methodology errors before they reached the dashboard
- 3-page Power BI dashboard; every DAX measure is checked against its Python and SQL equivalent

➡️ [View the project](https://github.com/MSkandula/ecommerce-delivery-retention-review)

### Other projects

| Project | What it does | Stack |
|---|---|---|
| [Sydney Airbnb Guest Satisfaction Classifier](https://github.com/MSkandula/AirBNB) | Predicts top-tier Sydney listings from 17,730 records. Host portfolio size, not price or amenities, drives guest satisfaction (tuned XGBoost, ROC-AUC 0.771, SHAP-verified) | Python, scikit-learn, XGBoost, SHAP |
| [Organ Disease Progression Visualizer](https://github.com/MSkandula/Disease-Progression-visuliazation) | CT-driven 3D lung-disease visualizer. OpenCV feature extraction drives an auditable PyVista mesh, validated on 8 cases | Python, OpenCV, PyVista |
| [Colorectal Cancer Tissue Classifier](https://github.com/MSkandula/Automatic-recognition-of-different-tissue-types-of-colorectal-cancer-using-deep-learning) | Classifies histopathology images into 8 tissue types. A custom CNN (94%) beat VGG16 transfer learning (89%) | TensorFlow, Keras |

### Education & certifications

- M.Sc. Data Science, Macquarie University, Sydney
- B.Tech, Computer Science & Engineering, GITAM University, India
- IBM Data Science Professional Certificate · Google Data Analytics Professional Certificate · AWS Cloud Fundamentals by AICTE
