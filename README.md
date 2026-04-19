# 📥 All-in-One Social Media Video Downloader

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Flask-lightgrey?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

A web-based utility tool built with **Flask** that allows users to download videos from multiple platforms including **YouTube, Twitter (X), Instagram, and Facebook** by simply providing the video URL.

---

## 🚀 Live Demo
You can try the live application here:  
**[Video Downloader Live](https://video-downloader-from-internet-1.onrender.com/)**

> **⚠️ Troubleshooting:** If the video fails to download or the link generation fails, it is possible that the **API keys have expired** or reached their rate limit. For YouTube, ensure `yt-dlp` is updated.

---

## ✨ Features
* **📺 YouTube & Playlist Support:** Download individual videos or entire playlists using `yt-dlp`.
* **📱 Multi-Platform:** Dedicated modules for Instagram, Facebook, and Twitter (X).
* **⚡ Direct Extraction:** Automatically fetches high-quality video stream URLs.
* **💻 Minimalist UI:** Simple, user-friendly web interface for quick downloads.

---

## 📂 Project Structure & Workflow

* **[main.py](https://github.com/amarnathmahat0/Video-downloader-from-internet/blob/main/main.py):** The primary entry point. It manages routing and serves the web interface.
* **[social_downloader_insta_fb.py](https://github.com/amarnathmahat0/Video-downloader-from-internet/blob/main/social_downloader_insta_fb.py):** Handles scraping for Instagram and Facebook.
* **[twitter_downloader.py](https://github.com/amarnathmahat0/Video-downloader-from-internet/blob/main/twitter_downloader.py):** Dedicated module to fetch Twitter (X) video links.
* **[templates/](https://github.com/amarnathmahat0/Video-downloader-from-internet/tree/main/templates):** Contains HTML frontend templates.

---

## ⚙️ Setup & Installation

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/amarnathmahat0/Video-downloader-from-internet.git](https://github.com/amarnathmahat0/Video-downloader-from-internet.git)
   cd Video-downloader-from-internet
Install Required Libraries:

Bash
pip install -r requirements.txt
pip install yt-dlp
Run the Application Locally:

Bash
python main.py
Navigate to http://127.0.0.1:5000 in your web browser.

🤝 Contributing
Contributions are welcome! If you want to add support for more platforms, feel free to fork the repo and submit a Pull Request.

Developed by Amarnath Mahato
