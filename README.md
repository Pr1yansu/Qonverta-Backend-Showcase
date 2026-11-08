<div align="center">

# Qonverta

**Document and media management backend with server-side conversion and reporting.**

![Java 21](https://img.shields.io/badge/Java%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)

</div>

> [!NOTE]
> **Showcase repository.** This is client work built at Runtime Solutions, and its source code is private. This page documents the product, my role and the engineering behind it.

## Overview

Qonverta manages documents, categories and media for its users. Conversion runs on the server (JavaCV/FFmpeg) instead of on the device, and the service generates PDF, Excel and CSV reports, with rate limiting, auditing and push notifications.

## My role

**Production setup** (5 commits): I prepared the service for production: environment configuration with safely escaped values, database bootstrap, conditional Firebase configuration, and the Spring Boot 4 JSON dependency fix. The core modules were built by a teammate.

## Tech stack

| Layer | Technologies |
|---|---|
| Backend | Java 21, Spring Boot, Spring Security, Spring Data JPA, Hibernate Envers |
| Media & docs | JavaCV / FFmpeg, PDFBox, iText, Apache POI, Commons CSV |
| Platform | MySQL, Bucket4j, Firebase, S3-compatible storage |

## What I worked on

- Production environment configuration and safe sourcing of env files in deployment scripts.
- Automatic database creation on first boot.
- Conditional Firebase activation so environments without credentials still start.
- Dependency fixes for JSON handling on Spring Boot 4.

---

<div align="center">

**Priyansu Chowdhury**: Backend-leaning full-stack developer (Java / Spring Boot · Next.js / TypeScript)

[LinkedIn](https://linkedin.com/in/priyansu-chowdhury) · [GitHub](https://github.com/Pr1yansu)

</div>
