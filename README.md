# Olá 👋, eu sou o Eduardo Yoshio

Português · [English](#english)

Analista de dados e BI em São Paulo. Trabalho do dado bruto ao dashboard: modelo camadas bronze, silver e gold em SQL, versiono as transformações e entrego relatórios em Power BI que as áreas de negócio usam no dia a dia.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eduardo-yoshio-852543163/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?logo=gmail&logoColor=white)](mailto:eduardo.y.nakahara@gmail.com)

### 🚀 Projetos

| Projeto | O que mostra | Stack |
|---|---|---|
| **[lab-pipeline-openmeteo](https://github.com/EduardoYoshioNakahara/lab-pipeline-openmeteo)** | Pipeline diário ponta a ponta: landing particionada, bronze → silver → gold em Delta, checagem de qualidade que derruba o Job, alerta de falha parcial, time travel para desfazer uma carga errada e relatório Power BI em PBIP | Databricks · Delta Lake · Python · SQL · Power BI · GitHub Actions |
| **[lab-memecoins-bi](https://github.com/EduardoYoshioNakahara/lab-memecoins-bi)** 🚧 | Coleta horária de duas APIs públicas com rate limit por host, log por chamada, bronze append-only com MERGE idempotente e watchlist com regras de entrada e saída | Databricks · PySpark · SQL |
| **[Analise_Olist-Narrativa_Executiva](https://github.com/EduardoYoshioNakahara/Analise_Olist-Narrativa_Executiva)** | 96 mil pedidos de e-commerce: pedidos atrasados têm nota média de 2,3 contra 4,3 no prazo; health score por estado, churn, RFM e recomendações de negócio | Python · pandas · matplotlib · seaborn |

### 🔧 O que eu faço
- **SQL** em BigQuery e Databricks: modelagem em camadas, MERGE incremental, deduplicação e checagens de qualidade
- **Dataform / Delta Lake** para transformações versionadas e reprocessáveis
- **Power BI**: modelagem semântica, DAX, segurança por linha (RLS) e projetos em PBIP versionados no Git
- **Python** para ingestão de APIs e automação (requests, pyarrow, pandas)
- **Git e GitHub Actions** em todo o fluxo: branch, PR e deploy só depois do merge

### 🧭 Como eu trabalho
Desconfio de execução verde. Valido pelo efeito nos dados: contagem contra o calendário, duplicidade na chave, frescor por camada. Grande parte do meu trabalho é investigar por que um número não bate, começando pelo fim da cadeia e voltando até a origem.

### 🎯 Próximos passos
Aprofundar em engenharia de analytics: orquestração como código, testes de dados e CI/CD para pipelines.

### ⚽ Fora do trabalho
Sou apaixonado por esportes e gosto de procurar padrões neles com dados.

### 🛠️ Ferramentas
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?logo=googlebigquery&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

---

<a id="english"></a>
## English

Data & BI analyst based in São Paulo, Brazil. I work from raw data to dashboard: I model bronze, silver and gold layers in SQL, version every transformation and ship Power BI reports that business teams use every day.

### 🚀 Projects
- **[lab-pipeline-openmeteo](https://github.com/EduardoYoshioNakahara/lab-pipeline-openmeteo)**: end-to-end daily pipeline on Databricks over a public API. Partitioned landing, bronze → silver → gold in Delta, a quality gate that fails the job, partial-failure alerts, time travel to undo a bad load and a Power BI report in PBIP.
- **[lab-memecoins-bi](https://github.com/EduardoYoshioNakahara/lab-memecoins-bi)** 🚧: hourly ingestion from two public APIs with per-host rate limiting, a per-call run log, append-only bronze with idempotent MERGE and a rule-based watchlist.
- **[Analise_Olist-Narrativa_Executiva](https://github.com/EduardoYoshioNakahara/Analise_Olist-Narrativa_Executiva)**: 96k e-commerce orders; late orders average a 2.3 rating vs. 4.3 for on-time ones. State health score, churn, RFM and business recommendations.

### 🔧 What I do
- **SQL** on BigQuery and Databricks: layered modeling, incremental MERGE, deduplication and data quality checks
- **Dataform / Delta Lake** for versioned, reprocessable transformations
- **Power BI**: semantic modeling, DAX, row-level security (RLS) and PBIP projects versioned in Git
- **Python** for API ingestion and automation (requests, pyarrow, pandas)
- **Git and GitHub Actions** across the workflow: branch, PR and deploy only after merge

### 🧭 How I work
I don't trust a green run. I validate by the effect on the data: row counts against the calendar, duplicate keys, freshness per layer. Much of my work is figuring out why a number doesn't add up, starting at the end of the chain and tracing it back to the source.

### 🎯 Next steps
Going deeper into analytics engineering: orchestration as code, data testing and CI/CD for pipelines.
