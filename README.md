<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1A1B27,100:00D9FF&height=220&section=header&text=Mangesh%20Jadhav&fontSize=42&fontColor=FFFFFF&fontAlignY=35&desc=Data%20Analyst%20%7C%20BI%20Developer%20%7C%20Cloud%20Analytics&descSize=18&descColor=00D9FF&descAlignY=55&animation=fadeIn" width="100%" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mangesh--jadhav)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mangeshjadhav948@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mangesh-Jadhav-2)

</div>

---

### 🧑‍💼 About Me

```yaml
Name:       Mangesh Jadhav
Role:       Data Analyst @ Probus Insurance
Education:  Executive MBA — IT & Analytics
Domain:     BFSI & Analytics
Focus:      Data Infrastructure · Cloud Analytics · Business Intelligence
```

- 🔹 Automated ETL pipelines achieving **70% performance improvement** in data processing throughput
- 🔹 Designed AWS Data Warehouse architectures using **S3 → Glue → Redshift**
- 🔹 Built **Power BI dashboards** with advanced DAX measures and semantic data models
- 🔹 Proficient in optimized SQL — parameterized CTEs, window functions, complex joins on multi-million row datasets

---

### 🛠️ Tech Stack

<div align="center">

#### 📦 Databases
![MS SQL Server](https://img.shields.io/badge/MS_SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

#### ⚙️ Data Engineering
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![AWS Glue](https://img.shields.io/badge/AWS_Glue-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![ETL Pipelines](https://img.shields.io/badge/ETL_Pipelines-FF6F00?style=for-the-badge&logo=apacheairflow&logoColor=white)

#### 📊 BI & Visualization
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

#### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)

</div>

---

### 🚀 Featured Projects

<table>
<tr><td>

#### 📈 [Analytics EDA Project](https://github.com/Mangesh-Jadhav-2/Analytics-EDA-Project)

> End-to-end Exploratory Data Analysis pipeline for multi-dimensional BFSI data profiling

**Stack:** `Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `SQL`

- Parameterized CTEs for reusable SQL query patterns
- Window functions for rolling aggregations & trend analysis
- Automated data quality checks across 20+ feature columns
- Outlier detection using IQR & Z-score methods
- Built reusable profiling templates — **reduced EDA effort by 60%**

</td></tr>
<tr><td>

#### 🤖 [RAG Reporting System](https://github.com/Mangesh-Jadhav-2/RAG-Reporting-System)

> For automated analytical report generation

**Stack:** `Python` · `LangChain` · `OpenAI API` · `SQL` · `Pandas` · `Jinja2`

- Semantic layer abstraction decoupling business logic from physical data models
- LLM-powered narrative generation with parameterized prompts
- Automated weekly report generation — **reduced manual effort by 80%**

</td></tr>
<tr><td>

#### 📊 [Performance Analytics Dashboard](https://github.com/Mangesh-Jadhav-2/Performance-Analytics-Dashboard)

> Enterprise KPI tracking dashboard for insurance analytics at Probus Insurance

**Stack:** `Power BI` · `DAX` · `MS SQL Server` · `Excel` · `Power Query`

- Star-schema data model (facts: transactions, claims; dimensions: agents, products, time)
- 15+ interactive reports with drill-through navigation
- Time-intelligence DAX measures — YTD, QoQ, Weighted, Rolling averages
- Row-level security (RLS) for multi-tenant access
- Incremental refresh for near-real-time reporting

</td></tr>
</table>

---

### 📐 End-to-End Data Pipeline Architecture

> *Actual production architecture built at Probus Insurance*

#### ⚙️ AWS Glue — ETL & Data Processing Layer

```mermaid
flowchart LR
    subgraph ON-PREM["🏢 On-Premise"]
        MSSQL[("🗄️ MS SQL Server")]
    end

    subgraph AWS_GLUE["☁️ AWS Glue"]
        direction TB
        ETL1["Visual ETL\MSSQL_to_AWS"]
        S3_RAW[("📦 S3 — MSSQL_Glue\(Raw Parquet)")]
        SPARK1["⚡ PySpark\Parquet_conso"]
        SPARK2["⚡ PySpark\Agent_master_update"]
        S3_CLEAN[("📦 S3 — BI_Parquet\CLEAN_upd")]
        S3_BIZ[("📦 S3 — Business Data\Production_data")]
        ETL2["Visual ETL\AWS to MS SQL"]
    end

    subgraph QUERY["🔍 Query Layer"]
        ATHENA["Amazon Athena\Basic Querying"]
    end

    subgraph DEST["🏢 Destination"]
        MSSQL2[("🗄️ On-PREM MS SQL\(Staged Back)")]
        GW["🌐 On-PREM Gateway"]
    end

    MSSQL -- "JDBC via VPN" --> ETL1
    ETL1 --> S3_RAW
    S3_RAW --> SPARK1
    S3_RAW --> SPARK2
    SPARK1 --> S3_BIZ
    SPARK2 --> S3_CLEAN
    S3_BIZ --> ATHENA
    S3_BIZ --> ETL2
    ETL2 --> MSSQL2
    MSSQL2 --> GW

    style ON-PREM fill:#1a1b27,stroke:#00d9ff,color:#fff
    style AWS_GLUE fill:#1a1b27,stroke:#FF9900,color:#fff
    style QUERY fill:#1a1b27,stroke:#8C4FFF,color:#fff
    style DEST fill:#1a1b27,stroke:#47A248,color:#fff
```

#### 📊 Power BI — Semantic Model & Report Layer

```mermaid
flowchart LR
    subgraph SOURCES["🔌 Data Sources"]
        SQL[("🗄️ SQL Server\On-PREM Gateway")]
        ATH[("🗄️ Amazon Athena\P24_Proj Gateway")]
    end

    subgraph TRANSFORM["⚙️ Dataflows"]
        DF["Dataset Gateway\(Dataflow Gen1)"]
    end

    subgraph MODELS["📐 Semantic Models"]
        SM1["Production_Report"]
        SM2["Production_Report\RLS for Motor"]
        SM3["Direct_Query\"]
    end

    subgraph REPORTS["📊 Reports"]
        R1["Production_Report\Overview"]
        R2["Management\nDashboard"]
        R3["Business Dashboard\RLS for Motor"]
        R4["Direct_Query\P24_Dashboard"]
    end

    SQL --> DF
    DF --> SM1
    DF --> SM2
    SM1 --> R1
    SM1 --> R2
    SM2 --> R3
    ATH --> SM3
    SM3 --> R4

    style SOURCES fill:#1a1b27,stroke:#CC2927,color:#fff
    style TRANSFORM fill:#1a1b27,stroke:#FF9900,color:#fff
    style MODELS fill:#1a1b27,stroke:#F2C811,color:#fff
    style REPORTS fill:#1a1b27,stroke:#00d9ff,color:#fff
```
---

<div align="center">

### 🤝 Let's Connect

💼 **Open to collaboration** on Data Infrastructure, Cloud Analytics, and BI projects

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mangesh--jadhav)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mangeshjadhav948@gmail.com)

<br/><br/>

*"Exploring data, building dashboards and uncovering insights that matter."*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1A1B27,100:00D9FF&height=120&section=footer" width="100%" />
