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

- **[Manta](https://www.getmanta.com/)**  

  Deep code-level and SQL lineage platform especially strong for complex ETL (Informatica, SSIS, DataStage) and enterprise pipeline visibility.



- **[OpenLineage (standard + managed options)](https://openlineage.io/)**  

  Open standard for lineage metadata; commercial and managed offerings build on the standard and its integrations.



- **[DataHub (Acryl / managed)](https://datahubproject.io/)**  

  Open-source metadata platform with strong SQL and column-level lineage; commercial managed service available.



- **[Atlan](https://atlan.com/)**  

  Modern data workspace with active metadata, column-level lineage, and strong support for dbt, Snowflake, and the modern data stack.



- **[Collibra](https://www.collibra.com/)**  

  Enterprise data governance and catalog platform with lineage, stewardship workflows, and broad system coverage.



- **[CastorDoc](https://www.castordoc.com/)**  

  Data catalog and lineage-oriented platform focused on discoverability and documentation for analytics teams.



- **[Secoda](https://www.secoda.co/)**  

  AI-assisted data catalog and lineage for analytics engineering and self-serve discovery.



- **[Microsoft Purview](https://azure.microsoft.com/en-us/products/purview)**  

  Microsoft’s unified data governance service with lineage for Azure and connected data estates.



- **[OvalEdge](https://www.ovaledge.com/)**  

  Data catalog and lineage platform aimed at enterprise discovery, governance, and impact analysis.



- **[Alex Solutions](https://www.alexsolutions.com.au/)**  

  Data governance and lineage solutions used in enterprise and regulated environments.



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
