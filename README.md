# 🕵️‍♂️ Fake Account Detection in Social Media

A Python-based system deployed on Raspberry Pi to detect and flag potentially fake social media accounts using behavioral and metadata analysis. This lightweight, edge-ready solution is designed for researchers, developers, and digital safety advocates aiming to combat online impersonation and bot activity.

---

## 🔍 Project Overview

This project leverages Python scripts and machine learning techniques to analyze user data—such as posting frequency, profile completeness, follower ratios, and engagement metrics—to identify suspicious patterns commonly associated with fake accounts.

The system runs on a Raspberry Pi, making it portable, energy-efficient, and ideal for edge deployment or educational demonstrations.

---

## 🧠 Core Features

- 📊 **Behavioral Analysis**: Tracks posting intervals, content diversity, and interaction patterns.
- 🧾 **Metadata Scraping**: Extracts profile details using APIs or web scraping (e.g., username, bio, follower/following count).
- 🧠 **ML-Based Classification**: Uses trained models to classify accounts as genuine or fake.
- 🛠️ **Raspberry Pi Integration**: Optimized for low-resource environments with GPIO-based alerting (e.g., LED or buzzer on detection).
- 📤 **Report Generation**: Outputs detection logs and summaries for review.

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**: scikit-learn, pandas, requests, BeautifulSoup, matplotlib
- **Hardware**: Raspberry Pi 4 (or compatible)
- **Optional APIs**: Twitter API, Instagram Graph API (for real-time data)

---
