# Story Bank — Master STAR+R Stories

This file accumulates your best interview stories over time. Each evaluation (Block F) adds new stories here. Instead of memorizing 100 answers, maintain 5-10 deep stories that you can bend to answer almost any behavioral question.

## How it works

1. Every time `/career-ops oferta` generates Block F (Interview Plan), new STAR+R stories get appended here
2. Before your next interview, review this file — your stories are already organized by theme
3. The "Big Three" questions can be answered with stories from this bank:
   - "Tell me about yourself" → combine 2-3 stories into a narrative
   - "Tell me about your most impactful project" → pick your highest-impact story
   - "Tell me about a conflict you resolved" → find a story with a Reflection

## Stories

<!-- Stories will be added here as you evaluate offers -->
<!-- Format:
### [Theme] Story Title
**Source:** Report #NNN — Company — Role
**S (Situation):** ...
**T (Task):** ...
**A (Action):** ...
**R (Result):** ...
**Reflection:** What I learned / what I'd do differently
**Best for questions about:** [list of question types this story answers]
-->

### [ETL / Automation] WhoozCooking Pipeline Automation
**Source:** Report #001 — Analytic Partners — Marketing Science Analyst
**S:** Raw data sitting in siloed sources at WhoozCooking; manual effort doubled as the platform grew.
**T:** Automate data ingestion to enable cross-functional analysis at scale.
**A:** Built end-to-end ETL pipeline using Python, AWS Glue, and Airflow for automated ingestion and transformation.
**R:** 50% reduction in data processing time; improved data availability for cross-functional analysis.
**Reflection:** Would instrument the pipeline from day one to catch data quality issues at ingestion — learned the hard way that downstream models inherit upstream noise.
**Best for questions about:** technical problem-solving, automation, data engineering, process improvement

---

### [Statistical Modeling] WhoozCooking Churn Analysis
**Source:** Report #001 — Analytic Partners — Marketing Science Analyst
**S:** User retention dropping at WhoozCooking; no model to identify at-risk users early.
**T:** Build a churn prediction model to give the product team an early warning signal.
**A:** SQL-based cohort analysis combined with logistic regression on behavioral engagement signals; delivered insights in weekly stakeholder reports.
**R:** Insights guided product iteration and engagement strategies.
**Reflection:** Would track model accuracy drift over time — a model that's right in month 1 can degrade as user behavior evolves.
**Best for questions about:** statistical modeling, consumer behavior, stakeholder communication, A/B testing

---

### [Statistical Modeling] F1 Tire Strategy App
**Source:** Report #001 — Analytic Partners — Marketing Science Analyst
**S:** No data-driven tool existed for real-time pit strategy decisions using lap and weather data.
**T:** Build a strategy tool that predicts tire degradation to support in-race decisions.
**A:** R Shiny application with Kaplan-Meier survival curves, time-series decomposition, and linear mixed-effects models to account for driver variability.
**R:** Pit strategy success rate improved 25% in simulations.
**Reflection:** Survival models are underused outside clinical research — this project proved their value in operational settings. The mixed-effects approach handled nested data (driver × team) better than simple regression.
**Best for questions about:** statistical depth, independent projects, creative problem-solving, R skills

---

### [Communication / Stakeholder] Redshift Star Schema + Power BI Dashboards
**Source:** Report #001 — Analytic Partners — Marketing Science Analyst
**S:** Stakeholder teams at WhoozCooking had no unified view of retention and platform KPIs.
**T:** Build a single source of truth dashboard that enables data-driven decisions.
**A:** Designed Redshift star schema data model, built Power BI dashboards covering user retention, onboarding funnel, and KPI tracking; delivered weekly reports.
**R:** Stakeholder teams aligned on performance trends; reports became the standard for prioritization meetings.
**Reflection:** Star schema design up front saves enormous rework — defining the grain before building is the hardest and most important step.
**Best for questions about:** data modeling, dashboards, stakeholder management, BI tools

---

### [Research / Independent Work] Pulse Diagnosis System (Patent)
**Source:** Report #001 — Analytic Partners — Marketing Science Analyst
**S:** No product existed for pulse-based chronic disease detection; research gap in non-invasive diagnostics.
**T:** Research, build, and patent a sensor analytics system from scratch.
**A:** Designed Arduino IoT sensor data collection, engineered signal processing algorithms in C/C++ for classification, validated clinically for >90% diagnostic accuracy.
**R:** Patent granted in India (Patent No. 202321031953, May 2023).
**Reflection:** Cross-domain projects (engineering + healthcare) require writing for non-technical reviewers — documentation rigor is as important as technical execution.
**Best for questions about:** independent initiative, research, patent/IP, going beyond scope
