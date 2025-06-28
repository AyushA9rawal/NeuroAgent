# 🧠 NeuroAgent – AI Health Productivity Agent

Align your energy with your goals using **AI-powered daily task prioritization** based on your **steps, sleep, and calendar context**.

---

## 🚀 What is NeuroAgent?

NeuroAgent is a lightweight AI agent that:
✅ Connects **Google Fit** (steps, sleep).  
✅ Fetches **Google Calendar tasks**.  
✅ Uses **Gemini AI** to suggest the *single best task* for your day based on your **energy readiness**.  
✅ Automatically delivers the suggestion to you via **Telegram**.

Built to help people align **wellness and productivity** using automation and AI in a practical, minimal way.

---

## ✨ Features

- 📊 **Energy-Aware Task Selection** using steps and sleep data.
- 🗓️ Pulls your upcoming tasks from Google Calendar.
- 🤖 Uses Gemini’s reasoning to analyze your readiness and priorities.
- 📲 Sends actionable recommendations to Telegram daily.
- 🔄 Runs automatically with **n8n** workflows.

---

## 🛠️ Tech Stack

- [n8n](https://n8n.io) (automation workflow engine)
- Google Fit API (steps, sleep)
- Google Calendar API
- Gemini Pro API (OpenAI/Google AI)
- Telegram Bot API

---

## 🎥 Demo

[👉 Watch the Loom demo here](YOUR_LOOM_LINK_HERE)

![Telegram Suggestion Screenshot](screenshots/telegram_suggestion.png)

---

## ⚙️ How It Works

1. **Trigger (Scheduled daily)** on n8n.
2. Fetch **steps and sleep data** from Google Fit.
3. Fetch **calendar events** for the day.
4. Generate a **prompt** for Gemini with your current energy data + tasks.
5. Gemini returns your **single best task** for the day.
6. NeuroAgent **sends it via Telegram** to you automatically.

---

## 🪄 Why I Built This

I’m fascinated by the intersection of **health, wellness, and productivity**.

NeuroAgent is my experiment in helping people live **more intentional, energy-aligned days using AI**.

---

## 🧩 Future Enhancements

- Integrate **heart rate and HRV data** for deeper readiness estimation.
- Contextual break suggestions based on energy dips.
- ML-based personalization for smarter recommendations over time.
- Slack/Discord integrations alongside Telegram.

---

