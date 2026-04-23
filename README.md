@"
# 🟢 contract-management-streamlit-keep-alive

GitHub Actions workflow to keep the **Contract Management Streamlit app** awake on Streamlit Community Cloud (free tier).

## 🎯 Purpose

Streamlit Community Cloud puts apps to sleep after **12 hours of inactivity**.
This repo pings the app every **6 hours** automatically via GitHub Actions to prevent hibernation.

## 🔗 Target App

| Item | Detail |
|------|--------|
| App URL | https://contract-management-app.streamlit.app/ |
| Source Repo | https://github.com/tanasedw/contract-management-streamlit |
| Platform | Streamlit Community Cloud (Free Tier) |

## ⏰ Schedule

| UTC | Bangkok (UTC+7) |
|-----|----------------|
| 00:00 | 07:00 |
| 06:00 | 13:00 |
| 12:00 | 19:00 |
| 18:00 | 01:00 |

## 🚀 Manual Trigger

Go to **Actions** tab → Select **Keep Streamlit App Alive** → Click **Run workflow**

## 📁 Structure

```.
└── .github/
    └── workflows/
        └── keep_alive.yml   # Scheduled ping workflow
```
"@ | Set-Content README.md -Encoding UTF8