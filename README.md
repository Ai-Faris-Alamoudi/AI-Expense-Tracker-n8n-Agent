# AI Expense Tracker using n8n, Ollama, and Google Sheets

This project is an AI automation workflow built with n8n. It allows a user to send a natural language expense message, then an AI Agent extracts the expense details and records them automatically in Google Sheets.



## Features

- Accepts natural language expense messages
- Extracts expense name, amount, date, and category
- Uses an AI Agent inside n8n
- Connects to a local Ollama chat model
- Records structured expense data in Google Sheets
- Uses simple memory to support the AI Agent workflow

## Tools Used

- n8n
- Docker
- Ollama
- Google Sheets
- AI Agent node
- Simple Memory

## Workflow Overview

1. The user sends an expense message through the n8n chat.
2. The AI Agent extracts the required fields.
3. The extracted data is recorded in Google Sheets.
4. The workflow confirms that the expense was recorded successfully.

## Extracted Fields

- Expense Name
- Expense Date
- Amount
- Category / Subscription Type

## Screenshots

### n8n Workflow

![n8n Workflow](n8n-workflow.jpeg)

### Google Sheets Output

![Google Sheets Output](google-sheets-output.jpeg)



## Future Improvements

- Add Telegram input support to record expenses directly through a Telegram bot.
- Improve date handling for inputs such as “today”, “yesterday”, and specific dates.
- Add more expense categories such as food, transportation, subscriptions, shopping, and bills.
- Generate weekly and monthly expense summaries.



## Important Note

This repository does not include private credentials, API keys, Telegram bot tokens, Google credentials, or private sheet links.




