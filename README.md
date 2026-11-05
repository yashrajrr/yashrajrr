<div align="center">

# Yashraj Rathor

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=2C9FC9&center=true&vCenter=true&width=780&lines=Building+multi-agent+systems+with+LangGraph+and+LangChain;LLM+routers+%7C+tool-using+agents+%7C+text-to-SQL+%7C+RAG;Data+pipelines+on+Azure+with+Databricks+and+PySpark;Final-year+IT+engineering+student+%7C+Navi+Mumbai" alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://leetcode.com/u/heat-code/"><img src="https://img.shields.io/badge/LeetCode-heat--code-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
<a href="mailto:yashrajrathor2005@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

---

## About

I'm a final-year B.E. Information Technology student at SIES Graduate School of Technology (University of Mumbai, CGPA 9.3/10). My work sits between data engineering and agentic AI: I build systems where LLM agents decide which tool to call, validate their own output, and run against real databases and APIs, and I build the data pipelines that feed them.

---

## General Info

| | |
|---|---|
| Name | Yashraj Radheshyam Rathor |
| Degree | B.E. Information Technology, SIES Graduate School of Technology (University of Mumbai) |
| CGPA | 9.3 / 10 |
| Location | Navi Mumbai, India |
| Focus | Agentic AI, data engineering, RAG |
| Contact | yashrajrathor2005@gmail.com |

---

## Featured Project: Agentic AI Data Analyst and ETL Automation Agent

A multi-agent system that takes a natural-language request and routes it to the right specialist: a SQL agent for questions about data, or an ETL agent for extraction and transformation jobs.

```mermaid
flowchart LR
    Q[Natural-language request] --> R{LLM router}
    R -->|question about data| S[SQL agent]
    R -->|extract / transform task| E[ETL agent]
    S --> W1[Question curation]
    W1 --> W2[Schema discovery]
    W2 --> W3[SQL generation]
    W3 --> W4[AI safety validation]
    W4 --> W5[PostgreSQL execution]
    W5 --> W6[Response generation]
    E --> T1[API extraction]
    T1 --> T2[Pandas transformations]
    T2 --> O[CSV / JSON / Parquet]
```

- **Routing:** an LLM-based router decides between the SQL agent and the ETL agent for each request.
- **SQL agent:** a 7-stage workflow covering question curation, schema discovery, SQL generation, AI-based safety validation, PostgreSQL execution, and response generation. The validation stage checks generated queries before they touch the database.
- **ETL agent:** tool-driven workflows for API extraction and Pandas transformations, with output in CSV, JSON or Parquet.
- **Stack:** Python, LangGraph, LangChain, PostgreSQL, Pandas.

---

## Other Projects

**Spotify End-to-End Data Engineering Pipeline on Azure** (Jul 2026 - Present)
Parameterized, metadata-driven ingestion in Azure Data Factory into Azure Data Lake Storage Gen2, with incremental loading and backfilling. Data is organized in a Bronze / Silver / Gold medallion architecture, with cleaning, transformation and validation done in Azure Databricks using PySpark.

**Memora Semantic Learning System** (Sep 2025 - Jun 2026)
A learning assistant built on Retrieval-Augmented Generation. It includes a document retrieval pipeline for educational content, semantic search, and answers generated from vector embeddings.

---

## Skills

| Area | Tools |
|---|---|
| Agentic AI | LangGraph, LangChain, RAG, multi-agent routing, vector embeddings |
| Data engineering | Azure Data Factory, Azure Data Lake, Databricks, PySpark, ETL |
| Languages and data | Python, SQL, OOP, Pandas, NumPy, PostgreSQL, MySQL |
| Tooling | Git, GitHub, CI/CD, Jupyter, Postman |

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/LangGraph-FF6F00?style=flat-square" alt="LangGraph"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="PySpark"/>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"/>

</div>

---

## Competitive Programming

<div align="center">

<a href="https://leetcode.com/u/heat-code/">
<img src="https://leetcard.jacoblin.cool/heat-code?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode stats for heat-code" width="85%"/>
</a>

</div>

---

## Experience

**Data Science Intern, Reva Technologies** (Jun - Jul 2025)
Analysed climate datasets with Python and SQL for rainfall forecasting, built and evaluated machine learning models for weather prediction, and did preprocessing and feature engineering to improve accuracy.

## Education

- **B.E. Information Technology**, SIES Graduate School of Technology, University of Mumbai. CGPA 9.3/10 (Aug 2023 - Present)
- 12th, Science, Shiravane Vidyalaya and Junior College. 65.17% (2021 - 2023)
- 10th, St. Xavier's High School and Jr. College, Maharashtra State Board. 89.00% (2020 - 2021)

## Certifications and Awards

- IBM (Coursera): Python for Data Science, AI and Development
- IBM (Coursera): Essential Tools for Data Scientists
- Postman: API Fundamentals Student Expert
- Second Prize, Cognition 2025 (SIES GST): led planning and execution of an AI-powered healthcare platform
- Class Representative, Student Council (2024 - 2025)

---

## GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=Yashrajrr&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub streak"/>

<br/><br/>


---

<div align="center">

yashrajrathor2005@gmail.com | Navi Mumbai, India

</div>
