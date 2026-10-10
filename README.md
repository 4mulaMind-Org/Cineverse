<div align="center">

# 🎬 Cineverse

### Book your show. Skip the queue. Feel the cinema.

A full-stack movie ticket booking platform with an editorial-magazine frontend and a battle-tested Spring Boot backend.

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.1.1-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-27-ED8B00?logo=openjdk&logoColor=white)](https://jdk.java.net/27/)
[![MySQL](https://img.shields.io/badge/MySQL-9.7-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Hibernate](https://img.shields.io/badge/Hibernate-7.4.5-59666C?logo=hibernate&logoColor=white)](https://hibernate.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![License](https://img.shields.io/badge/License-MIT-22C55E)](LICENSE)

[Live Demo](http://localhost:8082/cineverse.html) · [Report Bug](https://github.com/4mulaMind-Org/Cineverse/issues) · [Request Feature](https://github.com/4mulaMind-Org/Cineverse/issues)

</div>

---

## 📖 Overview

**Cineverse** is a modern cinema booking experience — no dark themes, no generic purple gradients. Inspired by the editorial layouts of A24 and the Criterion Collection, it pairs a warm, magazine-style interface with a production-grade REST API.

Select a film, pick your show, tap your seats, confirm. Done in under 20 seconds.

<div align="center">

> **Status:** Active development · **Version:** 1.0.0 · **Last updated:** October 2026

</div>

---

## ✨ Features

### 🎨 Frontend — The Interface

- **Editorial design language** — Playfair Display serif + Inter sans, warm cream palette, film grain texture
- **Ticket-stub cards** — perforated edges, dashed dividers, Netflix-style film numbering
- **Curtain animation** — the booking modal opens like a theater curtain
- **Visual seat map** — real aisle gaps, hover glow, live total calculation
- **Live marquee** — infinite scrolling headline bar
- **Search & filter** — search movies by title, genre, or language
- **Demo mode** — works offline with mock data; switch to live backend with one click
- **Toast notifications** — slide-in feedback for every action
- **Fully responsive** — mobile, tablet, desktop
- **Zero dependencies** — a single HTML file, no npm, no build step

### ⚙️ Backend — The Engine

- **REST API** covering movies, theaters, shows, seats, bookings, and payments
- **Layered architecture** — Controller → Service → Repository → Entity
- **JPA/Hibernate** with MySQL persistence and auto-schema updates
- **DTO mapping** — clean separation between database and API
- **Bean Validation** — `@Valid`, `@NotNull` on every incoming request
- **Global exception handling** — custom `ResourceNotFoundException`
- **Relationship cascading** — Booking → ShowSeat → Payment
- **Lombok** — zero boilerplate for getters, setters, constructors

---

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Backend**
- Java 27
- Spring Boot 4.1.1
- Spring Data JPA
- Hibernate 7.4.5
- MySQL 9.7
- Jakarta Bean Validation 3.1
- Lombok 1.18.48
- Maven

</td>
<td valign="top" width="50%">

**Frontend**
- Vanilla HTML5
- Modern CSS3 (Grid, Flexbox, CSS vars)
- ES2022 JavaScript
- Google Fonts
  - Playfair Display
  - Inter
  - JetBrains Mono
- Zero build tools

</td>
</tr>
</table>

---

## 🚀 Quick Start

### Prerequisites

| Tool | Version | Check |
|---|---|---|
| JDK | 21 or 27 | `java -version` |
| Maven | 3.9+ | `mvn -version` |
| MySQL | 8.0+ | `mysql --version` |

### 1. Clone

```bash
git clone https://github.com/4mulaMind-Org/Cineverse.git
cd Cineverse
