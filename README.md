<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Mahesh%20Sai%20Kandula&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Junior%20Data%20Engineer%20%C2%B7%20Analytics%20Engineer%20%C2%B7%20Sydney&descSize=18&descAlignY=58" width="100%" alt="Mahesh Sai Kandula, Junior Data Engineer and Analytics Engineer, Sydney"/>

**I build tested, documented data pipelines and dashboards people can trust, and I check my own numbers.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mahesh--kandula--data-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahesh-kandula-data/)
[![Portfolio](https://img.shields.io/badge/Portfolio-maheshsaikandula.com-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.maheshsaikandula.com/)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maheshsaikandula@gmail.com)

</div>

---

### 👋 About me

- 🎓 **Master of Data Science**, Macquarie University (2026) · B.Tech in Computer Science & Engineering
- 🛠️ **Data operations at Optus** (part-time, 2025-2026): monitored production **Databricks** and **dbt** pipelines, investigated failed loads and reconciled source and destination tables in **SQL**
- 💼 **Now:** on-site IT operations support at **Total IT Global** for enterprise clients and their developer and data teams
- 🎯 **Open to** junior data engineering, analytics engineering, data analyst and BI roles in Sydney

---

### 🧰 Tech stack

<div align="center">

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)
![dbt](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
<br/>
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

</div>

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🚆 [Sydney Transit Intelligence Platform](https://github.com/MSkandula/sydney-transit-intelligence-platform)
*Live TfNSW rail data → Databricks lakehouse → dbt → Tableau*

| | |
|---|---|
| **96.2%** | trains on time (57,363 stop events) |
| **4 of 17** | lines cause 54% of delay-minutes |
| **31** | dbt tests, CI on every PR |

- Ingests GTFS feeds every 15 min into Bronze/Silver/Gold Delta tables
- dbt Core: 8 marts and 1 incremental fact table, docs on GitHub Pages
- Found and fixed 2 silent pipeline failures, then added a health check

`Python` `Databricks` `dbt` `SQL` `GitHub Actions` `Tableau`

</td>
<td width="50%" valign="top">

#### 💳 [PayScope: Payments Risk & Merchant Analytics](https://github.com/MSkandula/PAYscope)
*Data-quality pipeline for a synthetic payments processor*

| | |
|---|---|
| **138K** | records across 6 tables |
| **~4,000** | injected defects detected |
| **9** | findings from auditing the pipeline |

- Raw → clean → mart across 3 PostgreSQL schemas. Bad records are flagged, never deleted
- Caught a validity cascade that wrongly excluded ~29,700 sound transactions
- 7 SQL marts, explainable risk rules, 3 [Tableau dashboards](https://public.tableau.com/app/profile/mahesh.sai.kandula7753/viz/Transaction_monitoring/Dashboard3?publish=yes)

`PostgreSQL` `SQL` `Python` `Tableau`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📦 [E-Commerce Delivery & Retention Review](https://github.com/MSkandula/ecommerce-delivery-retention-review)
*99K orders taken from Excel → Python → SQL → Power BI*

- Late orders (4+ days) score **1.85/5** against **4.29/5** for early ones
- Lateness clusters in a few states, up to **3.5x** the national rate
- Every pandas result reproduced in SQL, which caught **2 errors** before the dashboard

`PostgreSQL` `Python` `Power BI` `DAX`

</td>
<td width="50%" valign="top">

#### 🏠 [Sydney Airbnb Guest Satisfaction](https://github.com/MSkandula/AirBNB)
*ML on 17,730 Sydney listings*

- Tuned XGBoost reaching **ROC-AUC 0.771**, with leakage-proof features
- SHAP shows host portfolio size drives satisfaction more than price or amenities

`Python` `scikit-learn` `XGBoost` `SHAP`

</td>
</tr>
</table>

<details>
<summary><b>🔬 More projects (computer vision and deep learning)</b></summary>
<br/>

| Project | What it does | Stack |
|---|---|---|
| [Organ Disease Progression Visualizer](https://github.com/MSkandula/Disease-Progression-visuliazation) | CT-driven 3D lung-disease visualizer. OpenCV features drive an auditable PyVista mesh, validated on 8 cases | Python, OpenCV, PyVista |
| [Colorectal Cancer Tissue Classifier](https://github.com/MSkandula/Automatic-recognition-of-different-tissue-types-of-colorectal-cancer-using-deep-learning) | Classifies histopathology images into 8 tissue types. A custom CNN (94%) beat VGG16 transfer learning (89%) | TensorFlow, Keras |

</details>

---

### 🎓 Education & certifications

| | |
|---|---|
| 🎓 **Master of Data Science** | Macquarie University, Sydney · 2024-2026 |
| 🎓 **B.Tech, Computer Science & Engineering** | GITAM University, India · 2020-2024 |
| 📜 **Certifications** | IBM Data Science · Google Data Analytics · AWS Cloud Virtual Internship |

---

<div align="center">

**How I work:** reproduce every number two ways · test the pipeline, not just the code · write down the limits

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" alt=""/>

</div>
