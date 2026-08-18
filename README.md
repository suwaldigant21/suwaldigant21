<h1 align="center">Digant Suwal</h1>
<h3 align="center">Cloud Data Engineer — AWS-Certified | Building production-grade data & MLOps pipelines</h3>

<p align="center">
I design and ship data systems on AWS: batch and streaming pipelines, lakehouse architectures, and the MLOps layer on top of them. Every project below is a working, reproducible build — not a tutorial clone — with real bugs found, real numbers measured, and real infrastructure-as-code behind it.
</p>

<p align="center">
<a href="https://www.linkedin.com/in/digantsuwal/">LinkedIn</a> ·
<a href="mailto:digantsuwal21@gmail.com">Email</a> ·
📍 Nepal
</p>

---

### 🧰 Tech Stack

**Languages**
`Python` `SQL` `Java`

**AWS**
`S3` `Glue` `Athena` `Redshift` `Aurora` `DynamoDB` `Lambda` `Step Functions` `EventBridge` `SNS` `SQS` `Kinesis` `SageMaker` `Bedrock` `EC2` `VPC` `IAM` `KMS` `CloudWatch` `API Gateway` `Route 53` `Amplify`

**Data Engineering**
`Apache Airflow` `dbt` `PySpark` `Redpanda` `T-SQL` `Power BI` `Simba ODBC`

**Infrastructure & DevOps**
`Terraform` `CloudFormation` `Docker` `ECS` `ECR` `Git` `GitHub Actions` `CI/CD` `Linux`

**ML**
`XGBoost` `Scikit-learn` `Pandas` `NumPy` `R / caret`

---

### 🚀 Featured Projects

#### [CareMatrix — Healthcare Risk Adjustment & MLOps Lakehouse](https://github.com/suwaldigant21/CareMatrix_Healthcare_Data_Lakehouse-MLOps_Pipeline)
`AWS (S3, Athena, Glue)` `dbt` `PySpark` `XGBoost` `Power BI` `Terraform`

Serverless data lakehouse processing 66K+ raw Medicare claims through PySpark and dbt into 303K+ HIPAA-aligned, PHI-masked risk scores across 110K+ patients — implementing CMS's actual CMS-HCC hierarchy-exclusion methodology sourced from official government reference files, not an approximation. Decoded CMS's proprietary SAS-format risk model coefficients (268 verified weight factors) after finding no open-source reader for the format. Built an XGBoost readmission model on 45K+ patient-years (ROC-AUC 0.778) with dynamic class weighting for severe imbalance, served through Power BI via Athena/Simba ODBC. Full IaC on Terraform with least-privilege IAM and cost-optimized Parquet storage.

#### [StreamGuard — Real-Time Fraud Detection & Streaming MLOps Pipeline](https://github.com/suwaldigant21/Stream-Guard)
`AWS (S3, Athena, Glue, CloudWatch, SNS)` `Redpanda` `PySpark` `dbt` `XGBoost` `Terraform` `FastAPI`

Streaming fraud-detection pipeline (Redpanda → PySpark Structured Streaming → dbt/Athena) processing 6.3M+ transactions with zero data loss, scaling a modeling approach first validated on a 24K-row academic sample (R, 0.93 AUC) to production-scale class imbalance (1:560). Diagnosed a production data-loss bug via CloudTrail/IAM/EventBridge forensics, traced it to dbt-athena's relation-replacement semantics, and redesigned medallion layer boundaries to eliminate the failure class entirely. Deployed an XGBoost classifier with a PR-curve-derived threshold, cutting false positives from 30,545 to 77 while retaining 73% recall (PR-AUC 0.855), served live via FastAPI. Full observability (CloudWatch, SNS, dead-man's-switch liveness alarm) plus a verified GDPR Article 17 right-to-erasure endpoint. Terraform-provisioned under a strict $3–5 budget ceiling, backed by 66 automated tests.

#### [SQL Data Warehouse — Local Build & AWS Cloud Deployment](https://github.com/suwaldigant21/sql-data-warehouse-project)
`T-SQL` `AWS S3, Glue, Step Functions, Athena, EventBridge, SNS` `Terraform` `Power BI`

Local SQL Server warehouse consolidating ERP and CRM sources through a Bronze → Silver → Gold pipeline into a star schema, then rebuilt as a cloud-native version: S3 for storage, Glue for transformation, Step Functions for orchestration, EventBridge-triggered runs with SNS failure alerting. Curated Gold-layer datasets exposed through Athena for Power BI, all infrastructure provisioned via Terraform under least-privilege IAM.

---

### 📜 Certifications

- **AWS Certified Solutions Architect – Associate** (SAA-C03) — 758/1000
- **AWS Certified Machine Learning Engineer – Associate** (MLA-C01) — 803/1000
- **AWS Certified Data Engineer – Associate** (DEA-C01) — 743/1000
- **AWS Microcredentials**: Serverless Demonstrated · Data Lakehouse Demonstrated · Data Streaming Demonstrated

---

### 📊 GitHub Stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=suwaldigant21&show_icons=true&theme=default&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=suwaldigant21&layout=compact&hide_border=true" />
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=suwaldigant21&hide_border=true" />
</p>
