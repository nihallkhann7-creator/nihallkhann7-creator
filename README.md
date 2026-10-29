# Hi, I'm Nihal Khan 👋

**Data & Analytics Engineer · Bengaluru, India**

I build the pipelines and dashboards that show a marketing team where its money goes and what it earns back. For nearly three years at **Supertails** (an Indian D2C pet-care company), I owned the digital-marketing data stack end to end, from the ad-platform APIs to the revenue, acquisition, spend and ROAS numbers the founders read every morning.

- 🔭 **Open to:** Data Analyst · Business Analyst · Analytics / Data Engineer · Marketing Analytics roles, in Bengaluru or remote
- 🛠️ **Currently building:** a job-search bot that finds roles, tailors my CV to each one and applies
- 📫 **Reach me:** nihallkhann7@gmail.com

---

## What I've built

- **Multi-channel marketing ETL.** Hourly and daily pulls from Google Ads, Meta, Apple Search Ads, Criteo, RevX / Intellibid, Newton, AppsFlyer and GA4 into MySQL and BigQuery. These ran first as cron jobs on GCP VMs, then moved to containerised Cloud Run jobs deployed through Git.
- **Marketing Spends Dashboard.** A FastAPI backend and React (Vite) frontend with hourly spend tracking held to IST, plus geo and campaign views.
- **Campaign taxonomy and attribution.** A four-stage campaign resolver that maps every campaign into a 21-bucket source taxonomy, and session-level attribution in BigQuery using session-touch, first-touch and last-non-direct-touch models, with an AppsFlyer install fallback.
- **Geo modelling.** A city-cluster pipeline covering all channels, with eight metro buckets and NCR split into its sub-regions.
- **Data-quality monitoring.** A daily checker and an hourly watchdog that email alerts when data goes stale, drifts or has gaps.
- **Order attribution.** A greedy nearest-average matching algorithm that assigns restricted Facebook orders to campaigns and ad sets. It replaced a slow subset-sum approach.
- **Revenue AI analyser (prototype).** An endpoint inside the dashboard that writes grounded analyst narratives. It grew out of my internal AI hackathon project, *Revenue Leak Radar*.

## Analysis highlights

- **Paid-marketing RCA.** Showed that an apparent month-on-month collapse was mostly a baseline effect from salary-cycle peaks. The real problems were a ~17% rise in acquisition CAC and an inefficient shift of budget between channels.
- **Brand RCA.** Traced a ~8.6% day-normalised GMV dip for a major pet-food brand to a single city, which accounted for ~57% of the decline. Stockouts and a fall in organic traffic were behind it.

## How I like to engineer

- Idempotent writes: upsert on unique keys, never delete-and-reload
- One combined fetch split in Python beats repeated heavy CTEs over raw tables
- Each pipeline step is isolated, so one failure never blocks the rest
- Check the query cost estimate before anything touches BigQuery

## Toolkit

| Area | Tools |
|---|---|
| Languages | Python (pandas, FastAPI), SQL (MySQL, BigQuery), JavaScript / React |
| Cloud & ops | GCP (BigQuery, Cloud Run, GCS, Secret Manager), Docker, cron, Git / GitHub |
| Marketing data | Google Ads API, Meta Marketing API, AppsFlyer, GA4, Criteo, Apple Search Ads |
| BI & reporting | Tableau, Power BI, Google Sheets automation, Excel |
| Learning | Spark / PySpark, Databricks |

## Experience

**Supertails**, Bengaluru
- Senior Associate, Data & Analytics (Jan 2026 – Oct 2026)
- Associate, Data Analyst (Aug 2024 – Dec 2025)
- Data Analyst Intern (Jan 2024 – Jul 2024)
- Longest-tenured member of the team. I mentored interns and onboarded every new joiner on the team's data and processes.

**Licious**: Business Analyst Intern (Dec 2022 – Feb 2023)

## Education

- **MBA, Business Analytics**, AIMS Institutes, Bengaluru (2021 – 2023)
- **B.E., Civil Engineering**, REVA University, Bengaluru (2016 – 2020)
