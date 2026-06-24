# ai-sales-pipeline-automation
![Workflow](./Screenshot%20worflow.png)
Automated B2B lead scoring pipeline — n8n + OpenAI GPT-4o-mini + HubSpot CRM | 250 leads processed automatically
# 🤖 AI Sales Pipeline Automation

> Automated B2B lead scoring and CRM enrichment pipeline — built as a portfolio project to demonstrate AI automation, business process optimization, and CRM integration.

---

## 📊 Project Overview

This project simulates a real-world B2B sales operations challenge: **how to qualify 250 inbound leads without manual effort**.

The pipeline automatically:
- Reads raw lead data from Google Sheets
- Scores each lead using GPT-4o-mini based on 8 business signals
- Categorizes leads as **Hot / Warm / Cold**
- Pushes enriched contact data directly into HubSpot CRM

**Result: 250 leads processed autonomously — 0 manual intervention required.**

---

## ⚙️ Tech Stack

| Tool | Role |
|------|------|
| **n8n** | Workflow automation orchestrator |
| **OpenAI GPT-4o-mini** | AI lead scoring engine |
| **Google Sheets** | Lead data source (250 B2B leads) |
| **HubSpot CRM** | Contact enrichment destination |
| **JavaScript** | JSON parsing & data transformation |

---

## 🔄 Workflow Architecture
