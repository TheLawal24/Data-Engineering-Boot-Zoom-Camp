# Data-Engineering-Boot-Zoom-Camp
Start: 17 January 2022
Registration link: https://airtable.com/shr6oVXeQvSI5HuWD
Register in DataTalks.Club's Slack
Join the #course-data-engineering channel
Subscribe to our public Google Calendar (it works from Desktop only)
The videos are published to DataTalks.Club's YouTube channel in the course playlist
Leaderboard
Syllabus

Note: This is preliminary and may change
Week 1: Introduction & Prerequisites

Course overview
Introduction to GCP
Docker and docker-compose
Running Postgres locally with Docker
Setting up infrastructure on GCP with Terraform
Preparing the environment for the course
Homework
More details

Week 2: Data ingestion

Data Lake
Workflow orchestration
Setting up Airflow locally
Ingesting data to GCP with Airflow
Ingesting data to local Postgres with Airflow
Moving data from AWS to GCP (Transfer service)
Homework
More details

Week 3: Data Warehouse

Goal: Structuring data into a Data Warehouse

Instructor: Ankush

Data warehouse (BigQuery) (25 minutes)
What is a data warehouse solution
What is big query, why is it so fast, Cost of BQ, (5 min)
Partitoning and clustering, Automatic re-clustering (10 min)
Pointing to a location in google storage (5 min)
Loading data to big query & PG (10 min) -- using Airflow operator?
BQ best practices
Misc: BQ Geo location, BQ ML
Alternatives (Snowflake/Redshift)
Duration: 1-1.5h

Week 4: Analytics engineering

Goal: Transforming Data in DWH to Analytical Views

Instructor: Victoria

Basics of analytics engineering (15 mins)
Developing a dbt project (Combination of coding + theory) (1:30)
Visualising the data in Google data studio (15 mins)
Duration: 2h

More details

Week 5: Batch processing

Goal:

Instructor: Alexey

Distributed processing (Spark) (40 + ? minutes)
What is Spark, spark cluster (5 mins)
Explaining potential of Spark (10 mins)
What is broadcast variables, partitioning, shuffle (10 mins)
Pre-joining data (10 mins)
use-case
What else is out there (Flink) (5 mins)
Extending Orchestration env (airflow) (30 minutes)
Big query on airflow (10 mins)
Spark on airflow (10 mins)
Duration: 1-1.5h

Week 6: Streaming

Goal:

Instructor: Ankush

Basics
What is Kafka
Internals of Kafka, broker
Partitoning of Kafka topic
Replication of Kafka topic
Consumer-producer
Schemas (avro)
Streaming
Kafka streams
Kafka connect
Alternatives (PubSub/Pulsar)
Duration: 1.5h

Week 7, 8 & 9: Project

Putting everything we learned to practice
Duration: 2-3 weeks

Upcoming buzzwords
Delta Lake/Lakehouse
Databricks
Apache iceberg
Apache hudi
Data mesh
KSQLDB
Streaming analytics
Mlops
Duration: 30 mins

Overview

Architecture diagram



Technologies

Google Cloud Platform (GCP): Cloud-based auto-scaling platform by Google
Google Cloud Storage (GCS): Data Lake
BigQuery: Data Warehouse
Terraform: Infrastructure-as-Code (IaC)
Docker: Containerization
SQL: Data Analysis & Exploration
Airflow: Pipeline Orchestration
DBT: Data Transformation
Spark: Distributed Processing
Kafka: Streaming
Prerequisites

To get most out of this course, you should feel comfortable with coding and command line, and know the basics of SQL. Prior experience with Python will be helpful, but you can pick Python relatively fast if you have experience with other programming languages.

Prior experience with data engineering is not required.

Instructors

Ankush Khanna (https://linkedin.com/in/ankushkhanna2)
Sejal Vaidya (https://linkedin.com/in/vaidyasejal)
Victoria Perez Mola (https://www.linkedin.com/in/victoriaperezmola/)
Alexey Grigorev (https://linkedin.com/in/agrigorev)
Tools

For this course you'll need to have the following software installed on your computer:

Docker and Docker-Compose
Python 3 (e.g. via Anaconda)
Google Cloud SDK
Terraform
See Week 1 for more details about installing these tools

Questions

Asking questions in Slack

You can ask any questions in the #course-data-engineering channel in DataTalks.Club slack

Please follow these recommendations when asking for help

FAQ

Q: I registered, but haven't received a confirmation email. Is it normal? A: Yes, it's normal. It's not automated. But you will receive an email eventually
Q: At what time of the day will it happen? A: Office hours will happen on Mondays at 17:00 CET. But everything will be recorded, so you can watch it whenever it's convenient for you
Q: Will there be a certificate? A: Yes, if you complete the project
Q: I'm 100% not sure I'll be able to attend. Can I still sign up? A: Yes, please do! You'll receive all the updates and then you can watch the course at your own pace.
Q: Do you plan to run a ML engineering course as well? A: Glad you asked. We do :)
Our friends

Big thanks to other communities for helping us spread the word about the course:

DPhi
MLOps.community
Check them out - they are cool!
