# Company KPI Monitoring Dashboard | Power BI

An academic Business Intelligence mini-project that uses **Microsoft Power BI** to monitor and analyze a company's financial and marketing performance from **January 2018 to December 2020**.

## Project overview

The dashboard transforms monthly business data into visual indicators that help monitor performance, compare results with targets, and explore relationships between marketing and financial KPIs.

### Key performance indicators

- Revenue and target revenue
- Gross profit and gross margin
- Leads (prospects)
- Marketing costs
- Conversion rate and churn rate
- Customer Acquisition Cost (CAC)
- Customer Lifetime Value (CLV)
- Marketing influence and organic reach rate

## Dashboard contents

The Power BI report contains three main pages:

1. **KPI overview** – summary cards and time-series/campaign charts for revenue, profit, leads, marketing costs, conversion rate, churn rate, gross margin, and marketing influence.
2. **KPI correlations** – visual analysis of the relationships between revenue and leads, CAC and CLV, and leads and conversion rate.
3. **Marketing campaign scorecard** – campaign-level revenue, target revenue, KPI status, and sparklines.

## Files

```text
power-bi-company-kpi-dashboard/
├── README.md
├── .gitignore
├── report/
│   └── ProjetFinal.pbix
└── docs/
    └── Mini_Projet_Power_BI_KPI.pdf
```

- `report/ProjetFinal.pbix` – interactive Power BI report. Open it with **Power BI Desktop**.
- `docs/Mini_Projet_Power_BI_KPI.pdf` – project report/documentation.

## Dataset

The project report identifies the dataset as **CMO KPI Data**, available on Kaggle:

https://www.kaggle.com/datasets/muskanmalviya/cmo-kpi-data

The dataset itself is not included in this repository. Please download it from Kaggle and follow its terms of use if you need to reproduce or modify the report.

## Tools

- Microsoft Power BI
- Power Query / Power BI data model
- DAX measures and Power BI visualizations

## How to open the project

1. Install **Power BI Desktop**.
2. Clone or download this repository.
3. Open `report/ProjetFinal.pbix` in Power BI Desktop.
4. If Power BI requests the source dataset, download the CMO KPI Data dataset from the Kaggle link above and update the data-source path in Power BI.

## Academic context

Mini-project for the **Advanced Databases** module, Licence in Data Engineering and Software Development (IDDL), academic year **2023–2024**.

**Project contributors:** Ilham Kajtih, Sakina Daoudi, and Widad Aoulad Haddou.  
**Supervisor:** Pr. Mourad Fariss.

## Notes

This repository presents an academic project. The figures and interpretations are those documented in the accompanying report and should be understood in the context of the dataset and project assumptions.
