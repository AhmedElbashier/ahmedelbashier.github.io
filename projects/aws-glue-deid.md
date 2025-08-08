# AWS Glue PHI De-identifier

**Year:** 2025  
**Domain:** Healthcare Data Engineering  
**Stack:** AWS Glue, Python, AWS Comprehend Medical, S3, IAM

## Overview
Automated ETL pipeline that detects and removes PHI from clinical notes to produce HIPAA-safe datasets for model training.

## Key Features
- PII/PHI detection with Comprehend Medical
- Token replacement & masking strategies
- Audit logging and metrics
- Configurable output schemas

## Architecture
S3 ingest → Glue ETL → Comprehend Medical → de-identification → curated S3 buckets with lineage.

## Results
Enabled secure model training workflows; reduced manual scrubbing effort; improved compliance posture.

## Links
- Code: #
- Live Demo: #
- Deck/Docs: #
