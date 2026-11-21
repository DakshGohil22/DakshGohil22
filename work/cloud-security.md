# Cloud integrations and security

## GCS connector

At Crest Data, I built a connector that collects users, roles, permissions, activity logs, and objects from customer Google Cloud Storage accounts and publishes the data to Kafka.

It includes OAuth 2.0 onboarding, pagination, retries, and incremental fetching. I tested it with JUnit and Python tests, as well as live GCS integration tests.

## Cloud security controls

I built harvesting and detection logic for more than 200 controls in a CSPM platform covering AWS, GCP, Azure, and StackIt. The work involves turning security conditions defined by researchers into resource collectors and SQL queries.

I also built and maintain a cloud-provider collector layer. It calls provider APIs, handles pagination and rate limits, and maps different response formats into the shared database schema used by the platform.

**Stack:** Java, Kafka, PostgreSQL, Hibernate/JPA, OAuth 2.0, REST APIs.

[Back to profile](../README.md)
