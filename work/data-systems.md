# Distributed data systems

**Professional work at Crest Data · Java · Spring Boot · Temporal · Spark · Iceberg · PostgreSQL**

I work on the ingestion, transformation, and metric computation behind an Engineering Insights platform. The platform brings data from DevOps, service management, and security tools into a consistent view of engineering delivery.

## Reliable ingestion

I rebuilt a legacy ServiceNow ingestion pipeline from static, cron-based jobs into Temporal-orchestrated workflows with durable state, retries, and checkpointing. The workflows cover tickets, CMDB data, and changelogs, with exponential backoff and rate-limit handling.

I also engineered recovery-oriented ingestion for Bitbucket Server and Bitbucket Cloud, supporting both cloud-managed workers and workers deployed in customer environments.

## Transformations and delivery metrics

- Built Spark + Iceberg transformation jobs supporting schema evolution and time-travel queries.
- Built and scaled metrics including Lead Time, MTTR, Deployment Frequency, Change Failure Rate, Trellis Score, and Security Insights.
- Tuned SQL queries behind core metrics to reduce computation time and query cost.
- Worked on integrations spanning Snyk, Wiz, Jira, ServiceNow, GitHub, GitLab, and Azure DevOps.

## Production correctness

I diagnosed a correlation defect affecting Azure DevOps work items and designed a correction for **30M+ mismatched records**, with prevention of recurrence across other customer organizations. I also proposed and shipped a scheduler to terminate long-running processes and reduce wasted compute.

## What I care about

Recovery behavior is part of the architecture. A pipeline needs to handle partial failure, resume work, and produce consistent results.

[← Back to profile](../README.md)
