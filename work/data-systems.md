# Data ingestion and engineering metrics

At Crest Data, I work on the backend of an Engineering Insights platform. It collects data from DevOps, service management, and security tools to calculate metrics such as Lead Time, MTTR, Deployment Frequency, and Change Failure Rate.

## Ingestion

I rebuilt a ServiceNow pipeline that previously ran on cron jobs using Temporal. The workflows cover tickets, CMDB data, and changelogs, with checkpointing, retries, exponential backoff, and rate-limit handling.

I also built ingestion for Bitbucket Server and Bitbucket Cloud. The workers can run in the cloud or in a customer's own environment.

## Other work on the platform

- Built Spark and Iceberg transformation jobs with schema evolution and time-travel queries.
- Tuned SQL queries used to calculate engineering metrics.
- Worked on integrations with Snyk, Wiz, Jira, ServiceNow, GitHub, GitLab, and Azure DevOps.
- Diagnosed an Azure DevOps correlation defect and designed a fix that corrected more than 30 million mismatched production records.
- Proposed and built a scheduler to terminate long-running processes that were consuming unnecessary compute.

**Stack:** Java, Spring Boot, Temporal, Apache Spark, Iceberg, PostgreSQL, Redis, Elasticsearch, GCP, Jenkins.

[Back to profile](../README.md)
