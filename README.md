# Data & Analytics Engineering Portfolio | Teis Nilsson

Hi, I'm Teis.

I'm an **Analytics Engineer** with experience across analytics, digital platforms, data transformation, business intelligence, and enterprise systems.

My background spans **IT infrastructure, Salesforce development, marketing analytics, and analytics engineering**, giving me a broad perspective on how data moves from operational source systems through transformation and modelling to reporting and business decision-making.

This portfolio is where I develop those foundations further through **production-inspired Analytics Engineering and Data Engineering projects** using SQL, Python, BigQuery, Dataform, Microsoft Fabric, Power BI, and legacy enterprise technologies.

I enjoy building reliable data products that are easy to **trust, maintain, and use**.

> **My philosophy is simple: leave every system a little better than you found it.**

---

# Current Focus

I'm currently strengthening my Data Engineering and Analytics Engineering skills through hands-on projects built around realistic data and business problems.

Rather than treating technologies as isolated skills, I focus on how they work together across the data lifecycle:

```text
Source Systems
      │
      ▼
  Ingestion
      │
      ▼
   Raw Data
      │
      ▼
Data Quality
      │
      ▼
Transformation
      │
      ▼
   Modelling
      │
      ▼
Semantic Layer
      │
      ▼
Business Intelligence
```

Current focus areas include:

- Python for data engineering and automation
- SQL and relational databases
- Data profiling and quality
- Analytics Engineering
- Dimensional modelling
- ELT pipelines
- Cloud analytics architecture
- Semantic models
- Git and reproducible development workflows

---

# Portfolio Projects

| Project | Focus | Status |
| --- | --- | --- |
| **[SAP ASE Legacy Data Engineering Lab](https://github.com/Teisson/ase-legacy-lab)** | Legacy databases, SQL, transactions, extraction | 🚧 In Progress |
| **[Digital Analytics Platform](https://github.com/Teisson/ga_project/tree/master)** | Data quality, modelling, analytics engineering | 🚧 In Progress |
| CRM Segmentation & Predictive Scoring | Customer modelling and feature engineering | Planned |
| AI Analytics Assistant | AI on top of trusted analytical models | Future Extension |

---

# SAP ASE Legacy Data Engineering Lab 🚧

A hands-on legacy database lab built around **SAP Adaptive Server Enterprise 16** running in a containerized RHEL environment.

The project started as an exploration of an unfamiliar enterprise database and has developed into a practical environment for understanding legacy data engineering patterns.

Current work includes:

- Relational schema design with primary and foreign keys
- Analytical SQL, joins, aggregation, and grain
- Reusable analytical views
- Transaction and error handling
- ASE-specific object ownership and database behaviour
- Bash-based SQL execution
- Environment-based configuration
- RHEL and Podman
- Git-based development and documentation

The transaction experiments explore both successful and failed units of work, including explicit `COMMIT`, `ROLLBACK`, and error handling.

The next stage focuses on **extracting and validating ASE data with Python** and exploring how legacy data can be moved toward a modern analytical platform.

**[View SAP ASE Legacy Data Engineering Lab →](https://github.com/Teisson/ase-legacy-lab)**

---

# Digital Analytics Platform 🚧

My primary long-term portfolio project is an end-to-end analytics platform built around synthetic digital analytics data inspired by sources such as **GA4, advertising platforms, and conversion systems**.

The goal is not simply to produce a dashboard, but to explore the engineering decisions required to turn imperfect source data into a **reliable and maintainable analytics product**.

## Architecture Direction

```text
Synthetic Digital Analytics Data
              │
              ▼
         Raw Ingestion
              │
              ▼
           Raw Layer
              │
              ▼
    Profiling & Data Quality
              │
              ▼
       Transformations
              │
        ┌─────┴─────┐
        ▼           ▼
     Staging       Tests
        │
        ▼
   Analytics Models
        │
        ▼
   Dimensional Model
        │
        ▼
    Semantic Layer
        │
        ▼
   Business Intelligence
```

## Current Stage

The project currently focuses on:

- Exploring raw datasets with Python and Pandas
- Profiling columns and distributions
- Identifying missing and inconsistent values
- Detecting duplicates and potential integrity issues
- Understanding relationships between datasets
- Defining data-quality rules before transformation
- Developing through Git-based feature branches

A core principle of the project is to **understand the data before changing it** rather than immediately replacing, deleting, or imputing questionable values.

## Planned Development

As the project develops, I plan to explore:

- Reproducible data ingestion
- Data profiling and validation
- Data-quality rules
- SQL transformations
- Dimensional modelling
- Fact and dimension tables
- Automated testing
- Semantic modelling
- Incremental processing
- Business-oriented reporting
- Pipeline documentation
- Data dictionaries
- Cloud deployment

## Technology Direction

The architecture will evolve as engineering requirements emerge rather than forcing technologies into the solution from the beginning.

Technologies currently used or planned for exploration include:

**Python • Pandas • SQL • BigQuery • Dataform • Power BI • Git / GitHub**

Additional technologies will be introduced where they solve an actual engineering problem.

**[View Digital Analytics Platform →](https://github.com/Teisson/ga_project/tree/master)**

---

# Future Projects

## CRM Segmentation & Predictive Scoring

A planned Python and SQL project exploring how behavioural, transactional, and customer data can be transformed into useful customer-level analytical models.

Planned areas include:

- Data cleaning and deduplication
- Identity resolution
- Customer-level modelling
- Behavioural segmentation
- Feature engineering
- Customer scoring
- Privacy-aware data handling
- Export-ready audiences

Potential technologies:

**Python • Pandas • SQL • BigQuery • Scikit-learn**

## AI Analytics Assistant

A future exploration of how LLMs and agentic workflows can interact with a **trusted analytics environment**.

Rather than building an isolated chatbot, the goal is to investigate AI as an additional capability on top of tested models, documented metrics, and reliable data.

Potential use cases include:

- Data-quality investigation
- Root-cause analysis
- KPI explanations
- Analytics documentation
- Metadata discovery
- SQL assistance
- Business-friendly analytics exploration

This is intentionally planned **after the underlying data platform** rather than using AI as a substitute for reliable data engineering.

---

# Technical Skills

## Data Engineering & Analytics Engineering

- SQL
- Python
- Pandas
- ELT pipelines
- Data modelling
- Dimensional modelling
- Star schemas
- Semantic models
- Data quality and validation
- Data governance
- API integrations

## Data & Analytics Platforms

- Google Cloud Platform
- BigQuery
- Dataform
- Microsoft Fabric

## Business Intelligence & Digital Analytics

- Power BI
- Looker Studio
- Tableau
- Google Analytics 4
- Google Tag Manager
- Server-side tagging
- Customer journey analytics
- Attribution

## Enterprise Systems & Platform

- Salesforce
- HubSpot
- Pipedrive
- Git / GitHub
- IAM principles
- Linux / RHEL
- Podman

## Data & Privacy

- GDPR
- Data governance
- First-party data strategy

---

# Engineering Approach

I believe good analytics starts long before the dashboard.

Reliable insights depend on:

- Well-understood source data
- Clear business definitions
- Appropriate data models
- Explicit data-quality rules
- Reproducible transformations
- Maintainable pipelines
- Testing
- Documentation

A transformation should not exist simply because it makes the data look cleaner. It should have a **reason, a rule, and a reproducible implementation**.

Likewise, technology should solve a problem rather than become the goal of the project.

My aim is to build **data products that people can trust and genuinely use**.

---

# Currently Learning

My current development focus is deliberately centred on strengthening the engineering fundamentals behind modern analytics platforms:

- Python for data engineering
- Advanced SQL
- Data profiling and data quality
- Dimensional modelling
- Modern Analytics Engineering practices
- Cloud data architecture
- Legacy-to-modern data integration

Future areas of exploration include orchestration, infrastructure as code, advanced cloud data engineering, and agentic AI systems.

---

# Contact

If you're interested in Analytics Engineering, Data Engineering, modern analytics platforms, or building reliable data products, I'd be happy to connect.

**LinkedIn:**  
https://www.linkedin.com/in/teis-nilsson/

**Email:**  
teisnilsson@gmail.com
