# 📥 All-in-One Social Media Video Downloader

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Flask-lightgrey?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

A web-based utility tool built with **Flask** that allows users to download videos from multiple platforms including **Twitter (X), Instagram, and Facebook** by simply providing the video URL.

---

## 🚀 Live Demo
You can try the live application here:  
**[Video Downloader Live](https://video-downloader-from-internet-1.onrender.com/)**

> **Note:** If the video fails to download or the link generation fails, it is possible that the **API keys have expired** or reached their rate limit.

---

## ✨ Features
* **Multi-Platform Support:** Dedicated modules for extracting videos from Instagram, Facebook, and Twitter.
* **Minimalist UI:** Simple, user-friendly web interface for quick downloads.
* **Direct Extraction:** Automatically fetches high-quality video stream URLs.
* **Modular Architecture:** Clean code structure with separate handlers for different platforms.

---

## 📂 Project Structure & Workflow

* **[main.py](https://github.com/amarnathmahat0/Video-downloader-from-internet/blob/main/main.py):** The primary entry point. It manages routing and serves the web interface.
* **[social_downloader_insta_fb.py](https://github.com/amarnathmahat0/Video-downloader-from-internet/blob/main/social_downloader_insta_fb.py):** Handles the scraping and link extraction for Instagram and Facebook.
* **[twitter_downloader.py](https://github.com/amarnathmahat0/Video-downloader-from-internet/blob/main/twitter_downloader.py):** Specifically designed to process and fetch Twitter (X) video links.
* **[templates/](https://github.com/amarnathmahat0/Video-downloader-from-internet/tree/main/templates):** Contains the HTML templates for the frontend.

---

## ⚙️ Setup & Installation

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/amarnathmahat0/Video-downloader-from-internet.git](https://github.com/amarnathmahat0/Video-downloader-from-internet.git)
   cd Video-downloader-from-internet
Install Required Libraries:Bashpip install -r requirements.txt
Run the Application Locally:Bashpython main.py
Navigate to http://127.0.0.1:5000 in your web browser.🤝 ContributingContributions are welcome! If you want to add support for YouTube, TikTok, or other platforms, feel free to fork the repo and submit a Pull Request.Developed by Amarnath Mahato
