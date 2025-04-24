# 🔍 Facebook Group Keyword Monitor

A keyword-monitoring tool for Facebook groups you’re a member of, built using Puppeteer and Docker. Designed to alert you when posts contain target keywords like “photographer” or “brand shoot.”

## 🚀 Features
- Keyword scanning of Facebook group posts
- Cookie-based session authentication
- Desktop notifications for keyword hits
- Google Sheets logging
- Runs in Docker container or scheduled via cron

## 🧰 Stack
- Node.js
- Puppeteer
- Docker
- Google Sheets API

## 📦 Setup
1. Clone this repo
2. Fill out `.env` using `.env.example`
3. Build Docker container:
   docker build -t fb-keyword-monitor .
4. Run:
   docker run --env-file .env fb-keyword-monitor

