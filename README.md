<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Lloyd%20Mwiti&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Data%20Analyst%20%7C%20Data%20Engineering%20%C2%B7%20SQL%20%C2%B7%20Power%20BI%20%C2%B7%20Python&descAlignY=58&descSize=18" width="100%" alt="Lloyd Mwiti — Data Analyst"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=20&pause=1200&color=2C7DA0&center=true&vCenter=true&width=640&lines=Turning+raw+data+into+business+decisions;ETL%2FELT+pipelines+%26+data+modelling;PostgreSQL+%7C+Power+BI+%7C+DAX+%7C+Python;Retail+analytics+%26+business+intelligence;Actuarial+Science+%C3%97+Data+Engineering" alt="Typing SVG" /></a>

<p>
  <a href="mailto:lloydmwiti258@gmail.com"><img src="https://img.shields.io/badge/Email-lloydmwiti258%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/lloyd-mwiti-mugo-94066a243/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Location-Kenya-2C5364?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location"/>
  <img src="https://img.shields.io/badge/Open%20to-Data%20Roles-2EA043?style=for-the-badge" alt="Open to roles"/>
</p>

</div>

---

## 👋 About Me

I'm a **Data Analyst with a Data Engineering skill set** who turns messy operational data into clear, decision-ready reporting. I work mainly in **PostgreSQL** and **Power BI**, building everything from ETL/ELT pipelines, data models, and analytical views to executive dashboards.

My foundation is quantitative: a **BSc in Actuarial Science** (KCA University), strengthened by a **Data Engineering Bootcamp** at **LuxDevHQ**. I bring a risk-and-numbers mindset to analytics, and I care about reports that are accurate, reproducible and easy for the business to use.

- 🔭 **Currently:** building retail sales and business-intelligence reporting on PostgreSQL
- 🌱 **Learning:** advanced DAX modelling, Python automation and data-pipeline design
- 💬 **Ask me about:** SQL, Power BI, data cleaning, retail and POS analytics
- ⚡ **Approach:** simple, readable solutions first, with trade-offs explained

---

## 🛠️ Tech Stack

<div align="center">

**Databases & Querying**

<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/Aiven-FF3554?style=flat-square&logo=aiven&logoColor=white"/>
<img src="https://img.shields.io/badge/DBeaver-382923?style=flat-square&logo=dbeaver&logoColor=white"/>

**Business Intelligence & Analysis**

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/DAX-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Power%20Query-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>
<img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>

**Programming & Integrations**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/Google%20Sheets%20API-34A853?style=flat-square&logo=googlesheets&logoColor=white"/>
<img src="https://img.shields.io/badge/Odoo%20POS-714B67?style=flat-square&logo=odoo&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>

</div>

---

## 🚀 Featured Projects

### 📊 [Customer Retention & Analytics Platform](https://github.com/lloydmwiti258-dev/customer-Retention-and-journey-Analysis) — Python · Flask · BI ⭐ *Flagship*
> A full-stack business-intelligence platform for a multi-branch retailer. It turns raw POS records in Google Sheets into a live dashboard covering **retention, CAC/LTV, regional performance, churn risk and product bundling**.

<p>
  <img src="https://img.shields.io/badge/20%2B-Branches-2C5364?style=flat-square" alt="20+ branches"/>
  <img src="https://img.shields.io/badge/9-Regions-203A43?style=flat-square" alt="9 regions"/>
  <img src="https://img.shields.io/badge/6-Time%20Grains-2C7DA0?style=flat-square" alt="6 time grains"/>
  <img src="https://img.shields.io/badge/13-API%20Endpoints-2EA043?style=flat-square" alt="13 API endpoints"/>
  <img src="https://img.shields.io/badge/16-Interactive%20Charts-0F2027?style=flat-square" alt="16 charts"/>
</p>

```mermaid
flowchart LR
    A[("Google Sheets<br/>POS data")] -->|gspread · retry/backoff| B["Extract & Clean"]
    B --> C["KPI Engine<br/>retention · CAC · LTV · cohorts"]
    C --> D[("2-tier cache")]
    D --> E["Flask REST API"]
    E --> F["Chart.js dashboard"]
    E --> G["Excel exports"]
    style C fill:#203A43,stroke:#2C7DA0,color:#ffffff
    style F fill:#2C5364,stroke:#2C7DA0,color:#ffffff
```

- **ETL pipeline** from Google Sheets: retry with exponential backoff, regex price cleaning, a shop-to-region dimension, and phone-based customer IDs
- **Retention analytics** at day, week, month, quarter, half-year and year level, plus cumulative **New vs Returning** cohorts
- **Unit economics**: CAC, LTV and period-over-period growth rates, linking marketing spend to acquisition
- **Cross-shop origin analysis** showing whether new branches win new customers or move existing ones from other shops
- **RFM-style recency segmentation** with one-click **Excel win-back lists**, plus **market-basket bundle mining**
- **Performance**: replaced an O(n×m) per-customer scan with vectorised pandas grouping; shop data lazy-loads on demand
- **Secure deployment**: environment-based secrets, Vercel/Gunicorn ready, logic checked against mock datasets

`Python` `pandas` `Flask` `REST API` `Chart.js` `Google Sheets API` `ETL` `Retention` `CAC/LTV` · 📂 [View project overview](https://github.com/lloydmwiti258-dev/customer-Retention-and-journey-Analysis)

---

### 🏭 Production Planning & Demand Forecasting — Python · PostgreSQL · Odoo 🆕 *New*
> A planning platform that turns **one monthly revenue target** into a demand forecast for every product and shop, the **raw materials to buy**, and **daily min/max stock levels** for every outlet. All of it comes from live Odoo ERP data.

<p>
  <img src="https://img.shields.io/badge/600k%2B-POS%20Order%20Lines-2C5364?style=flat-square" alt="600k+ POS order lines"/>
  <img src="https://img.shields.io/badge/20%20%C2%B7%208-Channels%20%C2%B7%20Regions-203A43?style=flat-square" alt="20 channels, 8 regions"/>
  <img src="https://img.shields.io/badge/1%E2%80%9312-Month%20Horizon-2C7DA0?style=flat-square" alt="1-12 month horizon"/>
  <img src="https://img.shields.io/badge/7-Planning%20Dashboards-2EA043?style=flat-square" alt="7 planning dashboards"/>
  <img src="https://img.shields.io/badge/100%25-Target%20Reconciliation-0F2027?style=flat-square" alt="100% target reconciliation"/>
</p>

```mermaid
flowchart LR
    A[("Odoo ERP<br/>POS · BoM · stock · dispatch")] -->|SQL · snapshot · cache| B["Demand forecast<br/>seasonality + momentum"]
    B --> C["Scale to target<br/>shop reconciliation"]
    C --> D["Material requirements<br/>BoM explosion"]
    C --> E["Min / Max stock<br/>run-rate · lead times"]
    D & E --> F["7-tab planning dashboard"]
    style B fill:#203A43,stroke:#2C7DA0,color:#ffffff
    style C fill:#203A43,stroke:#2C7DA0,color:#ffffff
    style F fill:#2C5364,stroke:#2C7DA0,color:#ffffff
```

- **Forecasting model**: each month's forecast blends the same month last year with the last three months' trend. It covers 1–12 months and is scaled to the revenue target.
- **Cold start**: new shops and products borrow growth from regional peers, then the region, then the whole portfolio, instead of being blended with a false "zero last year".
- **Hierarchical reconciliation**: bottom-up shop forecasts now sum to **exactly** the company target. Before, they overshot by ~10%.
- **MRP**: projected units are multiplied through each product's Bill of Materials to give the raw materials needed.
- **Inventory**: min/max levels come from a blend of planned and actual sales pace, plus each shop's measured dispatch lead time.
- **Data engineering**: advanced PostgreSQL (CTEs, ROLLUP, FILTER), a snapshot of closed months built from 600k+ order lines, and a cache that serves old data while it refreshes
- **Data quality**: fixed bundles counted three times, corrected pooled outlet revenue, and reconciled stock totals with the stock report

`Python` `Flask` `PostgreSQL` `Odoo` `Demand Forecasting` `MRP` `Inventory Optimisation` `Data Engineering` · 📂 [View repo](https://github.com/lloydmwiti258-dev/production-planning-forecasting)

---

### ☀️ Sunrise SQL Project — PostgreSQL
> SQL analysis project on the Sunrise dataset, covering data exploration, cleaning and business queries.

`PostgreSQL` `SQL` `Data Analysis` · 📂 [View repo](https://github.com/lloydmwiti258-dev/SQL-PROJECT)

---

### 🛒 Retail Sales Reporting Suite — PostgreSQL · Odoo POS
> A production set of SQL reports for a multi-outlet retailer running Odoo POS on PostgreSQL.

- Covers **~19 physical and online outlets** in a single, consistent reporting layer
- **ROLLUP-based subtotals** for outlet, category and grand-total views in one query
- **Canonical masterfile product ordering**, so every report lines up with the business's product list
- **Date parameters at the top of each file**, so non-technical users can rerun any period safely

`PostgreSQL` `ROLLUP` `CTEs` `Odoo` `Retail Analytics`

---

### 🚕 Ride-Hailing Analytics — SQL → Power BI
> End-to-end analysis of a real-world ride-hailing booking dataset, from dirty raw table to CEO-ready insight.

- **Cleaned a messy booking table** by fixing types, nulls, duplicates and inconsistent categories
- Built **analytical SQL views** with computed revenue columns as a single source of truth
- Connected the cleaned PostgreSQL view to **Power BI** and resolved DAX and schema-prefix issues along the way
- Delivered **CEO-facing insights** on demand, revenue and booking performance

`PostgreSQL` `SQL Views` `Power BI` `DAX` `Data Cleaning`

---

### 🚗 Car Sales Dashboard — Power BI
> Interactive Power BI report built on a car sales dataset.

- Data cleaning and shaping in **Power Query Editor**
- Debugged a custom-column formula error caused by **column type ordering in Applied Steps**
- Sales KPIs and drill-down visuals for performance tracking

`Power BI` `Power Query` `DAX`

---

### 🐍 Python ↔ Google Sheets Automation
> Lightweight pipeline that reads and writes Google Sheets from Python.

- Service-account **API setup and authentication** with `gspread`
- Read/write operations with **pandas integration** for analysis-ready DataFrames

`Python` `gspread` `pandas` `Google Sheets API`

---

## 💼 Experience

| Role | Organization | Focus |
|---|---|---|
| **Data Analyst** | Denri Africa | SQL reporting, retail sales analytics, BI |
| **Intern** | CIC Insurance | Insurance operations and data |

## 🎓 Education & Training

| Credential | Institution |
|---|---|
| **BSc Actuarial Science** | KCA University |
| **Data Engineering Bootcamp** | LuxDevHQ |

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=lloydmwiti258-dev&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lloydmwiti258-dev&layout=compact&hide_border=true&theme=tokyonight&langs_count=6" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=lloydmwiti258-dev&theme=tokyonight&hide_border=true" alt="GitHub streak"/>

</div>

---

## 🤝 Let's Work Together

I'm open to **Data Analyst, BI Analyst and Analytics Engineering** roles and collaborations. If you need clean data, reliable SQL or dashboards that leadership will use, let's talk.

<div align="center">

<a href="mailto:lloydmwiti258@gmail.com"><img src="https://img.shields.io/badge/Get%20in%20touch-2C5364?style=for-the-badge&logo=maildotru&logoColor=white" alt="Get in touch"/></a>

<img src="https://komarev.com/ghpvc/?username=lloydmwiti258-dev&color=2C5364&style=flat-square&label=Profile+views" alt="Profile views"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=110&section=footer" width="100%"/>

</div>
