# AI Email Threat Analysis Workflow

## Overview

This project is an AI-powered n8n workflow that automatically analyses incoming Gmail messages, determines whether they are potentially malicious or benign, generates summaries, and stores the processed information for further investigation.

## Workflow

![Workflow](images/workflow.png)

## Features

- Gmail Trigger
- Email preprocessing
- AI-powered email analysis
- Suspicious email detection
- Automatic classification
- Ticket creation
- Email summarisation
- Spreadsheet logging

## Technologies

- n8n
- Gmail API
- OpenAI
- Google Sheets

## Workflow Process

1. Gmail receives a new email.
2. Email variables are extracted.
3. Email body is converted into plain text.
4. AI analyses the message.
5. The workflow checks whether the email appears malicious.
6. A ticket is created based on the result.
7. A summary is generated.
8. Results are uploaded into a spreadsheet.

## Status

Portfolio Project
