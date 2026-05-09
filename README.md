<div align="center">

# Hey, I'm Arham 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=500&lines=Aspiring+Cloud+Engineer;AWS+%7C+Terraform+%7C+Serverless;BS+Cybersecurity+%40+MAJU;Cloud+Engineering+%E2%86%92+Cloud+Security)](https://git.io/typing-svg)

</div>

---

## 🚀 About Me

I'm an aspiring **Cloud Engineer** from 🇵🇰 Karachi, Pakistan with hands-on experience building and automating cloud infrastructure and data pipelines. Currently studying **BS Cybersecurity at MAJU** and actively building toward a career in **Cloud Security Engineering**.

- 🔭 Currently studying **AWS Certified Developer Associate (DVA-C02)**
- 🛠️ Building production-grade projects with **AWS, Terraform, Python, and Snowflake**
- 🔐 Long-term focus: **Cloud Security Engineering**
- 📦 20+ public repositories on GitHub
- 💬 Ask me about **AWS, Serverless, IaC, and Data Pipelines**
- 📍 Based in Karachi — open to **cloud internships**

---

## 🛠️ Tech Stack

### **Cloud & Infrastructure**
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/terraformio/terraformio-icon.svg" alt="terraform" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/snowflake/snowflake-icon.svg" alt="snowflake" width="40" height="40"/>
</p>

### **CI/CD & DevOps**
<p align="left">
  <img src="https://www.vectorlogo.zone/logos/github/github-icon.svg" alt="github-actions" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/apache_airflow/apache_airflow-icon.svg" alt="airflow" width="40" height="40"/>
</p>

### **Languages & Tools**
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="sql" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="git" width="40" height="40"/>
</p>

### **AWS Services**

<p align="left">
  <img src="https://img.shields.io/badge/Amazon_S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white"/>
  <img src="https://img.shields.io/badge/EC2_&_Auto_Scaling-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"/>
  <img src="https://img.shields.io/badge/IAM_&_Security-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/VPC_&_Networking-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQS_&_SNS-FF9900?style=for-the-badge&logo=amazonsqs&logoColor=white"/>
  <img src="https://img.shields.io/badge/EventBridge-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/DynamoDB-FF9900?style=for-the-badge&logo=amazondynamodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/CloudWatch-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/CloudFormation-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/ECS_&_Containers-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white"/>
</p>
---

## 🚀 Featured Projects

### 🔐 Secure VPC Architecture — Terraform
> **Production-grade multi-AZ network infrastructure with defense-in-depth**

Modular multi-AZ VPC with three-tier subnet layout (public, private, data), ALB, NAT Gateway, RDS, VPC Endpoints for private AWS service access, and VPC Flow Logs.

```
Internet Gateway
      │
Public Subnets (ALB, NAT GW)
      │
Private Subnets (App Layer)
      │
Data Subnets (RDS, VPC Endpoints)
      │
VPC Flow Logs → CloudWatch
```

**Stack:** Terraform • VPC • ALB • NAT Gateway • RDS • VPC Endpoints • Multi-AZ

---

### 🌐 Multi-AZ High Availability Web App
> **Self-healing infrastructure demo**

Fault-tolerant web app across 2 AZs behind ALB + ASG. Instances terminated mid-traffic to verify zero-downtime auto-recovery.

**Stack:** EC2 • ALB • Auto Scaling Group • Multi-AZ • CloudWatch

---

### 🏆 Real-Time Multi-Source Data Pipeline — Hackathon
> **End-to-end automated pipeline integrating 3 live financial APIs**

```
CoinMarketCap ──┐
OpenExchangeRates ──┤──► S3 → SNS → SQS → Lambda → Glue (PySpark) → Snowflake
Yahoo Finance ──┘
                          EventBridge (Scheduled Triggers)
```

**Stack:** Python • Lambda • S3 • SNS • SQS • Glue • PySpark • Snowflake • EventBridge

---

### 📈 S&P 500 Real-Time Intraday Pipeline
> **Dockerized Airflow orchestration on EC2**

Fully automated ETL pulling live S&P 500 market data, transforming with pandas, and loading to S3 and Snowflake.

```
yfinance API → EC2 (Docker + Airflow) → Transform → S3 + Snowflake
```

**Stack:** Python • Apache Airflow • Docker • EC2 • S3 • Snowflake • pandas

---

### ⚡ Serverless Weather Forecasting Pipeline
> **EventBridge → Lambda → Snowpipe → Looker Studio**

Daily pipeline fetching Open-Meteo weather data, storing to S3, auto-ingesting via Snowpipe, and visualizing on Looker Studio.

**Stack:** Lambda • EventBridge • S3 • SQS • Snowflake Snowpipe • Looker Studio

---

### 📊 AWS Stock Data Pipeline
> **Serverless event-driven ETL**

Fully serverless pipeline generating and processing synthetic OHLCV stock data for 50 symbols.

```
EventBridge → Lambda → S3 → SQS → Lambda → DynamoDB
```

**Stack:** Lambda • EventBridge • S3 • SQS • DynamoDB

---

### 🏗️ Lake-to-Warehouse ETL Pipeline
> **S3 → Glue → Athena → Redshift**

Enterprise-style pipeline with Glue Crawler schema discovery, serverless querying with Athena, and warehousing in Redshift.

**Stack:** S3 • Glue • Athena • Redshift • Python • PySpark

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=syedshaaharham&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=syedshaaharham&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165">
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=syedshaaharham&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="400">
</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=syedshaaharham&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4" alt="GitHub Trophies">
</div>

---

## 📈 Activity Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=syedshaaharham&theme=tokyo-night&hide_border=true" alt="Activity Graph">
</div>

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Syed_Shah_Arham-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/syedshaharham)
[![GitHub](https://img.shields.io/badge/GitHub-syedshaaharham-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/syedshaaharham)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-FF9900?style=for-the-badge&logo=vercel&logoColor=white)](https://syedshaharham.vercel.app/)

</div>

---

<div align="center">

### 💡 "There's a difference between using AWS and understanding AWS. I'm closing that gap."

![Profile Views](https://komarev.com/ghpvc/?username=syedshaaharham&color=2E9EF7&style=flat-square)
[![GitHub followers](https://img.shields.io/github/followers/syedshaaharham?label=Follow&style=social)](https://github.com/syedshaaharham)

</div>
