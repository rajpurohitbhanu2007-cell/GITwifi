# GITwifi Suite

A high-performance Windows desktop utility and captive portal network manager designed for campus networks.

## Features
- **Auto-Login & Keepalive**: Keeps your internet session active with adaptive pinging.
- **Multi-Profile Management**: Securely switch between multiple accounts.
- **Quota & Bandwidth Tracking**: Monitor daily usage and auto-rotate profiles.
- **Stealth Spoofing**: Customizable User-Agent (iOS / desktop modes).
- **Background Tray Service**: Minimal CPU and memory footprint with tray notifications.

## Getting Started

1. **Install Dependencies:**
   ```cmd
   pip install -r requirements.txt
   ```
2. **Configuration:**
   Copy `config.example.json` to `config.json` and configure your credentials.
3. **Run Application:**
   ```cmd
   python git_wifi_suite.py
   ```
   Or launch via `Launch_GITwifi.bat`.
