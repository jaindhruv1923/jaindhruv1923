<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:1B1B2F,100:C9971F&height=200&section=header&text=Dhruv%20Jain&fontSize=60&fontColor=E6E8EF&animation=fadeIn&fontAlignY=38&desc=Data%20Analyst%20%C2%B7%20AI%20%26%20Data%20Science%20Student&descAlignY=62&descSize=18)

<a href="#">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&size=17&duration=3000&pause=1200&color=C9971F&center=true&vCenter=true&width=650&lines=I+check+my+own+numbers+before+anyone+else+has+to;4+end-to-end+builds+%C2%B7+ML+%C2%B7+SQL+%C2%B7+full-stack;Traceability+first%2C+impressive-sounding+second" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jaindhruv1923)
[![Email](https://img.shields.io/badge/Email-Reach_Out-C9971F?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jaindhruv1923@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-jaindhruv1923-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jaindhruv1923)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-C9971F?style=for-the-badge&logo=vercel&logoColor=white)](#)

</div>

<br/>

## 📖 Table of Contents

- [About Me](#-about-me)
- [How I Work](#-how-i-work)
- [Skills](#-skills)
- [Featured Projects](#-featured-projects)
- [GitHub Stats](#-github-stats)
- [Certifications](#-certifications)
- [Experience](#-experience)
- [Let's Connect](#-lets-connect)

<br/>

## 👋 About Me

Final-year **B.Tech CSE (AI & Data Science)** student at BML Munjal University, Gurugram (2023–2027).

Currently working as a **Data Analyst Intern** at Udaghosh Social Welfare Society and a **Business Development Intern** at Contentora Media — both remote — while shipping full end-to-end personal projects on the side: not toy notebooks, but complete pipelines with real scraped/transactional data, trained ML models, dashboards, and (where it fits) a full backend.

I'm looking for **Data Analyst / Business Analyst** roles where the job is turning messy real data into decisions someone actually acts on.

<br/>

## 🔍 How I Work

> Every one of my project READMEs, dashboards, and case studies is written against the actual notebook or dataset that produced the numbers in it — not the other way around.

Across my own projects I've caught and fixed real mismatches before publishing:
- A dashboard "Business Health Score" that disagreed with its own source notebook
- A raw-row count that turned out to be a file's *line count*, not its actual record count
- An employer-cluster count that was off by one from what the model actually produced

I'd rather ship a slightly less flashy number that's true than a rounder one that isn't reproducible. That habit — audit first, publish second — is the thing I actually want a hiring manager to notice, more than any single metric.

<br/>

## 🧰 Skills

<div align="center">

| Category | Stack |
|---|---|
| **Languages & Query** | Python · SQL (PostgreSQL / MySQL / MariaDB) · R (basics) · DuckDB |
| **ML & Data Science** | Scikit-learn · SHAP · Pandas · NumPy · Statsmodels · mlxtend |
| **BI & Dashboarding** | Power BI · Excel (Pivot Tables, Solver, Forecast Sheet) · Streamlit · Plotly · Chart.js |
| **Web / Backend** | HTML/CSS/JS · Node.js · Express.js · MongoDB |
| **Tools** | Git/GitHub · Jupyter · Google Colab · VS Code · Apify · openpyxl |
| **Core Competencies** | Data Mining · Data Wrangling & Cleaning · ETL · Predictive Modeling · Statistical Analysis · Data Visualization · Business Intelligence · Report Automation |

</div>

<br/>

## 🏆 Featured Projects

### 📊 Profitara — Retail BI & Customer Analytics Platform

[![Repo](https://img.shields.io/badge/Repo-View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/jaindhruv1923/Project-Profitara-Retail-BI-Pipeline)
[![Live](https://img.shields.io/badge/Live-Streamlit_Dashboard-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://project-profitara-retail-bi-pipeline.streamlit.app/)

An end-to-end retail analytics pipeline built on a 10,000-row India quick-commerce transaction dataset — 4,918 orders, 1,448 customers, 9 categories / 17 sub-categories, ₹66.95L total revenue.

- 🌲 **Random Forest CLV model** — R² = 0.930, predicting 12-month customer lifetime value
- 📉 **Logistic Regression churn classifier** — AUC 0.91, 85% accuracy, flagging 361 at-risk customers
- 🧩 **K-Means segmentation** — silhouette 0.611, identifying 119 high-value "Champion" customers
- 🔗 **Apriori market-basket analysis** — 52 cross-sell rules (top: Baby Food → Diapers & Wipes, lift 9.58×)
- 🌳 **Isolation Forest** for discount-abuse detection
- 📊 A 13-page **Streamlit dashboard** with a live DuckDB SQL analytics layer, plus a standalone PostgreSQL layer and a **Power BI** build
- 📄 Full BA documentation package (BRD, Executive Summary, Process Flow)

`Python` `scikit-learn` `Streamlit` `PostgreSQL` `DuckDB` `Power BI` `Plotly`

<br/>

### 🕵️ Naukri Saaf — Ghost Job Listing Detection Platform

[![Repo](https://img.shields.io/badge/Repo-View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/jaindhruv1923/Project-Naukri-Saaf-Job-Listings-Analysis)
[![Live](https://img.shields.io/badge/Live-Streamlit_Dashboard-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://project-naukri-saaf-job-listings-analysis.streamlit.app/)

An ML pipeline on 3,000 real listings scraped via Apify from LinkedIn, Indeed, and Glassdoor (cleaned to 2,851 unique listings), flagging 29.3% as likely ghost postings under a documented weak-supervision labeling scheme — since no public ground-truth ghost-job dataset exists.

- 🤖 **5 classifiers benchmarked** under temporal cross-validation — best: Gradient Boosting, AUC 0.716, F1 0.527
- 🔬 **SHAP explainability** computed per listing, per feature — every flag is traceable
- 🧑‍💼 **5 employer behavioral clusters**, incl. a "High-Risk Ghost Poster" group: 1,361 employers, 32.8% ghost rate
- 🧩 **Chrome extension** (Manifest V3, vanilla JS) — reads the live job posting on any of the 4 supported portals and scores it using the model's real feature weights, 100% locally, **zero network calls**
- 📊 A 7-tab Streamlit dashboard, a **Power BI** dashboard, and a 32-query SQL staging/analytics layer
- 📄 A full 12-document BA package (BRD, Stakeholder Analysis, User Stories, RTM, Risk Register, UAT, KPIs)

`Python` `scikit-learn` `SQL` `Chrome Extension (vanilla JS)` `Power BI` `SHAP`

<br/>

### 🍝 Grilli — Restaurant Website + Live Reservation System

[![Repo](https://img.shields.io/badge/Repo-View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/jaindhruv1923)

Took a static restaurant landing-page template (frontend only, MIT-licensed) and turned it into a working full-stack product.

- 🐛 **6 template bugs fixed** — dead nav/footer links, a missing section `id`, and a real form bug where the guest-count and time dropdowns both shared `name="person"` so only one value was ever captured
- 🧑‍🍳 **"Our Chefs" section built from scratch** — 4 chef cards, hover/focus reveals experience + specialty — didn't exist in the original template at all
- 🔌 **Full backend built from scratch** — Node.js + Express REST API (5 endpoints: create/read/update/delete reservations)
- 🗄️ **MongoDB Atlas** persistence — every booking submitted through the form is verified live in the `reservations` collection
- ✅ The reservation form now actually works end-to-end: submit → API → database → live success message, no page reload

`Node.js` `Express.js` `MongoDB` `HTML/CSS/JS`

> *Repo link above points to my GitHub profile — add the direct repo URL here once published.*

<br/>

### 🎮 KidLearn — Gamified Learning Tracker for Kids

[![Repo](https://img.shields.io/badge/Repo-View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/jaindhruv1923)

A parent/child learning dashboard built entirely in vanilla HTML/CSS/JS — no framework, `localStorage` for persistence.

- 🔥 XP, daily streaks, and a **21-badge achievement system** with auto-award logic
- 🍅 A working **Pomodoro focus timer** (25/5 split) with a canvas-drawn progress ring
- 🧬 A canvas-rendered **"Learning DNA" radar chart** across 6 subjects
- 😄 Daily **mood check-in vs. XP performance** chart
- 🎯 Weekly goals, per-subject notes, a difficulty heatmap, and an auto-generated weekly report card
- 👨‍👩‍👧‍👦 Multi-child profiles with a parent/child view toggle

`JavaScript` `HTML/CSS` `Canvas API` `localStorage`

> *Repo link above points to my GitHub profile — add the direct repo URL here once published.*

<br/>

## 📈 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=jaindhruv1923&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=C9971F&icon_color=C9971F" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jaindhruv1923&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=C9971F" />

</div>

<br/>

## 📜 Certifications

| Certification | Issuer | Date |
|---|---|:---:|
| Microsoft Power BI Data Analyst — PL-300 (Prep) | Microsoft Learn | — |
| Harnessing the Power of Data with Power BI | Microsoft | Jun 2026 |
| Extract, Transform and Load Data in Power BI | Microsoft | Jun 2026 |
| Data Modeling in Power BI | Microsoft | Jun 2026 |
| Creative Designing in Power BI | Microsoft | Jun 2026 |
| Preparing Data for Analysis with Microsoft Excel | Microsoft | Jun 2026 |
| IoT Security: Interface and Data Security | CertNexus | Feb 2026 |
| Create and Design Digital Products using Canva | Coursera | Mar 2025 |
| Work with Components in Figma | Coursera | Mar 2025 |
| Create Customer Personas in Canva | Coursera | Mar 2025 |
| Create a Storyboard using Canva | Coursera | Mar 2025 |

<br/>

## 💼 Experience

**Data Analyst Intern** — Udaghosh Social Welfare Society *(Remote, Jul 2026 – present)*
Collect, clean, and analyze data from multiple sources; build interactive dashboards and automate recurring reporting workflows in Excel, Power BI, SQL, and Python; monitor KPIs to support stakeholder decisions.

**Business Development Intern** — Contentora Media *(Remote, Jul 2026 – present)*
Lead generation via LinkedIn and email campaigns; pitch decks and partnership proposals; competitor and industry trend analysis, outreach performance reporting.

<br/>

## 📫 Let's Connect

<div align="center">

Open to Data Analyst / Business Analyst roles and collaborations — feel free to reach out.

<a href="https://www.linkedin.com/in/jaindhruv1923">
  <img src="https://img.shields.io/badge/LinkedIn-jaindhruv1923-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:jaindhruv1923@gmail.com">
  <img src="https://img.shields.io/badge/Email-jaindhruv1923@gmail.com-C9971F?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/jaindhruv1923">
  <img src="https://img.shields.io/badge/GitHub-jaindhruv1923-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:1B1B2F,100:C9971F&height=100&section=footer)

</div>
