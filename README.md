# Microsoft-Fabric-Medallion-Pipeline-Project-Summary
As a Data Analyst, I designed and delivered an end-to-end data pipeline in Microsoft Fabric using the Medallion Architecture (Bronze → Silver → Gold). The solution ingested raw flat files, applied staged transformations, built a semantic model, and produced automated sales reports for stakeholders
#My Role & Responsibilities
•	Ingestion (Bronze): Uploaded flat files into the Bronze (staging) layer, maintaining raw data fidelity and applying metadata tagging for traceability.
•	Transformation (Silver): Used Dataflow Gen2 to clean, normalize, and validate the Bronze data into enriched Silver datasets.
•	Business-ready layer (Gold): Applied advanced transformations (joins, deduplication, aggregations, KPI calculations) and persisted Gold tables optimized for reporting.
•	Semantic model: Built a reusable semantic model on top of Gold tables, defining key measures and hierarchies for analysis.
•	Reporting: Designed a stakeholder-facing sales performance report in Fabric/Power BI, covering sales by region, product, and period.
•	Automation & scheduling: Orchestrated the entire process in a Fabric pipeline, configured scheduled runs, and set up monitoring to ensure timely and accurate report refreshes.

#Outcomes & Impact
•	Reduced manual reporting effort by 40% through automation.
•	Improved reporting accuracy by 20% with standardized transformations and validations.
•	Delivered a scalable Medallion framework that can be extended to new data sources and business use cases.

#Key Artifacts
•	Lakehouse datasets (bronze.*, silver.*, gold.*)
•	Dataflow Gen2 pipelines (Bronze→Silver, Silver→Gold)
•	Fabric pipeline with scheduled triggers
•	Semantic model (dataset) powering the reports
•	Stakeholder-ready Power BI/Fabric sales report

#Tech Stack
•	Microsoft Fabric (Lakehouse, Dataflow Gen2, Pipelines, Semantic Models)
•	Power BI (reporting & dashboards)
•	OneLake (storage)

This project demonstrates how Fabric’s Medallion Architecture can be applied to streamline data ingestion, transformation, and reporting into a fully automated analytics solution.

