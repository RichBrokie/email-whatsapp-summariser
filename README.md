# AI-Powered Email Summarization & WhatsApp Notification System

## 📬 Overview

This project automates the process of fetching unread emails from a personal Outlook account, summarizing them using Google's Gemini AI, and delivering the summaries via WhatsApp using Twilio's Sandbox API. It is designed to run daily on a headless DietPi server using a cron job.

## 🚀 Features

- 🔐 Secure authentication using MSAL device flow
- 📧 Fetches unread emails from Microsoft Outlook via Graph API
- 🧠 Summarizes email content using Gemini
- 🧹 Filters out irrelevant senders (e.g., LinkedIn, Bloomberg)
- 📲 Sends daily summaries to WhatsApp using Twilio Sandbox

## 🛠️ Tech Stack

- Python 3
- MSAL (Microsoft Authentication Library)
- Microsoft Graph API
- Google Generative AI (Gemini)
- Twilio WhatsApp Sandbox API
- Cron (Linux automation)
- DietPi (Debian-based OS)
