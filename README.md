﻿<h1 align="center">
    <img src="readme/golang_logo.webp">
    <p>URL Shortner - GO + Redis + Fiber</p>
</h1>

## ⭐ ABOUT

A simple and efficient URL shortener service built with **Go, Fiber, Redis, Docker (and Compose).**

## 🔨 TOOLS

- [Go](https://go.dev/)
- [Fiber](https://gofiber.io/)
- [Redis](https://redis.io/)
- [Docker](https://www.docker.com/)

## ✨ GETTING STARTED

Ensure you have the following installed on your system:

- Docker
- Docker Compose
- Postman

## 🔧 INSTALLATION

1. Clone the repository:
```bash
git clone https://github.com/rayantx/url-shortner.git
```

2. Build and run the containers using Docker Compose:
```bash
docker-compose up --build
```

## 🎡 USAGE

**API ENDPOINT**

**POST** in **Postman**
```bash
http://localhost:3000/api/v1/
```
Your **REQUEST**
```bash
{"url":"your_link"}
```
Your **REPONSE**
```bash
{
    "url": "your_link",
    "short": "your_link_shortened",
    "expiry": 24,
    "rate_limit": 5,
    "rate_limit_reset": 25
}
```


