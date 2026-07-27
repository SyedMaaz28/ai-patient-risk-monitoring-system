# 🏥 AI Patient Risk Monitoring System

An AI-powered hospital triage workflow built with n8n and Groq Llama 3.1.

## Features

- Webhook-based patient intake
- Patient validation
- Clinical context enrichment
- AI-powered risk assessment
- LOW / MEDIUM / HIGH / CRITICAL routing
- Gmail notifications
- Google Sheets audit logging
- Global error handling
- Confidence-based routing

## Tech Stack

- n8n
- Groq
- Llama 3.1
- JavaScript
- Gmail API
- Google Sheets API

## Workflow

![Workflow](screenshots/workflow-overview.png)

## Architecture

Patient
↓

Webhook

↓

Validation

↓

Clinical Enrichment

↓

LLM Risk Assessment

↓

Risk Routing

↓

Notifications

↓

Audit Logging

## Sample Inputs

Located in

sample-data/

## Future Improvements

- FastAPI backend
- PostgreSQL
- Authentication
- Docker
- Redis
- Vector Database
