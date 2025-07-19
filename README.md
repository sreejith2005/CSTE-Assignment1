# n8n Automation Workflows Submission

This repository contains two n8n workflows for the internship assignment:
1. **Reddit & Twitter Research Bot**: Searches Reddit and Twitter for topics and logs results to Google Sheets.
2. **YouTube Video Finder with Analysis**: Searches YouTube for videos (4-20 minutes, last 14 days), analyzes with AI, and logs to Google Sheets.

## How the Workflows Work
- **Input**: Text query via n8n manual trigger.
- **Processing**: API calls to Reddit/Twitter/YouTube, filtering, AI analysis (Gemini).
- **Output**: Logs all results (including errors) to Google Sheets.

<img width="1823" height="776" alt="image" src="https://github.com/user-attachments/assets/ae6f6e28-f0c2-4ca9-84a9-95fa00f6c210" />

## Setup Instructions
1. Import JSON files into n8n (Workflow > Import from File).
2. Configure API keys in n8n credentials:
   - YouTube API Key
   - Twitter Bearer Token
   - Gemini API Key
   - Google Sheets credentials
3. Replace placeholders (e.g., YOUR_API_KEY) in JSON.
4. Execute and test.
