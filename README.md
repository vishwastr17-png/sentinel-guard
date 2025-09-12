# 🛡️ Sentinel Guard

A unified digital threat protection system that detects toxicity, phishing, and misinformation in real-time via Telegram, with automated logging and alerting.

## 🌟 Features

- **Toxicity Detection:** Uses Hugging Face's `toxic-bert` AI model to identify harmful language.
- **Phishing Detection:** Custom rule-based engine to flag scam indicators ("urgent", "click here").
- **Fake News Detection:** Algorithmic analysis for misinformation patterns.
- **Threat Intelligence:** Simulates IP address detection and logging.
- **Automated Response:** Automatically logs threats to Google Sheets and sends alerts via ntfy.sh
