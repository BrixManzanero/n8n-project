# 🤖 AI-Powered Customer Support Automation Pipeline

An end-to-end automated email response system built with n8n, utilizing Google Gemini for intelligent sentiment analysis and dynamic response generation. 

## 🚀 Key Features
* **Automated Ingestion:** Listens to incoming Gmail messages and triggers the workflow automatically.
* **Context-Aware AI:** Uses Google Gemini LLM with conversational memory to understand context, summarize issues, and draft personalized replies.
* **Sentiment Analysis:** Automatically categorizes customer emails (e.g., Frustrated, Happy, Neutral) for better prioritization.
* **Data Logging:** Dynamically parses JSON output from the AI and logs the sentiment, summary, and reply directly into a Google Sheets tracking database.

## 🛠️ Tech Stack
* **Workflow Automation:** n8n
* **Large Language Model (LLM):** Google Gemini (with simple memory components)
* **APIs / Integrations:** Gmail API, Google Sheets API (OAuth2)
* **Data Handling:** JSON Parsing & Expression Mapping

## 📁 Project Structure
* `/workflows` - Contains the exported JSON blueprint of the n8n automation pipeline.