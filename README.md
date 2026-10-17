# Hi there, I'm Daffa 👋 (`@Srndraaaa`)

<p align="left">
  <a href="https://github.com/Srndraaaa"><img src="https://img.shields.io/github/followers/Srndraaaa?label=Followers&style=flat-square&color=blue" alt="GitHub Followers"></a>
  <a href="https://www.linkedin.com/in/daffa-sarendra-78944937b"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Focus-Data%20Engineering%20%7C%20ETL%20%7C%20IoT-2ea44f?style=flat-square" alt="Focus">
</p>

> **Data Science student at Universitas Muhammadiyah Semarang who likes the unglamorous half of data work: scheduled ETL, idempotent upserts, Docker Compose, and the health dashboard everyone ends up checking anyway.**
>
> My repos are mostly pipelines and screeners: weather data from Open-Meteo into PostgreSQL with its own monitoring dashboard, Binance ETH/USDT candles into NeonDB on a schedule, and a swing-trading screener with a documented filtering pipeline. Off the keyboard I lead a division at HIMASDA Unimus — managing cross-functional teams and branding — and I run Debian as a daily driver, mostly to keep myself honest about what actually runs where.

---

## 🚀 Featured GitHub Projects

### 🧩 Data Engineering & Pipelines

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/Srndraaaa/Simple-ETL-Pipeline-For-Weather-API-Open-Mateo">🌤️ Weather ETL (Open-Meteo)</a></h3>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
      </p>
      <p>Open-Meteo weather ETL into PostgreSQL — extraction with retry and timeout, normalization, idempotent upserts, run history, and an internal dashboard for pipeline health and data quality. Runs automatically every 2 hours, or manually on demand via Docker Compose.</p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/Srndraaaa/eth-project">🪙 ETH Market Data Pipeline</a></h3>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/Binance%20API-F0B90B?style=flat-square" alt="Binance API">
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
      </p>
      <p>Scheduled ingestion of Binance ETHUSDT 15m klines into a NeonDB PostgreSQL database — environment-based configuration, batched <code>execute_values</code> inserts, and structured logging for each run.</p>
    </td>
  </tr>
</table>

### 📈 Market Screening & Analysis

<table>
  <tr>
    <td colspan="2">
      <h3><a href="https://github.com/Srndraaaa/Alpha-Swing">📊 AlphaSwing US</a></h3>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/spec-v3.0%20documented-2ea44f?style=flat-square" alt="Documented spec">
      </p>
      <p>Swing-trading stock screener built around a top-down filtering funnel: multi-layer screening driven by macro conditions, mathematical scoring, hard-stop disqualification rules, response caching, and a watchlist workflow — specified in a written technical document and covered by tests (Finnhub API data).</p>
    </td>
  </tr>
</table>

### 📦 Datasets

- **[dataset-private](https://github.com/Srndraaaa/dataset-private)** — Working datasets for coursework and experiments: software defect prediction and UMKM credit-application classification.

---

## 🛠️ Tech Stack & Skills

<div align="left">

### 💻 Languages & Query

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
</p>

### 🗄️ Databases

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
</p>

### 🚢 Infrastructure & Tooling

<p>
  <img src="https://img.shields.io/badge/Docker%20%26%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

### 🧠 Data Science & ML

<p>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
</p>

</div>

---

## 📊 GitHub Analytics & Metrics

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Srndraaaa&theme=tokyonight" alt="Daffa's GitHub Profile Details" width="100%">
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Srndraaaa&theme=tokyonight" alt="Top Languages by Repo" width="49%">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Srndraaaa&theme=tokyonight" alt="GitHub Repository & Contribution Stats" width="49%">
</p>

---

## 🌱 Current Engineering Focus

- 🔁 **ETL & Orchestration** — making scheduled pipelines boring and reliable; Apache Airflow is next on the list.
- 🧪 **Data Quality & Monitoring** — run history, health checks, and dashboards that make a broken pipeline obvious.
- 🐳 **Containerized Data Stacks** — Docker Compose as the default way to ship reproducible data environments.
- 📡 **IoT & Applied Projects** — prior experience leading an IoT-based smart farming project, from sensors to dashboard.

---

## 📫 Connect & Collaborate

- **GitHub**: [@Srndraaaa](https://github.com/Srndraaaa)
- **LinkedIn**: [daffa-sarendra](https://www.linkedin.com/in/daffa-sarendra-78944937b)

Always open to collaborating on **Data Engineering, Machine Learning, or IoT** projects.

---

<p align="center">
  <i>"Raw data in. Decisions out."</i>
</p>
