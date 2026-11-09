SCRIPT VAULT BY PRINCE — VERSION 2.0

New in v2.0:
1. AI Script Generator prompt builder: enter topic and preferences, copy the prompt into ChatGPT, then paste the generated script back into the app to save it. This does not call an AI API directly; it opens ChatGPT separately and requires internet.
2. Content Planner: set recording and publishing dates on any script and see scheduled items and status counts.
3. Voice & Delivery Guide: select a saved script for line-by-line delivery cues and save personal delivery notes.

Install / update:
This is a Progressive Web App (PWA). Host all files at the root of a secure HTTPS site (GitHub Pages works). Upload/replace index.html and sw.js to update an existing deployment. Keep manifest.webmanifest and icon.svg in the repository root.

Data and privacy:
Scripts, schedules, and delivery notes are stored in localStorage in this browser on this device. They are not synced to a cloud database. Do not clear site data. Use Settings > Export backup regularly. Import backup can replace current data.

AI note:
The generator builds a detailed prompt for ChatGPT. It does not contain an API key or make direct AI API calls. Copy the prompt, open ChatGPT, paste it, then copy the finished script back into the Save generated script box.
