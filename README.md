# 👋 Hi, I'm Felipe Castro
🎯 **Senior Data Engineer** | ☁️ **Microsoft Fabric & Azure Expert** | Data Engineering · Real-Time Analytics

I am a Senior Data Engineer with 8+ years of experience transforming complex data into strategic, AI-ready insights. I specialize in architecting scalable Medallion Lakehouses and Real-Time Streaming pipelines within the Microsoft Fabric ecosystem.

Currently at EPAM Systems, I focus on building robust ETL/ELT architectures and real-time analytics solutions that simplify complexity and drive business value.

🛠️ **Top Tech:** Microsoft Fabric | Delta Lake | Spark Structured Streaming | PySpark | Python

---

## 📌 Featured Projects
*Selected work showcasing end-to-end data engineering and AI-ready architectures.*

### 🧱 Microsoft Fabric & Data Engineering

* **[Real-Time Stock Volatility](https://github.com/felipecastro-data/real-time-stock-volatility-fabric)** **Tech:** Microsoft Fabric, Spark Structured Streaming, PySpark, yfinance API.
  **Impact:** Engineered a real-time streaming pipeline using Hopping Windows and Watermarking to analyze market volatility spikes with exactly-once processing semantics.

* **[Fabric Medallion CI/CD with Terraform](https://github.com/felipecastro-data/fabric-medallion-cicd-terraform)** **Tech:** Microsoft Fabric, Terraform, GitHub Actions, Deployment Pipelines, PySpark, Delta Lake.
  **Impact:** Built a production-grade Medallion lakehouse (1.6M Chicago bike trips + weather) provisioned with Terraform and promoted dev → test → prod by GitHub Actions with OIDC (no secrets) and an approval gate, guarded by 117 unit tests and a 45-check data-quality gate that blocks bad releases.

### 🏛️ Data Architecture & Data Governance

* **[Lakehouse Governance as Code](https://github.com/felipecastro-data/lakehouse-governance-as-code)** **Tech:** Databricks, Unity Catalog, Python, Databricks Asset Bundles, GitHub Actions, Delta Lake, AI/BI Dashboards.
  **Impact:** Declared Unity Catalog governance as code: YAML policy rendered by a Python engine into idempotent SQL and promoted dev → prod by GitHub Actions with a service principal and an approval gate, enforcing ABAC masking of PII, failing the pipeline on grant drift, honoring GDPR right-to-erasure, and publishing an auditor scorecard (100% owned, classified and PII-masked, 0 drift) guarded by 90 unit tests.

* **[Fabric Data Mesh with Purview Governance](https://github.com/felipecastro-data/fabric-domain-architecture-purview-governance)** **Tech:** Microsoft Fabric, Microsoft Purview, OneLake, Terraform, Microsoft Entra ID, GitHub Actions, Python.
  **Impact:** Designed a 3-domain data mesh on Fabric as code: producer and consumer domains publish data products through 12 OneLake shortcuts (485 MB served in place, 0 bytes copied), with least-privilege OneLake security roles enforced at every hop, plus Purview sensitivity labels, endorsement, tags and lineage. Two Terraform stacks deploy through GitHub Actions with OIDC and an approval gate, and a daily compliance check fails on any drift between the tenant and the code.

### 🤖 AI & Multi-Agent Systems

* **[Medallion Data Dictionary RAG](https://github.com/felipecastro-data/medallion-data-dictionary-rag-system)** **Tech:** Python, Databricks SQL, MCP, Anthropic API, Voyage AI, ChromaDB, Streamlit.
**Impact:** Built a RAG chatbot that auto-generates and answers questions about a data dictionary over a Databricks Medallion lakehouse, using a Claude-powered subagent to draft column descriptions and Voyage AI/ChromaDB retrieval to answer natural-language queries via the Anthropic API.

* **[Self-Healing Data Pipeline](https://github.com/felipecastro-data/self-healing-databricks-pipeline-multi-agent)** **Tech:** Claude Code, MCP, Databricks, PySpark, Python.
**Impact:** Built a diagnostic multi-agent system for failed Databricks PySpark jobs, chaining log-parser → classifier → patch-proposer subagents to classify each failure and propose a templated fix, with every patch gated behind human approval and logged to a full evidence trail.

---

## 📜 Certifications

- 🏅 **[DP-700: Microsoft Certified: Fabric Data Engineer Associate](https://learn.microsoft.com/api/credentials/share/en-us/FelipeCastro-8026/96572499DF943EBC?sharingId=13D660F56C1DFFA3)**
- 🏅 **[DP-600: Microsoft Certified: Fabric Analytics Engineer Associate](https://learn.microsoft.com/api/credentials/share/en-us/FelipeCastro-8026/6C5A2F5A8A5864FC?sharingId=13D660F56C1DFFA3)**
- 🏅 **[PL-300: Microsoft Certified: Power BI Data Analyst Associate](https://learn.microsoft.com/api/credentials/share/en-us/FelipeCastro-8026/F853AABE365874B3?sharingId=13D660F56C1DFFA3)**

---

## 🚀 Tools & Tech

![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-000000?style=flat&logo=Microsoft&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E34F26?style=flat&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-005C84?style=flat&logo=postgresql&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=flat&logo=databricks&logoColor=white)
![Unity Catalog](https://img.shields.io/badge/Unity%20Catalog-1B3139?style=flat&logo=databricks&logoColor=white)
![Microsoft Purview](https://img.shields.io/badge/Microsoft%20Purview-0078D4?style=flat&logo=microsoft&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat&logo=Microsoft%20Azure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat)

---

💬 *Let's connect and build amazing things with data.* 🔗 [LinkedIn](https://www.linkedin.com/in/felipecastro-data/)
