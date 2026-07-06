# Daily Sales Automation (n8n)

An automated pipeline that generates and sends a daily sales report — fully hands-off, no manual reporting needed.

## How it works
1. **Schedule Trigger** — runs automatically every day at 8 AM
2. **MySQL Query** — pulls yesterday's sales data (product, quantity, revenue)
3. **Code Node** — calculates total revenue, total quantity, and top-selling product
4. **Conditional Check** — if revenue falls below ₹5,00,000, triggers a low-sales alert email
5. **Google Gemini AI** — generates a professional written summary of the day's performance
6. **Google Sheets** — logs the day's data for historical tracking
7. **Gmail** — sends the AI-generated report to stakeholders

## Tech Stack
n8n · MySQL · Google Gemini API · Google Sheets API · Gmail API

## Why I built this
To eliminate manual daily sales reporting — replacing a repetitive task with a fully automated pipeline that alerts on underperformance and keeps a running data log automatically.
