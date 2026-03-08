# SAR Guardian – SAR Narrative Generator with Audit Trail

SAR Guardian is an AI-assisted compliance platform that helps generate Suspicious Activity Report (SAR) narratives with full evidence traceability and a tamper-evident audit trail.

## Overview

This project provides a full-stack solution for AML (Anti-Money Laundering) compliance. It generates SAR narratives from structured financial case data while ensuring every statement is supported by verifiable evidence.

Aligned with regulatory guidance from:
- FinCEN
- FIU-IND
- FATF

## Tech Stack

| Layer | Technology |
|------|-------------|
| UI | Streamlit |
| Backend | FastAPI, SQLAlchemy |
| Database | PostgreSQL (Supabase) |
| Authentication | JWT + bcrypt |
| LLM | Groq / OpenAI |
| Frontend | Next.js, TypeScript, TailwindCSS |

## Key Features

- AI-generated SAR narratives
- Sentence-level evidence mapping
- Immutable audit trail with SHA-256 hashing
- Role-based access control
- Override governance workflow
- Alert monitoring system

## Running the Project

### Install dependencies
```bash
pip install -r requirements.txt
