# Sustainable-Research-Journal-Bot

This project uses [n8n](https://n8n.io) to automatically fetch the latest research papers on AI and sustainability from [arXiv](https://arxiv.org/), format them, and email a weekly digest.  

---

## Features
- Weekly scheduled workflow (Cron)
- Fetches papers from arXiv API
- Parses XML into JSON
- Formats results into a digest
- Sends email via Gmail SMTP

---

## Usage Instructions
1. Run n8n (Docker or local install)
2. Import the workflow file from `workflows/arxiv_fetch_and_summarize.json`
3. Add Gmail SMTP credentials in n8n
4. Execute workflow manually or let the Cron node automatically run weekly

---

## Example Output
📌 Climate And Resource Awareness is Imperative to Achieving Sustainable AI  
🔗 http://arxiv.org/abs/2502.20016v1  
📝 Sustainability encompasses three key facets: economic, environmental, and social...  

---

## Project Structure
sustainable-research-bot/  
├── workflows/  
│ └── arxiv_fetch_and_summarize.json  
└── README.md  
