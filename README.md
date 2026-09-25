**AI Lead Intelligence & Sales Automation**
An AI-powered lead qualification and sales automation workflow built with n8n, Google Gemini, Tally Forms, Email Automation, and Google Sheets.

**Project Overview**
This project automates the process of receiving business leads, analyzing them with AI, qualifying them based on lead score, sending appropriate follow-up emails, and saving the results in Google Sheets.

**Workflow**
Tally Form → Webhook → Lead Data Preparation → AI Lead Analyzer → Lead Qualification → Email Automation → Google Sheets

**Lead Qualification Logic**
HOT: Lead score ≥ 80
WARM: Lead score ≥ 50
LOW: Lead score < 50

**AI Analysis**
The AI Lead Analyzer evaluates each lead and generates:
Lead Qualification
Lead Score (0–100)
Customer Intent
Business Need
Recommended Action
Reason
The AI analysis is based only on the information submitted through the lead form and is designed to avoid unsupported assumptions.

**Automation**
After AI analysis:
HOT leads receive an immediate follow-up alert.
WARM leads receive a business inquiry follow-up email.
LOW leads receive a general business follow-up email.
All processed leads are saved to Google Sheets.
Tools & Technologies
n8n
Google Gemini
Tally Forms
Webhooks
Email Automation
Google Sheets
JSON
AI Agents

**Workflow File**
The n8n-workflow.json file contains a clean, reusable version of the workflow.
Credentials, API keys, personal email addresses, and private configuration details have been removed from the public workflow file.
To use the workflow, connect your own:
Google Gemini credentials
Email/SMTP credentials
Google Sheets account
Google Sheet

**Project Purpose**
This project demonstrates practical skills in:
AI automation
Lead qualification
Workflow automation
Webhook integration
AI-powered decision logic
Email automation
Google Sheets integration
No-code/low-code automation with n8n

**Author**
Izah Sharif
BS Information Technology
Izah Sharif

