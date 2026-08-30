# Hi, I'm Mahesh 👋

**Data Analyst** based in Sydney — I work in **SQL · PostgreSQL · Python · Tableau** to turn messy, large-scale data into trustworthy, decision-ready insight.

Master of Data Science (Macquarie University). I like the full path from raw data to a dashboard someone can actually act on: cleaning and validating data, modelling it in SQL, and communicating what it means.

📫 maheshsaikandula@gmail.com · [LinkedIn](https://www.linkedin.com/in/mahesh-kandula-b6393622a) · [My Portfolio Website](https://www.maheshsaikandula.com)

---

## 🔧 Tools I work with

`SQL` · `PostgreSQL` · `Python (pandas, NumPy)` · `Tableau` · `Power BI` · `Excel` · `Git` · `Jupyter`
ETL · data cleaning & validation · data modelling · exploratory data analysis · dashboarding

---

## 📊 Featured project — PayScope

**Digital Payments Risk & Merchant Analytics Platform** · `PostgreSQL` `SQL` `Python` `Tableau`

An end-to-end payments analytics pipeline simulating a fintech data stack, built to show the full data lifecycle — from raw data to business-ready dashboards.

- Layered **raw → clean → mart** architecture across 3 PostgreSQL schemas, over **100K+ transactions, 10K customers, 1.2K merchants**
- A **data-quality framework** that flags bad records instead of silently dropping them (nulls, duplicates, broken keys, invalid codes), preserving a full audit trail — **69.7% trusted transaction coverage**
- **7 SQL business marts** for transaction monitoring, merchant performance, chargeback analysis, and customer-risk profiling
- **3 interactive Tableau dashboards** with KPI tiles, time-series trends, and risk segmentation
- Key finding: source-system risk tiers diverged from actual merchant behaviour — which is why I built a behaviour-based segmentation layer

➡️ [**View the project**](https://github.com/MSkandula/PAYscope) · 📈 [Live dashboards on Tableau Public](https://public.tableau.com/app/profile/mahesh.sai.kandula7753/viz/Transaction_monitoring/Dashboard3?publish=yes)

## 📦 Featured project — E-Commerce Delivery & Retention Review

**Marketplace delivery & retention analysis** · `PostgreSQL` `SQL` `Python` `Power BI`

End-to-end analysis of a 100K-order marketplace ($13.6M revenue, 9 relational tables), taken
through Excel → Python → SQL → Power BI — each tool brought in because the previous one hit
a real limit, not chosen up front.

- Modelled **9 relational tables** (99,441 orders, 3,095 sellers, 71 categories) into
  PostgreSQL and independently reproduced all **6 business analyses** in both pandas and
  SQL, catching and correcting **2 methodology errors** (a revenue-denominator bug, a naive
  freight-ratio calculation) before either reached a dashboard
- Found that orders delivered 4+ days late score **1.85/5** vs. **4.29/5** for early
  orders, and that the delay clusters in a handful of states (up to **3.5x** the national
  rate) — connecting a low **3.12%** repeat-purchase rate to a specific, fixable delivery
  problem rather than a diffuse one
- Built a 3-page **Power BI** dashboard on a star-schema model with **15+ validated DAX
  measures**, each checked against its Python and SQL equivalent
- Documented a full decision log and self-correction trail — treating catching your own
  errors as part of the deliverable, not something to hide

➡️ [**View the project**](https://github.com/MSkandula/ecommerce-delivery-retention-review)

## 🗂️ Other projects

| Project | What it does | Stack |
|---|---|---|
| [Sydney Airbnb Guest Satisfaction Classifier](https://github.com/MSkandula/AirBNB.git) | Predicts top-tier Sydney listings from 17,730 records; found host portfolio size — not price or amenities — drives guest satisfaction (tuned XGBoost, ROC-AUC 0.771, SHAP-verified) | Python, scikit-learn, XGBoost, SHAP |
| [Organ Disease Progression Visualizer](https://github.com/MSkandula/Disease-Progression-visuliazation) | Deterministic CT-driven 3D lung-disease visualizer; OpenCV feature extraction drives an auditable PyVista mesh, validated on 8 cases | Python, OpenCV, PyVista |
| [Colorectal Cancer Tissue Classifier](https://github.com/MSkandula/Automatic-recognition-of-different-tissue-types-of-colorectal-cancer-using-deep-learning) | Classifies histopathology images into 8 tissue types; custom CNN (94%) beat VGG16 transfer learning (89%) | TensorFlow, Keras |

## 🎓 Education & certifications

- **M.Sc. Data Science** — Macquarie University, Sydney
- **B.Tech, Computer Science & Engineering** — GITAM University, India
- IBM Data Science Professional Certificate · Google Data Analytics Professional Certificate · AWS Cloud Fundamentals by AICTE
