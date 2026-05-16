<p align="center">
<img width="1672" height="941" alt="Banner" src="https://github.com/user-attachments/assets/2644d8a0-5d13-4414-8848-387549300c20" />
</p>

# Hi, I'm Minh Khoa 👋

I'm a backend developer who enjoys building things, breaking them, and figuring out how they actually work.

---

## 🧰 Tech I work with

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)

---

## 📌 About me

* Interested in backend development and API design
* I learn by building first, then refining my understanding through iteration
* Applying context prompting in personal projects to make AI a practical part of my workflow
* Always working toward cleaner, more maintainable code
---

## 🧪 Featured Project

### 🎮 GameTopUp — *My Backend Playground for Game Top-up Flows*

This is my **personal backend playground** where I apply what I've learned about ASP.NET Core and system design to experiment with a real-world problem: transforming a manual, chat-based game top-up workflow into a structured platform.

* **Tech Stack:** ASP.NET Core (Web API), Dapper, MySQL, Docker.
* **Architecture:** Layered Architecture (Controllers → Application Services → Business Services → Repositories)

#### 🎯 Motivation
Small game shops often handle discount top-up orders manually via chat, which easily leads to human errors, missed orders, and slow processing. This system aims to centralize that entire flow into a manageable backend platform.

#### 🧠 What I'm building & exploring in this project:
* **Order State Machine:** Moving away from manual chat tracking by setting up a structured queue with explicit status transitions (`Pending` → `Paid` → `Processing` → `Completed` / `Cancelled`) to handle the order lifecycle properly.
* **Pricing & Margin Logic:** Handling the business logic behind intermediary pricing, focusing on how to programmatically calculate profit margins based on wholesale costs, retail prices, and discount rates.
* **Internal Wallet & Audit Flow:** Working on a basic deposit/withdrawal system with QR-based flows, while learning how to use `BalanceBefore` and `BalanceAfter` to ensure financial traceability.
* **Concurrency & Safety:** Exploring backend techniques to handle concurrent transaction requests safely, aiming to keep financial data consistent and prevent double-spending as the system expands.
