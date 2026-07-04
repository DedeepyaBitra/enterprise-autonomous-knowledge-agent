# Enterprise Autonomous Knowledge Execution Agent

## Overview

This project is an Enterprise Autonomous Knowledge Execution Agent built using n8n and Google Gemini.

The agent answers employee queries by retrieving information from an internal company knowledge base using Retrieval-Augmented Generation (RAG). Based on the retrieved information, it reasons about the request, provides accurate responses, and performs business actions where applicable.

The project uses only internal company knowledge and connected data sources instead of relying on general AI knowledge.

---

## Features

- Retrieval-Augmented Generation (RAG)
- AI Agent with reasoning capability
- Google Drive knowledge base
- Google Gemini Embeddings
- Simple Vector Store
- Employee database lookup
- Leave balance lookup
- Audit logging
- Multi-source knowledge retrieval
- Graceful handling of missing information

---

## Tech Stack

- n8n
- Google Gemini
- Google Drive
- Google Sheets
- Simple Vector Store
- Markdown Documents

---

## Workflow

### Knowledge Base Ingestion

- Reads Markdown documents from Google Drive
- Downloads documents
- Converts documents into AI-readable format
- Splits documents into smaller chunks
- Generates embeddings
- Stores embeddings in the Simple Vector Store

### Enterprise AI Agent

- Receives user requests
- Searches the internal knowledge base
- Retrieves relevant information
- Reasons over retrieved information
- Uses connected tools when required
- Generates an explainable response
- Records actions in audit logs

---

## Knowledge Sources

- Employee Handbook
- HR Leave Policy
- IT Support Knowledge Base
- Expense & Software Access Policy
- Company FAQ
- Employee Database
- Leave Balance Database

---

## Available Tools

- Enterprise Knowledge Base
- Employee Database
- Leave Balance Database
- Audit Logs

---

## Sample Queries

- How many annual leave days does an employee receive?
- What is the company's work from home policy?
- Apply two days leave.
- My laptop is not turning on.
- Can I claim travel expenses?
- Show remaining leave balance.

---

## Test Cases

### Test 1

**Question**

How many annual leave days does an employee receive?

**Expected Result**

The AI retrieves the HR Leave Policy and answers using the retrieved information.

---

### Test 2

**Question**

Apply two days leave.

**Expected Result**

The AI retrieves the leave policy, checks leave balance, determines whether the request is allowed, and records the action.

---

### Test 3

**Question**

My laptop is not turning on.

**Expected Result**

The AI retrieves the IT Support Knowledge Base and provides the correct troubleshooting procedure.

---

### Test 4

**Question**

Can I claim ₹2500 as travel expense?

**Expected Result**

The AI retrieves the Expense Policy and determines whether the request satisfies company policy.

---

### Test 5

**Question**

Who won the FIFA World Cup 2026?

**Expected Result**

The AI responds that the information is not available in the internal knowledge base instead of generating an incorrect answer.

---

## Repository Structure

```
enterprise-autonomous-knowledge-agent/
│
├── workflow/
│   └── enterprise_autonomous_knowledge_execution_agent.json
│
├── knowledge_base/
│   ├── 01_employee_handbook.md
│   ├── 02_hr_leave_policy.md
│   ├── 03_it_support_kb.md
│   ├── 04_expense_software_access_policy.md
│   └── 05_company_faq.md
│
├── data/
│   ├── employee_database.csv
│   ├── leave_balance.csv
│   └── audit_logs.csv
│
├── screenshots/
│
├── README.md
├── INSTALLATION.md
└── LICENSE
```

---

## Future Improvements

- Human approval for critical actions
- Email notifications
- Slack integration
- Persistent long-term memory
- Additional enterprise knowledge sources

---

## Author

**Dedeepya Bitra**
