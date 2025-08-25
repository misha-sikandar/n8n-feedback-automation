# N8N Feedback Automation

This project automates the process of handling feedback forms using **N8N**:

- Complaints → Saved in Airtable (Complaints Table) + Slack notification  
- Compliments → Saved in Airtable (Compliments Table) + Slack notification  
- Feature Requests → Saved in Airtable (Feature Requests Table) + Slack notification  

## Tools Used
- [N8N](https://n8n.io/) – workflow automation
- Airtable – database for feedback storage
- Slack – team notifications

## How to Use
1. Import the `feedback-form.json` workflow into your N8N instance.
2. Add your Airtable and Slack credentials.
3. Run the workflow and start receiving automated feedback routing!

Note: This workflow JSON does not include API credentials.  
Please add your own Airtable and Slack credentials after importing.


---
