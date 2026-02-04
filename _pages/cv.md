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

Work experience
======

* 2025-present: Co-founder & Staff AI Engineer
  * Pulsecity
  * Duties include:
    * Architected a modular event intelligence platform that unifies urban signals into a source-agnostic Canonical Event Schema; implemented the Adapter Pattern to abstract diverse ingestion methods (REST/GraphQL APIs vs. custom scraping libraries).
    * Engineered an automated enrichment layer using the Instructor framework and Pydantic to enforce type-safe extraction from LLMs (OpenAI/Anthropic), mapping unstructured data to a multi-dimensional "Human Experience Taxonomy" for RAG and semantic search.
    * Developed a configuration-driven OOP framework utilizing advanced design patterns (Factory, Adapters, Singleton) to manage global application state and dynamically instantiate ingestion strategies based on source-specific metadata.


* 2025-2025: Senior ML Engineer, Pricing
  * [HP Inc (via Mphasis)](https://www.hp.com/es-es/home.html)
  * Duties included:
    * Collaborated within the Pricing Data Science team of HP Inc (Sant Cugat), with a data science software refactoring project for various markets, aiming at developing a common architecture for feature engineering, modeling, and deployment of price elasticity and causal inference models.
    *	Architected 3 modular Delta Live Tables pipelines in Python to support retail and commercial demand models across North America and EMEA, reducing code duplication by ~11%, enabling region-specific customizations.
    * Built counterfactual price model (LightGBM) to simulate competitor brand prices as if they were an HP brand, to use as confounders in a demand elasticity model.


* 2024-2025: LLM Engineer, Post-training
  * [Invisible Technologies](https://www.invisible.co/)
  * Duties included:
    * Executed advanced post-training workflows, including Supervised Fine-Tuning (SFT) and Reinforcement Learning from Human Feedback (RLHF), to optimize model reasoning and alignment.
    * Developed complex evaluation datasets including Chain-of-Thought (CoT) mathematical reasoning prompts and benchmarks to measure model performance in specialized domains, ensuring high-fidelity outputs for frontier LLM providers.
    * Collaborated on the implementation of reward modeling and preference-based optimization (DPO/PPO) to refine model behavior, safety guardrails, and surface model failure modes in complex tasks.


* 2023-2024: Data Scientist, Promotion Optimization (BEES)
  * [AB InBev](https://www.ab-inbev.com/)
  * Duties included:
    * Collaborated on a promotion (pricing) optimization algorithm, improving key metrics like ROI, investment, and coverage across various promotional strategies (combos, stepped, among others).
      * This involved modeling demand elasticity with a log-log model (XGBoost), optimizing for a chosen metric with cubic splines, rank suggested order arrangements in combos, among other dynamic phases.
    * Optimized ROI by 48% in A/B test promotional experiments in the market of Panama, over a period of 8 months.
    * Developed an algorithm targeting first-time purchasers, optimizing discount allocation and saving on budget.
    * Created an RCT module that automated user allocation into control and treatment groups and logged experiment metadata (promotion ID, allocation, blocking factors, timestamps) to a historical registry, reducing experiment design time by ~80%.
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
    * Built models such as linear regression, decision trees, PCA, and clustering.
    * Helped define sector-specific, multidimensional risk metrics spanning income underreporting, cost inflation, shareholder benefit abuse, and transfer pricing anomalies.
    * Mapped shareholding structures with graph theory (NetworkX, Bokeh), leveraging centrality insights to reveal influential entities and hidden transactional links, improving tax evasion case prioritization by 2x.
    * Created the Data Warehouse inventory eCatalog, a Shiny (R) solution mapping all data infrastructure used for risk estimations (metadata, data dictionaries, data lineage). This streamlined the process of identifying data sources by 2x.


Skills
======
* Python
* R
* SQL
* Git
* Spark
* Data Science & AI Techniques: Propensity score matching (PSM), Double machine learning (DML), Doubly robust machine learning (DRML), A/B/n testing, RCTs, CATE calibration methods, RAG, among others.
* Azure Cloud: Azure Databricks, DL/Hive, Azure Machine Learning Studio, Azure DevOps, Unity Catalog, Lakeflow (data orchestration), Delta Live Tables (DLT), and Azure Synapse Analytics. AWS: Amazon SageMaker, Amazon Redshift, Athena, AWS Glue.
* Additional Tools: MATLAB, Java, Gurobi, PuLP, Docker, MLflow, Airflow, Pytest, LangChain, CI/CD.


Leadership
======
* AB InBev Analytics Workshop Professor (2024)
* AB InBev Global Hackathon (2023)
* R Programming Mentor (2022-2023)



Last updated: {{ "now" | date: "%Y-%m-%d" }}
