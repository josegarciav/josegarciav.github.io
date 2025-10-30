---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Mathematical Modeling, Research, Statistics, and Computation, University of the Basque Country
* M.S. in Applied Mathematics, Santo Domingo Institute of Technology
* B.S. in International Business & Finance, Utah State University
* B.E. in Civil Engineering (first year), Santo Domingo Institute of Technology

Work experience
======

* 2025-2025: Senior Software Engineer, Pricing Analytics
  * [HP Inc (via Mphasis)](https://www.hp.com/es-es/home.html)
  * Duties included:
    * Collaborated within the Pricing Data Science team of HP Inc (Sant Cugat), with a software standardization project for multiple data projects in various markets, aiming at developing a common architecture for data engineering, feature engineering, modeling, and deployment of price elasticity and demand forecasting models.
    *	Architected 3 modular Delta Live Tables pipelines in Python to support retail and commercial demand models across North America and EMEA, reducing code duplication by ~11%, enabling region-specific customizations.
    * Designed with stakeholders new MLOps features including integration testing between AWS model deployment platforms and internal feature library versions, increasing model deployment reliability by 10%.


<!-- * 2024-2025: LLM Engineer
  * [Invisible Technologies](https://www.invisible.co/)
  * Duties included:
    * Engineer and curate high-quality datasets to fine-tune large language models (LLMs) for expert-level performance in specialized domains, with emphasis on mathematics, multi-step logical reasoning, and research-intensive tasks.
    * Developed Chain-of-Thought (CoT) mathematical reasoning prompts to strengthen model abilities in stepwise problem-solving, multi-hop inference, and inductive logic.
    * Designed adversarial prompts to surface model failure modes in complex tasks, collected source-verified corrections, and built supervised fine-tuning datasets to reduce hallucination rates. -->


* 2023-2024: Data Scientist, Promotion Optimization (BEES)
  * [AB InBev](https://www.ab-inbev.com/)
  * Duties included:
    * Collaborated with regional LATAM team on a promotion (pricing) optimization algorithm, improving key metrics like ROI, investment, and coverage across various promotional strategies (combos, stepped, among others).
      * This involved modeling demand elasticity with a log-log model (XGBoost), optimizing for a chosen metric with cubic splines, rank suggested order arrangements in combos, among other dynamic phases.
    * Optimized ROI by 48% in A/B test promotional experiments in the market of Panama, over a period of 8 months.
    * Developed an algorithm targeting first-time purchasers, optimizing discount allocation and saving on budget.
    * Designed and implemented causal inference models (X-Learner, T-Learner, Synthetic DiD, DRLearner) to assess market innovation impacts (ATT, CATE), enabling trend identification at the blocking factor level.


* 2022-2023: Data Scientist, Product Recommendation
  * [Santa Cruz Bank](https://bsc.com.do)
  * Duties included:
    * Optimized the product recommendation (NBA) feature pipeline from having less than 20 to over 50 variables, into a two-tower modeling (item-user embeddings) approach.
    * Enhanced customer segmentation by incorporating digital behavior clustering and psychographic profiling based on commerce data.
    * Automated weekly client account reporting via a data pipeline job, boosting productivity 3x and eliminating manual data wrangling.
    * Applied NLP techniques (sentiment analysis, n-grams, entity classification) to extract insights from Salesforce CRM interaction data.


* 2019-2022: Data Scientist, Risk Analytics
  * [DGII](https://dgii.gov.do/Paginas/default.aspx)
  * Duties included:
    * Collaborated in developing the analytics & machine learning feedback system to label taxpayers as risky or not risky.
    * Mapped shareholding structures using graph theory (NetworkX, Bokeh) to identify central entities and uncover hidden transactional relationships, improving the detection and prioritization of tax evasion cases by 2x.
    * Built models such as linear regression, decision trees, PCA, and clustering.
    * Created the Data Warehouse inventory eCatalog, a Shiny (R) solution mapping all data infrastructure used for risk estimations (metadata, data dictionaries, data lineage). This streamlined the process of identifying data sources by 5x.


Skills
======
* Python
* R
* SQL
* Git
* Spark
* Data Science & AI Techniques: Propensity score matching (PSM), Double machine learning (DML), Doubly robust machine learning (DRML), A/B/n testing, RCTs, CATE calibration methods, among others.
* Azure Cloud: Azure Databricks, DL/Hive, Azure Machine Learning Studio, Azure DevOps, Unity Catalog, Lakeflow (data orchestration), Delta Live Tables (DLT), and Azure Synapse Analytics. AWS: Amazon SageMaker, Amazon Redshift, Athena, AWS Glue.
* Additional Tools: MATLAB, Java, Gurobi, PuLP, Docker, MLflow, Airflow.


Leadership
======
* AB InBev Analytics Workshop Professor (2024)
* AB InBev Global Hackathon (2023)
* R Programming Mentor (2022-2023)



Last updated: {{ "now" | date: "%Y-%m-%d" }}
