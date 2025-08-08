# Knowledge Ingestion & Approval System

**Year:** 2025  
**Domain:** Enterprise AI Governance  
**Stack:** Next.js (Vercel), FastAPI, PostgreSQL, Azure Blob

## Overview
Workflow for ingesting healthcare docs, routing for admin review, and approving content before LLM use.

## Key Features
- Role-based access control
- Document parsing and versioning
- Approval queues and audit trails
- API for downstream model access

## Architecture
Next.js admin UI → FastAPI services → DB for metadata; storage in Azure Blob; webhooks for model updates.

## Results
Controlled, auditable AI knowledge base; reduced risk of unvetted content entering models.

## Links
- Code: #
- Live Demo: #
- Deck/Docs: #
