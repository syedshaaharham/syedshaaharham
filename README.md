
## 👨‍💻 About Me

An aspiring Cloud Engineer with hands-on experience in building and automating cloud infrastructure and deployment pipelines. I have worked with technologies such as Python, AWS, Docker, Airflow, and Snowflake to develop scalable and efficient cloud-based solutions.

I am passionate about learning the art of cloud architecture, improving infrastructure performance, and keeping up with the latest advancements in cloud technology. I enjoy working in collaborative settings, embrace complex engineering challenges, and am committed to growing my skills through meaningful, real-world projects.

```
📍 Karachi, Pakistan
🔐  Focus: Cloud Engineering → Cloud Security
```

---

<div align="center">


[![LinkedIn](https://img.shields.io/badge/LinkedIn-Syed_Shah_Arham-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/syedshaharham)
[![GitHub](https://img.shields.io/badge/GitHub-syedshaharham--2006-181717?style=for-the-badge&logo=github)](https://github.com/syedshaaharham)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live_on_Vercel-FF9900?style=for-the-badge&logo=vercel&logoColor=white)](https://syedshaharham.vercel.app/)
</div>

---

## 🛠️ Technical Proficiency

**Cloud Infrastructure**

| Skill | Proficiency |
|---|---|
| Amazon S3 | `████████████████░░░░` Advanced |
| AWS Lambda | `████████████████░░░░` Advanced |
| EC2 & Auto Scaling | `████████████████░░░░` Advanced |
| IAM & Security | `███████████████░░░░░` Advanced |
| VPC & Networking | `█████████████░░░░░░░` Intermediate |
| SQS & SNS | `█████████████░░░░░░░` Intermediate |
| EventBridge | `█████████████░░░░░░░` Intermediate |
| DynamoDB | `████████████░░░░░░░░` Intermediate |
| CloudWatch & Logging | `████████████░░░░░░░░` Intermediate |
| CloudFormation | `█████████░░░░░░░░░░░` Developing |
| ECS & Containers | `█████████░░░░░░░░░░░` Developing |

**Languages & Tools**

| Skill | Proficiency |
|---|---|
| Python | `█████████████░░░░░░░` Intermediate |
| SQL | `█████████████░░░░░░░` Intermediate |
| Linux & Bash | `████████████░░░░░░░░` Intermediate |
| Git & GitHub | `████████████░░░░░░░░` Intermediate |

---

## 🚀 Featured Projects

### 🔐 Secure VPC Architecture — Terraform
> **Production-grade multi-AZ network infrastructure with defense-in-depth**

Designed and provisioned a modular, multi-AZ VPC using Terraform with a three-tier subnet layout (public, private, data), an Application Load Balancer, NAT Gateway, RDS, VPC Endpoints for private AWS service access, and VPC Flow Logs for full network visibility.
Internet Gateway
│
Public Subnets (ALB, NAT GW)
│
Private Subnets (App Layer)
│
Data Subnets (RDS, VPC Endpoints)
│
VPC Flow Logs → CloudWatch

**Stack:** Terraform • VPC • ALB • NAT Gateway • RDS • VPC Endpoints • VPC Flow Logs • Multi-AZ

---

### 🌐 Multi-AZ High Availability Web App
> **Self-healing infrastructure demo**

Deployed a fault-tolerant web app across 2 AZs behind ALB + ASG. Terminated instances mid-traffic to demonstrate automatic recovery — the app never went down.
ALB
├── AZ-1 (EC2 instance)
└── AZ-2 (EC2 instance)  ← terminated mid-traffic, ASG self-healed

**Stack:** EC2 • ALB • Auto Scaling Group • Multi-AZ • CloudWatch

### 🏆 Real-Time Multi-Source Data Pipeline — Hackathon
> **End-to-end automated pipeline integrating 3 live financial APIs**

Built an end-to-end automated pipeline integrating 3 live financial APIs into a unified data warehouse.

```
CoinMarketCap ──┐
OpenExchangeRates ──┤──► S3 → SNS → SQS → Lambda → Glue (PySpark) → Snowflake
Yahoo Finance ──┘
                                    EventBridge (Scheduled Triggers)
```

**Stack:** Python • AWS Lambda • S3 • SNS • SQS • AWS Glue • PySpark • Snowflake • EventBridge • SQL Server

---

### 📈 S&P 500 Real-Time Intraday Pipeline
> **Dockerized Airflow orchestration on EC2**

Fully automated ETL pipeline pulling live S&P 500 market data, transforming with pandas, and loading to both S3 and Snowflake.

```
yfinance API → EC2 (Docker + Airflow) → Transform → S3 + Snowflake
```

**Stack:** Python • Apache Airflow • Docker • AWS EC2 • S3 • Snowflake • pandas

---

### ⚡ Serverless Weather Forecasting Pipeline
> **EventBridge → Lambda → Snowpipe → Looker Studio**

Daily automated pipeline fetching Open-Meteo weather data, storing to S3, auto-ingesting via Snowpipe, and visualizing on Looker Studio.

**Stack:** Python • AWS Lambda • EventBridge • S3 • SQS • Snowflake Snowpipe • Looker Studio

---

### 📊 AWS Stock Data Pipeline
> **Serverless event-driven ETL**

Fully serverless pipeline generating and processing synthetic OHLCV stock data for 50 symbols using a complete event-driven architecture.

```
EventBridge → Lambda → S3 → SQS → Lambda → DynamoDB
```

**Stack:** Python • Lambda • EventBridge • S3 • SQS • DynamoDB

---

### 🌐 Multi-AZ High Availability Web App
> **Self-healing infrastructure demo**

Deployed a fault-tolerant web app across 2 AZs behind ALB + ASG. Terminated instances mid-traffic to demonstrate automatic recovery — the app never went down.

**Stack:** EC2 • ALB • Auto Scaling Group • Multi-AZ • CloudWatch

---

### 🏗️ Lake-to-Warehouse ETL Pipeline
> **S3 → Glue → Athena → Redshift**

Enterprise-style data pipeline with schema discovery via Glue Crawler, serverless querying with Athena, and warehousing in Redshift.

**Stack:** AWS S3 • AWS Glue • Athena • Redshift • Python • PySpark

---

## 📫 Let's Connect

I'm actively looking for **cloud internships** in Karachi.

If you're working on cloud infrastructure, data pipelines, or security — let's talk.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/syedshaharham)

---

<div align="center">

*"There's a difference between using AWS and understanding AWS. I'm closing that gap."*

</div>
