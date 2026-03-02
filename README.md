# GitHub Webhook Action Repo

## 🔹 Purpose
This repository is used to **trigger webhook events** to a Flask server.  
Whenever a commit is pushed, GitHub sends a **push event** to the configured webhook URL.

## 🔹 How It Works
1. Code changes are committed to this repo.
2. GitHub triggers a **webhook event** for `push`.
3. The event is sent to the Flask Webhook Server.

## 🔹 Webhook Setup
The webhook must point to your Flask server (ngrok or deployed URL):
