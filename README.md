# n8n Internal Operations & Automation Assistant

This repository contains the exported workflow configurations for an automated internal operations assistant built using **n8n**. The system streamlines preliminary accounting, inventory management, and corporate archiving by integrating messaging platforms, cloud storage, and AI-powered data extraction.

## Project Overview
Manual data entry for invoices and inventory tracking is time-consuming and error-prone. This project solves that by creating a fully automated pipeline. Users can interact with the system via a mobile-friendly Telegram interface to upload documents (such as PDF invoices). The n8n workflow then processes these documents using LLM integration to parse key data, automatically updating Google Sheets and archiving the records.

## Key Features
*   **LLM-Powered Invoice Parsing:** Automatically extracts relevant vendor, customer, and pricing data from PDF invoices using Large Language Models.
*   **Automated Accounting & Inventory:** Dynamically updates customer/vendor account balances and tracks inventory movements directly in Google Sheets.
*   **Telegram Bot Interface:** Provides a seamless, mobile-friendly way for team members to submit documents and query data without needing a dedicated app.
*   **Corporate Archiving:** Organizes and safely stores processed documents into Google Workspace (Google Docs/Drive) for auditing and record-keeping.
    
## Measurable Impact
*   **Reduced manual data entry time by 40%.**
*   **Successfully automated the recording and processing of over 100 invoices per week.**

## Technologies & Integrations Used
*   **Automation Platform:** n8n (Node-based workflow automation)
*   **APIs & Services:** Telegram Bot API, Google Sheets API, Google Docs API
*   **Data Processing:** LLM API for PDF parsing

## How to Use
This repository contains the `.json` export of the n8n workflows. You can import these JSON files directly into your own n8n instance to replicate or study the automation nodes and connections.
