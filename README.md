# n8n EU Institutional Data Extraction Workflow

Production-grade n8n workflow for automated staff data extraction from EU institutional websites.

## What it does
- Fetches paginated staff records from public EU institutional APIs
- Extracts structured data: names, roles, departments, contact info
- Deduplicates records across runs
- Syncs results to Google Sheets
- Handles concurrency, timeouts, and retry logic

## Stack
- n8n (JavaScript custom nodes)
- Google Sheets API
- REST API integration

## Notes
Credentials replaced with placeholders. Built for production use.
