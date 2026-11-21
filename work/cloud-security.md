# Cloud integrations and security

**Professional work at Crest Data · Java · Kafka · PostgreSQL · OAuth 2.0 · Cloud APIs**

## Google Cloud Storage connector

I built a connector that extracts users, roles, permissions, activity logs, and objects from customer GCS accounts into Kafka, with self-service OAuth 2.0 onboarding.

The ingestion handles pagination, retries, and incremental fetching. I validated the connector with JUnit and Python tests, alongside live GCS integration testing.

## Multi-cloud security controls

I built harvesting and detection logic for **200+ controls** in a Cloud Security Posture Management platform spanning AWS, GCP, Azure, and StackIt.

This involved translating researcher-defined conditions into resource harvesting and SQL detection queries, including storage access and permissions checks.

I also built and maintain a cloud-provider collector layer that:

- Calls provider APIs across resource types.
- Normalizes different response shapes into a shared schema.
- Handles pagination and rate-limited retries.
- Supports a common entity-ID and provider contract for detection queries and UI rendering.

## What I care about

Different cloud providers model resources differently. A useful normalization layer preserves the security meaning of the original data while giving downstream queries a consistent contract.

[← Back to profile](../README.md)
