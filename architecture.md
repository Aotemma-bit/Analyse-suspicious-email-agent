# System Architecture

## Workflow Overview

```
Gmail Trigger
      │
      ▼
Extract Email Variables
      │
      ▼
Convert Email Body to Text
      │
      ▼
AI Email Analysis
      │
      ▼
Check if Malicious
     / \
    /   \
   ▼     ▼
Potentially  Potentially
Malicious    Benign
   │           │
   ▼           ▼
Create      Create
Ticket      Ticket
      \     /
       ▼   ▼
Generate Summary
       │
       ▼
Upload to Google Sheets
```

## Components

- Gmail Trigger
- Email Variable Extraction
- Email Body Processing
- AI Email Analysis
- Threat Classification
- Ticket Creation
- Email Summarisation
- Google Sheets Logging
