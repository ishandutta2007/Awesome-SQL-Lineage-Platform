# Awesome-SQL-Lineage-Platform

## Top SQL Lineage Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Column-Level Lineage, SQL Parsing, Pipeline Provenance, Impact Analysis & Data Catalog Integration*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **SQL / Data Lineage**. These systems map how data moves from sources through transformations to tables, dashboards, and models — enabling impact analysis, debugging, and governance.



**Examples** include Manta, OpenLineage, DataHub, Atlan, Collibra, CastorDoc, Secoda, Microsoft Purview, OvalEdge, and Alex Solutions (the category leaders).



**Open-source emphasis**: Data lineage has a strong open ecosystem. **OpenLineage**, **Marquez**, **DataHub**, **Apache Atlas**, and related projects provide standards and production-capable platforms. This section is heavily expanded with these tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Free Trial Limits | Key Lineage Strengths |
| :--- | :--- | :--- | :--- | :--- |
| **[Manta](https://www.getmanta.com/)** *(IBM)* | Enterprise automated code-level and SQL lineage platform designed for complex hybrid data estates. | **~$5,000/mo** ($60,000/yr base contract) or via IBM Resource Units at ~$0.41/RU-hour | **30-day free trial** via IBM Cloud Pak for Data sandbox (1 deployment env, 100 compute units, 1 data fabric project) | Deep legacy ETL parsing (Informatica, SSIS, DataStage), stored procedures, end-to-end column lineage |
| **[Astronomer Astro](https://www.astronomer.io/)** | Fully managed Apache Airflow & OpenLineage platform providing unified pipeline observability. | **$0.35/hour** (~$250/mo base for Developer tier) + $0.13/hr per worker | **14-day free trial** with **$20 free compute credits** (no credit card required, unlimited DAG lineage runs within credit cap) | Native OpenLineage emitter, runtime dataset dependencies, column-level Airflow/Spark lineage |
| **[Acryl Cloud](https://datahubproject.io/)** *(DataHub Managed)* | Commercial enterprise control plane and managed SaaS built on the open-source DataHub standard. | **~$1,667/mo** ($20,000/yr base subscription for Team/Business tier) | **14-day free trial / sandbox PoC** (up to 3 connectors, 10 user seats; open-source DataHub is free self-hosted under Apache 2.0) | Column-level lineage graphs, automated dbt/warehouse ingestion, impact analysis workflows |
| **[Atlan](https://atlan.com/)** | Active metadata platform and modern data workspace integrating cataloging and column lineage. | **~$6,250/mo** ($75,000/yr base contract for Growth tier) | **Free tier for 1 user** (single-user read/catalog access) or **14-day guided trial** (up to 5 data sources, 10 users) | Modern data stack integration (Snowflake, BigQuery, dbt), upstream/downstream impact alerts |
| **[Collibra](https://www.collibra.com/)** | Enterprise data governance and intelligence cloud platform with automated technical & business lineage. | **~$14,167/mo** ($170,000/yr base subscription for Core Platform) | **20-day free trial** for Data Quality & Observability module (up to 5 data connections; self-guided interactive sandbox for core) | End-to-end governance traceability, business glossary mapping, regulatory compliance auditing |
| **[CastorDoc](https://www.castordoc.com/)** *(Coalesce Catalog)* | Collaborative data catalog and automated lineage engine tailored for analytics and BI teams. | **~$833/mo** ($10,000/yr Starter tier) | **14-day free trial** (up to 3 warehouse connectors, 5 team members, full automated metadata & lineage scanning) | Automated SQL dialect parsing, BI dashboard lineage (Looker, Tableau, Metabase), impact scoring |
| **[Secoda](https://www.secoda.co/)** | AI-native data management, search, and automated column lineage platform for data teams. | **$99/mo** (Starter plan) or **~$2,000/mo** ($24,000/yr for Growth tier) | **14-day free trial** (no credit card required, up to 2 data warehouse integrations, 5 users) | Natural-language lineage search, AI documentation generation, automated Slack/Teams impact alerts |
| **[Microsoft Purview](https://azure.microsoft.com/en-us/products/purview)** | Unified data governance and cataloging service for Azure, multicloud, and on-premises data estates. | **$0.40/hour** per Data Governance Processing Unit (DGPU) + **$1.00/mo** per 100 governed assets | **Free tier forever** for up to **1,000 annotated data assets** + first 1 MB metadata storage free (requires activity within 90 days) | Native Azure Synapse/Data Factory lineage, multi-cloud connector ecosystem, automated classification |
| **[OvalEdge](https://www.ovaledge.com/)** | End-to-end data catalog, data governance suite, and automated code-level lineage tool. | **$1,300/mo** ($15,600/yr Essential plan) or **$100/user/mo** | **30-day free trial / First Month Free** package (up to 2 connected databases, 5 users, full lineage exploration) | SQL query log parsing, stored procedure tracing, automated impact analysis reports |
| **[Alex Solutions](https://www.alexsolutions.com.au/)** | Enterprise-grade metadata management and data lineage platform for regulated environments. | **~$3,500/mo** ($42,000/yr base enterprise tier) | **14-day free trial** upon request (evaluation environment with 3 custom metadata sources, sample enterprise lineage models) | Deep multi-technology parsing, regulatory audit trails (BCBS 239, GDPR), asset dependency graphs |
| **[Gudu SQLFlow Cloud](https://sqlflow.gudusoft.com/)** | Automated SQL dialect lineage analyzer and visualizer supporting 20+ SQL engines. | **$49.99/mo** (Premium Cloud, or $599.88/yr); On-prem starts at $500/mo | **Free forever tier** (web UI SQL parser, up to 20 queries/day) + **3-day Premium trial** (10,000 SQL statements/mo, REST API access) | Instant SQL dialect parsing, column-level dataflow visualization, CSV/JSON/SVG graph exports |



## Open-Source GitHub Projects

- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)**  

  Open standard for lineage metadata collection — instrument jobs as they run; integrations for Spark, Airflow, dbt, Flink, and more.



- **[Marquez](https://github.com/MarquezProject/marquez)**  

  Open-source metadata service and reference implementation of the OpenLineage API — collect, aggregate, and visualize job and dataset lineage.



- **[DataHub](https://github.com/datahub-project/datahub)**  

  Leading open-source metadata platform with search, governance features, and strong SQL/column-level lineage across warehouses, dbt, BI tools, and pipelines.



- **[Apache Atlas](https://github.com/apache/atlas)**  

  Open metadata and governance framework (historically Hadoop-centric) with lineage capabilities; foundation for some commercial offerings.



- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  

  Open-source metadata and data catalog platform with lineage, discovery, and quality features.



- **[sqllineage and SQL parsers](https://github.com/)**  

  Open Python and other parsers that extract table- and column-level lineage from SQL statements.



- **[dbt lineage / docs](https://docs.getdbt.com/)**  

  Built-in lineage graphs from dbt manifests — excellent for the transformation layer in modern stacks.



- **[Amundsen](https://github.com/amundsen-io/amundsen)**  

  Open data discovery and metadata engine (Lyft origin) with lineage-related capabilities in the broader ecosystem.



- **[Egeria](https://github.com/odpi/egeria)**  

  Open metadata and governance for exchanging metadata across tools and platforms.



- **[Airflow / Spark OpenLineage integrators](https://github.com/OpenLineage)**  

  Official and community listeners that emit OpenLineage events from common orchestration and compute engines.



### Additional Strong Open-Source Options

- Instrumenting pipelines with **OpenLineage** and storing events in **Marquez** or **DataHub**.

- Using **DataHub** as a full open catalog + lineage UI with push and pull ingestion.

- Relying on **dbt docs** lineage for the SQL transformation layer and extending outward with OpenLineage.

- Parsing query logs (Snowflake, BigQuery, etc.) with open SQL lineage parsers for warehouse-native lineage.

- Combining open lineage graphs with impact analysis scripts for change management.

- Preferring open standards so metadata is not locked to a single vendor.



**Frameworks for building custom systems**: Emit **OpenLineage** from Airflow, Spark, dbt, and jobs; collect in **Marquez** or **DataHub**; enrich with warehouse query-log lineage and dbt manifests. This stack is fully open and production-used. Commercial platforms (Manta, Atlan, Collibra, Purview, Secoda, etc.) still lead in deep legacy ETL parsing, polished governance workflows, support SLAs, and turnkey enterprise coverage.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Lineage accuracy depends on instrumentation coverage and parser quality. Incomplete lineage can give false confidence about impact. Open deployments require operational ownership (storage, upgrades, access control). Always validate critical impact analysis before making production schema changes.

- This list is not data-governance advice.



---

**Made for data engineers, analytics engineers, and governance teams who need to know where data comes from and where it goes.**

Let's keep lineage open, standards-based, and trustworthy.
