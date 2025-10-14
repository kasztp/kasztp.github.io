# 📑 Relevant Projects

This document outlines my most important professional & personal projects across various industries & domains, focusing on expertise in
**Data Engineering, Machine Learning (ML), Generative AI (GenAI), and Databricks Solution Architecture**.

---

## ML and GenAI Development

| Category | Details |
| :--- | :--- |
| **Business Domain** | **ML model and GenAI development** for audit-related business problems for a **Big4 client**. |
| **Project Description** | Developed various **ML models and GenAI tools** for high-impact business problems.<br><br>Key deliverables included:<br>- Binary and multi-class **classification models** for project records and reports.<br>- **LLM assisted processing** of client supplied files in various formats (text, Excel, PDF, images, zip files, folders).<br>- **Automated data extraction and enrichment** from finance documents (e.g. balance sheets, invoices, fund reports).<br>- Built business-facing reporting **dashboards and lightweight UI** for the AI tools. |
| **Tech Stack** | **Azure** (ADLS Gen2, AI Document Intelligence, AI Content Understanding, Azure OpenAI)<br>**Databricks** (Delta Lake, Unity Catalog, Vector Search, Jobs & Workflows, REST API)<br>**Python**<br>**SQL** |
| **Role(s)** | **ML Engineer**, **Data Engineer**, **Data Scientist**<br>**Databricks Solution Architect**<br>Note: Roles were often overlapping, sometimes on parallel projects. |

| Category | Details |
| :--- | :--- |
| **Business Domain** | PoC for ML use cases on Databricks. |
| **Project Description** | Proof of concept for an Enterprise client of Databricks.<br><br>Showcasing machine learning workflows using Databricks platform, including model training, deployment, and integration with various data sources. |
| **Tech Stack** | **Databricks** (MLflow, Delta Lake, Unity Catalog)<br>**Python**<br>**Apache Spark** |
| **Role(s)** | **Data engineer** |

---

## Near Real-time ELT of Australian Energy Market Data

| Category | Details |
| :--- | :--- |
| **Business Domain** | Near real-time **ELT solution for Australian Energy Market Operator data**. |
| **Project Description** | Migrated the Australian subsidiary of a major energy company from a slow, costly legacy **Oracle** system that couldn't handle modern **ML workloads**.<br><br>Notable features:<br>- Custom solution using **Azure and Databricks** reduced data availability time for traders from $\sim$**24 hours to less than 5 minutes**, significantly cheaper than the old solution.<br>- Enabling new use cases, such as predicting energy demand & prices and "day-trading" electricity (coupled with client's battery farm data) , resulting in multiple **\$10-100k USD extra profit daily**.<br>- System uses Azure Blob Storage/ADLS Gen2 to land data, then Databricks AutoLoader and **Spark streaming** to ingest files as they arrive.<br>- Utilizes a custom Python parser to unzip files (also in streaming fashion), process the AEMO proprietary format, and separate data into $\sim$ **800 different tables**. The data is available via **Unity Catalog** as **Delta tables**. |
| **Tech Stack** | **Azure** (ADLS Gen2, Blob storage, Azure Data Factory)<br>**Databricks** (Delta Lake, Unity Catalog, AutoLoader, Jobs & Workflows)<br>**Python**, **Pandas**<br>**Apache Spark** |
| **Role(s)** | **Data Engineer** |

---

## SAP HANA/BODS to Azure Databricks Migration (Retail Analytics)

| Category | Details |
| :--- | :--- |
| **Business Domain** | **SAP HANA/BODS to Azure Databricks migration of a Global Retail Analytics platform**. |
| **Project Description** | Migration and refactoring of an enterprise-scale Retail Analytics & Reporting platform from an end-of-life **SAP HANA & Business Object Data Services (BODS)** solution to a modern **Databricks-based system on Azure**.<br><br>Key deliverables:<br>- Redesign of the entire architecture for better performance and to better suit business needs.<br>- Rewrote and optimized all legacy **SAP HANA SQL code, SAP Calculation Views, and procedures** to **Databricks SQL and Spark native Python code**. |
| **Tech Stack** | **Azure** (ADLS Gen2)<br>**Databricks** (Delta Lake, Unity Catalog, Delta Live Tables, Jobs & Workflows)<br>**Apache Spark**<br>**SQL**<br>**Python** |
| **Role(s)** | **Data Engineer**<br>**Solutions Consultant** |

---

## Spark-Native Payments Reconciliation

| Category | Details |
| :--- | :--- |
| **Business Domain** | **Spark-native, highly scalable Payments Reconciliation**. |
| **Project Description** | Addressed a huge backlog of financial records (tens of millions of invoice items and payment transactions) traditionally reconciled manually by a large team. The manual process took $\sim$20 FTEs over a year for a single account with only $\sim$100k items.<br><br>- Achieved **multi-million USD cost savings** and huge efficiency gains by making the process mostly **automatic and fully scalable**.<br>- Solution extracts items from **SAP FI**, then executes preprocessing and a custom matching algorithm on **Databricks** using **Spark**.<br>- **Azure Data Factory** manages extraction from and loading to SAP, and triggers the **Databricks Workflow** for the reconciliation process. |
| **Tech Stack** | **Azure** (ADLS Gen2, ADF)<br>**Azure Databricks** (Delta Lake, Unity Catalog, Workflows)<br>**Apache Spark**<br>**Python, Pandas** |
| **Role(s)** | **Data Engineer** |

---

## Optimization & Consulting (various use cases & clients)

| Category | Details |
| :--- | :--- |
| **Business Domain** | **Cost and performance optimization** of **Apache Spark & Databricks** workloads,<br>**Architecture reviews and best practice workshops**. |
| **Project Description** | **Optimization** (Delivered 30+ smaller use cases):<br>- Optimized performance of existing **SQL or Python** (sometimes Scala) code.<br>- Refactored code to run efficiently on Spark/Databricks, or **optimized architecture for reducing operation cost**.<br><br>**Consulting & Workshops** (Ranging from Startup to Enterprise clients, mainly NL, UK, DE, ES):<br>- Reviewed architecture, suggested improvements, and identified performance and cost optimization opportunities.<br>- Held various **Databricks-related workshops** (e.g., Delta Lake, Unity Catalog, migration, integration with systems like Power BI/MSSQL/PowerApps) and general workshops (e.g., Data Governance, DevOps in data, MLOps). |
| **Tech Stack** | **Azure** (ADLS Gen2, Blob storage, ADF) **AWS**, **GCP**<br>**Databricks** (Delta Lake, Unity Catalog, AutoLoader, Jobs & Workflows, Vector Search, Model Serving, DLT, Lakeflow)<br>**Apache Spark**<br>**Python** (PySpark, Pandas, NumPy, MLFlow, etc.)<br>**SQL** |
| **Role(s)** | **Data Engineer**, **ML Engineer**<br> **Solutions Consultant**, **Resident Solutions Architect** |

---

## Slack Integrated Databricks Automation

| Category | Details |
| :--- | :--- |
| **Business Domain** | **Slack integrated Databricks automation**. |
| **Project Description** | Developed a **Slack Bot** with integrated **Databricks cluster management capabilities** and notifications for users to better control company-wide Databricks resource consumption. (As part of a team. I was responsible for Databricks API integration and end 2 end Cluster management workflow.) |
| **Tech Stack** | **Databricks** (Delta Lake, Unity Catalog, REST API) , **Python** , **Slack Python SDK** |
| **Role(s)** | **Full-stack developer** |

---

## Personal Projects

### AI & LLM

- **Project Health Status Analyzer**: An AI-powered tool to analyze and assess the health status of projects using LLM & RAG (with ChromaDB).
- **AI CV Generator**: A generative AI application for creating customized CVs/resumes based on user input and templates.
- **AWS Deepracer**: Autonomus racing of robocars based on reinforcement learning. (Participated in the official leauge for more than 5 years.)

### Data Engineering

- **HASS Databricks**: Integration project for connecting Home Assistant (smart home automation) with Databricks for data processing and analytics.
- **Databricks Exam Guide**: A comprehensive guide and study summary for Databricks certification exams, including tips and resources.

### Webapps & API Experiments

- **Map route creator**: A web application for creating and visualizing routes on maps, based on uploaded or user drawn pictures.
- **Sourcingtool**: A web-based tool (with Google based login and user management) for sourcing and ranking candidates based on LinkedIn & Github profiles.
- **HR_Ranking**: Ranking of Hungarian HR service providers based on the offical list of providers, and their Google Maps reviews.
- **URL_Shortener**: A simple URL shortening service with API for creating short links.
- **TextCompression**: A simple experiement for a text-compression service.

### Games & Game Helpers

- **Ninja_vs_Bakugan**: A game about a Ninja who battles against Bakugan creatures. (Entry for PyGames hackathon.)
- **Letterpress_Helper**: A helper tool for the Letterpress word game, providing word suggestions.
- **Wordle_Helper**: An assistant for the Wordle puzzle game, offering hints and possible solutions.
- **Szolanc**: A Hungarian word-based game helper.
- **Scrabble**: A Scrabble game helper with word validation and scoring in English and Hungarian.
- **SudokuAPI & backtracking Sudoku solvers**: A Sudoku API and a small collection of backtracking solvers implemented in multiple languages including pure Python (with some heuristics), NumPy, Go, and Julia for solving Sudoku puzzles efficiently.

---

### Participation in the Hungarian National IT Competition

- **2023**: I challenged myself to [enter and try to do my best in all categories](https://www.linkedin.com/pulse/my-oitm-2024-experience-journey-learning-challenges-peter-kaszt-8vh1f/).
  - **10th place** in **Azure Cloud** category
  - **18th place** in **Cyber Security** category
  - **29th place** in **Cloud BI** category
  - **Top 7%** in **Using LLMs** category
  - **Top 25** in 4 other categories
  - **Top 10%** in AI, Linux, DevOps categories

- **2022**: To my surprise I got into the Top 25 in one category.
  - **Top 25** in **Embedded Systems** category
