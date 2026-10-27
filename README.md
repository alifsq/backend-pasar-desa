# Pasar Desa — BUMDes Digital Marketplace API

[![Go Version](https://img.shields.io/badge/Go-1.22+-00ADD8?style=flat&logo=go)](https://golang.org/) [![Architecture](https://img.shields.io/badge/Architecture-Clean%20Architecture-blue)](#) [![Status](https://img.shields.io/badge/Status-In%20Development-yellow)](#)

A scalable RESTful backend service engineered to digitize local village-owned enterprise (BUMDes) commerce and local food vendors.

---

## 📌 Background & Problem Statement

In many rural areas, major food delivery and marketplace platforms do not operate due to geographical and logistics constraints. To bridge this gap, local villagers and small business owners rely on WhatsApp groups to buy and sell home-cooked meals, daily produce, and local goods.

However, as the merchant base grows daily, relying on WhatsApp creates severe operational bottlenecks:
- **Information Overload:** High message volume causes product listings and order messages to get buried quickly.
- **Unstructured Inventory & Catalog:** No centralized place for local merchants to showcase products or manage daily stock.
- **Order Inefficiency:** Absence of structured ordering leads to missed transactions and poor tracking.

---

## 💡 The Solution

**Pasar Desa** solves this by providing a lightweight, structured digital marketplace platform tailored for village enterprises (BUMDes) and local vendors:
- **Centralized Product Showcase:** Replaces chaotic group chats with a structured catalog for local vendors and food merchants.
- **Streamlined Order Flow:** Automates order creation and inventory tracking so merchants never miss an order.
- **Empowering Local Community:** Drives the village economy while keeping order flows simple and manageable.

---

## 🚀 Features

- **Framework & ORM**: Built using [Gin](https://github.com/gin-gonic/gin) and [GORM Gen](https://github.com/go-gorm/gen) for type-safe database queries.
- **Dependency Injection**: Integrated with [Google Wire](https://github.com/google/wire) for compile-time dependency injection.
- **Database Migrations**: Structured and version-controlled database schema migrations.
- **Logging**: High-performance structured logging powered by [Uber Zap](https://github.com/uber-go/zap).
- **Authentication**: JWT-based authentication featuring access token, refresh token workflows, and session revocation.
- **Email Delivery**: Automated email verification system with time-limited tokens sent via SMTP.
- **Configuration**: Centralized configuration management using [Viper](https://github.com/spf13/viper).
- **Security & Validation**: Request validation and structured logging integrated out of the box.

## 🛠️ Tech Stack

- **Language**: Go
- **Web Framework**: Gin
- **Database**: MySQL / PostgreSQL
- **ORM**: GORM & GORM Gen
- **Logging**: Uber Zap
- **Authentication**: JWT (JSON Web Tokens)
- **Dependency Injection**: Google Wire
- **Configuration**: Viper
- **Email Service**: SMTP

### Prerequisites

- [Go](https://golang.org/doc/install) (v1.27)
- [MySQL](https://www.mysql.com/) database server

---

## 💻 Built With

<p align="center">
  <em>Built with:</em><br><br>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Gin-008080?style=for-the-badge&logo=gin&logoColor=white" alt="Gin" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/GORM-00599C?style=for-the-badge&logo=go&logoColor=white" alt="GORM" />
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="JWT" />
  <img src="https://img.shields.io/badge/Uber_Zap-000000?style=for-the-badge&logo=uber&logoColor=white" alt="Uber Zap" />
  <img src="https://img.shields.io/badge/Google_Wire-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Wire" />
  <img src="https://img.shields.io/badge/Viper-5A29E4?style=for-the-badge&logo=go&logoColor=white" alt="Viper" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>
