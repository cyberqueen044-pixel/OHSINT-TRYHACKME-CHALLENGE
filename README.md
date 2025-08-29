# OHSINT-TRYHACKME-CHALLENGE
Walkthrough on OSINT Tryhackme

# TryHackMe OhSINT Walkthrough

This is a detailed walkthrough of the [OhSINT room on TryHackMe](https://tryhackme.com/room/ohsint), an OSINT (Open Source Intelligence) challenge designed to test your investigation skills using publicly available information.

---

## 🛠️ Tools & Skills Used
- **Reverse Image Search** (Google Images, TinEye, Yandex)
- **Social Media Reconnaissance**
- **WHOIS Lookups**
- **WiGLE** (Wireless network mapping)
- **Basic OSINT Mindset**: Connecting breadcrumbs to identify a target

---

## 🧩 Challenge Overview
You’re given a single image as a clue and need to extract as much intelligence as possible. This tests your ability to follow leads, pivot between sources, and verify open data.

---

## 🔍 Step-by-Step Process

### 1. Start with the Image
We were given an image (see below):

![Given Image](image.jpg)

First, I downloaded the image and checked its **metadata (EXIF data)**.

```bash
exiftool image.jpg
