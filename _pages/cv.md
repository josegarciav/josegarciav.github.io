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
<!-- * Ph.D. in Mathematics and Statistics, University of the Basque Country, 2029 (expected) -->
* M.S. in Mathematical Modeling, Statistics, and Computation, University of the Basque Country
* M.S. in Applied Mathematics, Santo Domingo Institute of Technology
* B.S. in International Business & Finance, Utah State University
<!-- * B.E. in Civil Engineering (first year), Santo Domingo Institute of Technology -->

Work experience
======

<!-- * 2025-Present: Senior Software Engineer, Pricing
  * [Mphasis](https://www.mphasis.com/home.html)
  * Duties included:
    * Collaborate within the Pricing Data Science team of HP Inc, with a software standardization project for multiple data projects in various global regions, aiming at developing a common architecture for data engineering, feature engineering, modeling, and deployment of pricing models.
    * The projects include causal inference for CATE estimation, demand prediction for smart promotions, among others. -->

* 2024-Present: Data Scientist, LLM Engineer (Freelance)
  * [Invisible Technologies](https://www.invisible.co/)
  * Duties include:
    * Engineer and curate high-quality datasets to fine-tune large language models (LLMs) for expert-level performance in specialized domains, with emphasis on advanced mathematics, multi-step logical reasoning, and research-intensive tasks.
    * Develop Chain-of-Thought (CoT) reasoning prompts and scaffolded training strategies to strengthen model abilities in stepwise problem-solving, multi-hop inference, and inductive logic.
    * Designed adversarial prompts to surface model failure modes in complex tasks, collected source-verified corrections, and built supervised fine-tuning datasets to reduce hallucination rates.

* 2023-2024: Data Scientist, Promotion Optimization (BEES)
  * [AB InBev](https://www.ab-inbev.com/)
  * Duties included:
    * Collaborated with regional LATAM team on a promotion optimization algorithm, improving key metrics like ROI, investment, and coverage across various promotional strategies (combos, stepped, among others).
      * This involved modeling demand elasticity with a log-log model (XGBoost), optimizing for a chosen metric with cubic splines, rank suggested order arrangements in combos, among other phases.
    * Optimized ROI by 48% in A/B test promotional experiments in the market of Panama, over a period of 8 months.
    * Developed an algorithm targeting first-time purchasers, optimizing discount allocation and saving on budget.
    * Designed and implemented causal inference models (X-Learner, T-Learner, Synthetic DiD) to assess market innovation impacts (ATT, CATE), enabling trend identification at the blocking factor level.


* 2022-2023: Data Scientist, Product Recommendation
  * [Santa Cruz Bank](https://bsc.com.do/home)
  * Duties included:
    * Optimized the product recommendation (NBA) feature pipeline from having < 20 to > 50 variables, into a collaborative filtering, ranking, and ensemble learning approach.
    * Enhanced customer segmentation by incorporating digital behavior clustering and psychographic profiling based on commerce data.
    * Automated weekly client account reporting via a data pipeline job, boosting productivity 3x and eliminating manual data wrangling.
    * Applied NLP techniques (sentiment analysis, n-grams, entity classification) to extract insights from Salesforce CRM interaction data.


* 2019-2022: Data Scientist, Risk Analytics
  * [Dominican Tax Administration](https://dgii.gov.do/Paginas/default.aspx)
  * Duties included:
    * Collaborated in developing the analytics & machine learning feedback system to label taxpayers as risky or not risky.
    * Mapped shareholding structures using graph theory (NetworkX, Bokeh) to identify central entities and uncover hidden transactional relationships, improving the detection and prioritization of tax evasion cases by 2x.
    * Built models such as linear regression, decision trees, PCA, and clustering.
    * Created the Data Warehouse inventory eCatalog, a Shiny (R) solution mapping all data infrastructure used for risk estimations (metadata, data dictionaries, data lineage). This streamlined the process of identifying data sources by 5x.



Skills
======
* Git
* Python
* R
* Data Science & AI Techniques: Propensity score matching (PSM), A/B/n testing, RCTs, synthetic controls, regularization, among others.
* Spark
* MLflow
* Azure Cloud: Azure Databricks, DL/Hive, Azure Machine Learning Studio, Azure DevOps, and Azure Synapse Analytics. AWS: Amazon SageMaker, Amazon Redshift, Athena, AWS Glue.
* Additional Tools: SQL, MATLAB, Java, CPLEX, Gurobi, PuLP.


Leadership
======
* AB InBev Analytics Workshop Professor (2024)
* AB InBev Global Hackathon (2023)
* R Programming Mentor (2022-2023)



Last updated: {{ "now" | date: "%Y-%m-%d" }}
