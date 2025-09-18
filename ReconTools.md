# 🛰️ Reconnaissance Phase Cheat Sheet

## 📌 Overview
- **Goal:** Gather information about the target before attacking.
- **Purpose:** Understand the environment, map the network, and identify possible entry points.
- **Position in hacking phases:** Comes first — before scanning, exploitation, maintaining access, and covering tracks.

---

## 🕵️ Types of Reconnaissance

### 🧩 Passive Recon
- **Definition:** Collecting information without directly touching the target.
- **Why it's stealthy:** No interaction with the target, so it's harder to detect.
- **Common Activities:**
  - Searching company websites, news, and social media
  - Collecting emails, usernames, and leaked data from public sources
  - Looking up domain registration and DNS info
  - Gathering information from search engines and public documents

### ⚡ Active Recon
- **Definition:** Collecting information by directly interacting with the target.
- **Why it's noisy:** Creates logs and can trigger security alerts.
- **Common Activities:**
  - Scanning for live hosts, open ports, and running services
  - Enumerating web directories and user accounts
  - Probing network shares or exposed resources

---

## 🧰 Tools by Category

### 📂 Open Source Intelligence (OSINT)
- **Maltego** — Maps relationships between people, companies, domains, emails.
- **theHarvester** — Finds emails, subdomains, and usernames from public sources.
- **Recon-ng** — Modular OSINT framework to automate information gathering.
- **SpiderFoot** — Collects data about targets from many public sources.

---

### 🌐 Network Scanning
- **Nmap** — Scans for live hosts, open ports, and services.
- **Masscan** — Very fast port scanner (internet-wide capable).
- **Angry IP Scanner** — Simple GUI tool for quickly finding active hosts.

---

### 🧭 DNS & WHOIS Enumeration
- **whois** — Shows domain ownership and registration info.
- **nslookup** — Resolves domains to IPs and shows DNS records.
- **dig** — Advanced DNS lookups and zone information.
- **dnsenum** — Automates DNS enumeration to find subdomains and hosts.

---

### 💻 Website & Web App Recon
- **Burp Suite** — Intercepts and analyzes web traffic; maps web apps.
- **WhatWeb** — Detects technologies used by a website.
- **Wappalyzer** — Identifies frameworks, libraries, and CMSs via browser.
- **Nikto** — Scans web servers for vulnerabilities and misconfigurations.

---

### 👤 Social Media & People Recon
- **Sherlock** — Finds usernames across hundreds of social media platforms.
- **Social-Searcher** — Searches social media for posts, mentions, and profiles.
- **LinkedIn OSINT searches** — Manual searches to find employees, emails, and org structure.

---

## ✅ Best Practices for Recon
- Get **written permission** and respect the defined **scope**.
- Start **passive** before going **active**.
- **Document everything** — screenshots, notes, export results.
- Stay **organized** — group findings (domains, IPs, emails, tech stacks).
- Always **stay ethical and legal**.

