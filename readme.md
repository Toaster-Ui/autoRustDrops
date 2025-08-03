# 🟣 Twitch Rust Drops Watcher

Automatically track and manage Twitch streamers eligible for Rust drops — opens eligible live streams in your browser, estimates remaining drop watch time, and rotates through streamers until all drops are complete.

---

## 🎯 Features

- 🔍 Scrapes [twitch.facepunch.com](https://twitch.facepunch.com) to find current Rust drop streamers
- 🟢 Detects which streamers are live, offline, or already completed
- ⏱️ Pulls drop progress from your [Twitch inventory](https://www.twitch.tv/drops/inventory)
- 🧮 Estimates remaining time based on percent complete (e.g., 45% = ~66 mins left)
- 🎥 Automatically opens streamers with uncompleted drops in your default browser
- 🔁 Automatically rotates to the next eligible streamer after a drop completes
- 💤 Waits 30 minutes and retries if no eligible streamer is online
- 💬 Simple command interface: `open` or `exit`

---

## 🚀 How to Use

### 📦 Option 1: Download and Run the .exe

#### 🔹 1. Download and Run the .exe and enjoy the drops

### 📦 Option 2: Run with Python

#### 🔹 1. Install Python 3.x  
Download from: https://www.python.org/downloads/

#### 🔹 2. Install required libraries
```bash
pip install requests beautifulsoup4
```
---

⚠️ DISCLAIMER

This project is a personal automation tool designed to help users manage Twitch Drops progress more easily.

- This project is not affiliated with Twitch or Facepunch Studios in any way.

- It does not simulate viewership, interact with the Twitch player, or manipulate drop systems.

- It simply automates the process of opening eligible Twitch streams based on public HTML content and estimated watch time.

- Use of this tool is at your own risk. Be sure to comply with Twitch’s Terms of Service and Drops Program Guidelines.





