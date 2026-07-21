# Instagram Growth Strategist  Job Intake

This n8n workflow is the starting point of an AI powered Instagram Growth Strategist.

It takes an Instagram username from Google Sheets, creates an analysis job, collects recent Instagram posts, sends the data to Google Gemini, and saves the results back to the sheet.

## How It Works

```text
Google Sheets
      ↓
New Instagram Username
      ↓
Create Analysis Job
      ↓
Collect Recent Posts
      ↓
Google Gemini Analysis
      ↓
Growth Insights
      ↓
Update Google Sheets
```

The workflow looks at things like:

* Best-performing posts
* Likes and comments
* Video views
* Content topics and niches
* Content strategy
* New content ideas
* Posting plan

## Built With

* **n8n**  Workflow automation
* **Google Sheets**  Job tracking and results
* **Apify**  Instagram data collection
* **Google Gemini**  AI-powered analysis

## Setup

1. Import the workflow into n8n.
2. Connect your Google Sheets account.
3. Add your own Apify API credentials.
4. Connect your Google Gemini credentials.
5. Add an Instagram username to the input Google Sheet.

The workflow will then process the account and save the analysis results back to the sheet.

> **Note:** API keys and credentials are not included in this repository. You need to add your own credentials after importing the workflow.

This workflow is part of a larger **Instagram Growth Strategist** project focused on turning Instagram data into practical growth strategies and content recommendations.
