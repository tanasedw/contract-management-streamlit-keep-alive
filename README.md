# contract-management-streamlit-keep-alive

GitHub Actions workflow to keep the Contract Management Streamlit app awake.

## Purpose

Streamlit Community Cloud (free tier) puts apps to sleep after **12 hours of inactivity**.
This repo pings the app every **6 hours** via GitHub Actions to prevent hibernation.

## Target App

https://contract-management-app.streamlit.app/

## Schedule

Runs at **00:00, 06:00, 12:00, 18:00 UTC** (07:00, 13:00, 19:00, 01:00 Bangkok time)

## Manual Trigger

Go to **Actions** tab → Select workflow → Click **Run workflow**