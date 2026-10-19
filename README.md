# 🌱 Plant-Forward Southeast Asia (Green Plate SEA)
### 东南亚绿食倡议 · 官方数字枢纽与志愿者协作平台

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Status: In-Development](https://img.shields.io/badge/Status-Under%20Development-blue.svg)]()
[![Non-Commercial](https://img.shields.io/badge/Project-Non--Commercial-brightgreen.svg)]()

> A grassroots digital hub dedicated to practical sustainability, reducing waste, and promoting evidence-based plant-forward living across Southeast Asia.  
> 立足东南亚的公益倡导平台：减少生态浪费，重塑生命价值，推广科学搭配的植物性饮食方案。

---

## 📌 About Us (关于我们)

**Plant-Forward Southeast Asia** is a community-driven nonprofit advocacy initiative. Our core mission is:
- **Avoid Unnecessary Waste:** Lower ecological footprint through mindful consumption.
- **Honor Life & Dignity:** Encourage empathy and care for living beings.
- **Evidence-Based Nutrition:** Advocate for gradual meat reduction based on balanced nutritional science, and support adopting full plant-based living when feasible.

Currently, our team operates primarily offline across communities in Southeast Asia through:
- 📢 Public workshops and educational meetups
- 📄 Community flyers and bilingual plant-based guide distribution
- 🤝 Regional volunteer network and local community mutual aid

---

## 🚀 Purpose of This Repository (项目规划)

This repository contains the source code for our official non-commercial web platform, designed to extend our physical grassroots actions into a scalable digital hub.

The planned platform includes:
1. **Nutrition & Meal Guides**: Scientifically validated, culturally adapted plant-based recipes tailored for Southeast Asian diets.
2. **Volunteer & Event Management**: A unified system for local volunteers to coordinate workshops, flyer distribution runs, and meetups.
3. **Open Educational Resources (OER)**: Printable vector posters, outreach pamphlets, and multilingual fact sheets accessible for everyone.

---

## 🛠️ Architecture & Tech Stack (技术架构)

This project is designed with minimal resource consumption in mind to ensure high performance on lightweight server infrastructure:

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | Next.js / Static HTML | Lightweight, SEO-friendly, low-bandwidth UI |
| **Backend / API** | Node.js / Nginx | Reverse proxy, static file distribution, registration API |
| **Database** | SQLite / PostgreSQL | Lightweight event registration & volunteer profiles |
| **Deployment** | Docker & Linux VPS | Portable, reproducible containerized deployment |

---

## 📂 Repository Structure (项目结构)

```text
├── docs/                # Public guidelines, nutrition references & printable flyers
├── src/
│   ├── components/      # UI components (navigation, event lists, recipe cards)
│   ├── pages/           # Platform pages & localized routing
│   └── styles/          # Lightweight styles
├── public/              # Static assets, Open Source icons & posters
├── docker-compose.yml   # Lightweight container orchestration
└── README.md
