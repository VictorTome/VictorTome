# Hi, I'm Victor Tomé 👋

**Data Engineer** building production data systems for **logistics and last-mile operations**.  
Python · SQL · ETL/ELT pipelines · Automation · Applied AI

I take messy, spreadsheet-driven operations and turn them into automated, reliable data products that people actually use. Today I do this at **Anjun Express** (cross-docking & last-mile delivery, Brazil), where my tools are part of the daily routine of regional managers, analysts and leadership.

Background: postgraduate program in **AI & Machine Learning** (UT Austin), 7 years in corporate banking, 3+ years in operations in Hawaii, and a law degree. Fully fluent in English.

---

## 🚚 Featured work

> These are production systems built on internal company data, so their repositories are private. Each one has a write-up that explains the problem, the architecture and the results.

### SLA Dash: SLA analytics platform for a 7-state region
Replaced Excel-based SLA reporting for Anjun Express's Centro-Oeste region **100%**.
- Automated Python ETL on **GitHub Actions** with validation before every load, refreshing **PostgreSQL (Neon)** several times per business day
- Web app (**TypeScript**, deployed on **Vercel**) with pivot-style drill-down: state → base → city → courier, plus an open-package view by delivery stage
- In the routine of **11 managers and analysts and the Regional Director**

📖 [Case study on Medium](https://medium.com/@victor.ltome/sla-dash-how-i-replaced-excel-sla-reporting-with-an-automated-data-platform-for-last-mile-facf58331e56)

### Daily Delivery-Punctuality Pipeline (Extract → Validate → Load)
Python pipeline that replaced a manual daily reporting routine for the Quality Supervision team.
- Handles an undocumented API pagination limit, live-data page overlap (defensive deduplication) and an Excel file too large for standard libraries, by editing the `.xlsx` XML directly to keep memory low while preserving pivot tables
- Schema, key and volume checks before loading; native alerts for failures and expiring credentials

📖 [Write-up on Medium (PT-BR)](https://medium.com/@victor.ltome/pipeline-an%C3%A1lise-d-1-57e054b17546)

### Expense-control SaaS for Hub, Fleet and Transport
Internal app (**Next.js, TypeScript, Recharts**) that unified costs previously spread across nine spreadsheets; mapped real fleet data and reverse-engineered the freight-cost formula.

📖 [Write-up on Medium (PT-BR)](https://medium.com/@victor.ltome/do-excel-ao-saas-construindo-um-sistema-de-controle-de-despesas-para-hub-frota-e-transporte-na-b742c65342ce)

---

## 📂 Public repositories

| Project | What it shows |
|---|---|
| [contratos-saas](https://github.com/VictorTome/contratos-saas) | Full-stack multi-tenant MVP built in 3 days: React + Vite, Node.js/Express + TypeScript, PostgreSQL + Prisma, JWT with refresh tokens, e-signature flow |
| [Credit Card Churn Prediction](https://github.com/VictorTome/Advanced-Machine-Learning-Credit-Card-Churn-Prediction) | Feature engineering and an XGBoost ensemble; 0.85 recall on validation (UT Austin) |
| [FoodHub EDA](https://github.com/VictorTome/EDA-Foodhub-Analysis) | Exploratory data analysis of food-delivery orders to improve operations (UT Austin) |

---

## 🛠️ Tech stack

- **Data engineering:** Python (pandas, NumPy, requests) · SQL · PostgreSQL · ETL/ELT · data validation · REST API ingestion
- **Automation & cloud:** GitHub Actions · Vercel · Neon · n8n · WhatsApp integrations · PowerShell
- **Applications:** TypeScript · Next.js · React · Node.js/Express · Prisma · Tailwind CSS · Recharts
- **Machine learning:** scikit-learn · XGBoost · Random Forest · K-Means/PCA · TensorFlow/Keras · NLP (Flan-T5, SentenceTransformer)

---

## ✍️ Writing & contact

I write about the systems I build at **[Victorious Data on Medium](https://medium.com/@victor.ltome)**.

[LinkedIn](https://www.linkedin.com/in/victor-tom%C3%A9-21032a90/) · [Medium](https://medium.com/@victor.ltome)
