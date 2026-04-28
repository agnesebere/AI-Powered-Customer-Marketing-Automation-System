# AI-Powered Customer Marketing Automation System

This project implements an AI-driven marketing automation workflow using **n8n and Mistral AI**.

## Features
- Customer segmentation (High, Medium, Low value)
- Churn risk analysis
- AI-driven marketing strategy generation
- Personalized email campaign creation
- Priority-based campaign execution
- Decision logging and historical context

## Tech Stack
- n8n (workflow automation)
- Mistral AI (LLM)
- Google Sheets API
- Gmail API
- JavaScript

## Workflow Overview
1. Load customer data and decision history
2. Merge and enrich data with context
3. AI generates segmentation and strategy
4. Priority scoring determines campaign execution
5. Emails sent to high-priority customers
6. Insights and decisions logged

## Files
- `workflow.json` → n8n workflow
- `report.pdf` → project report

## How to Run
1. Import the JSON file into n8n
2. Configure credentials (Google Sheets, Gmail, Mistral)
3. Run the workflow

## 💡 Project Goal
To automate customer targeting, improve retention, and optimize marketing resources using AI.
