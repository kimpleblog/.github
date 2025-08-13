Kimple DevOps Series — Central Index

> **Central catalog** รวมทุกโปรเจคจาก P01 → P12 ของซีรีส์ Dev → DevOps พร้อมลิงก์รีโป/เดโม/สถานะความคืบหน้าในที่เดียว

---

## ภาพรวมซีรีส์

-   เป้าหมาย: สร้างเว็บบล็อก + API + DB + CI/CD + Docker + Deploy บน Cloud และ Observability แบบครบเส้นทาง
-   รูปแบบ: **หลายรีโป** (แยกตามโปรเจค) อยู่ใต้ GitHub Organization เดียว kimpleblog-devops
-   การตั้งชื่อรีโป: p01-static-landing, p02-vanilla-js-blog, p03-express-api, …
-   Tag/Topic ที่ใช้ร่วมกัน: devops-series, node, express, react, docker, mongodb, tailwind

---

## สารบัญโปรเจค (Table of Contents)

| Code | Project                                      | Repo                                                     | Demo                                                     | Tech                      | Status  |
| ---- | -------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------- | ------------------------- | ------- |
| P01  | Static Landing (HTML + Tailwind)             | https://github.com/kimpleblog-devops/p01-static-landing  | https://kimpleblog-devops.github.io/p01-static-landing/  | HTML, Tailwind            | Finished  |
| P02  | Vanilla JS Blog (LocalStorage)               | https://github.com/kimpleblog-devops/p02-vanilla-js-blog | https://kimpleblog-devops.github.io/p02-vanilla-js-blog/ | HTML, JS, Tailwind        | In Progress |
| P03  | Express API (In-memory) + Docker + CI        | https://github.com/kimpleblog-devops/p03-express-api     | —                                                        | Node, Express, Docker, CI |         |
| P04  | Express + MongoDB (Mongoose) + Compose       | https://github.com/kimpleblog-devops/p04-express-mongo   | —                                                        | Express, MongoDB, Compose |         |
| P05  | Auth & Security (JWT, Helmet, Rate limit)    | https://github.com/kimpleblog-devops/p05-auth-security   | —                                                        | JWT, bcrypt, Helmet       |         |
| P06  | React Client (Vite + Tailwind)               | https://github.com/kimpleblog-devops/p06-react-client    | —                                                        | React, Vite, Tailwind     |         |
| P07  | Monorepo (API + Web) + CI Matrix + Lint/Test | https://github.com/kimpleblog-devops/p07-monorepo        | —                                                        | Workspaces, ESLint, CI    |         |
| P08  | Dockerize Prod + GHCR + Compose Prod         | https://github.com/kimpleblog-devops/p08-docker-prod     | —                                                        | Docker, GHCR, Compose     |         |
| P09  | Deploy AWS EC2 + Nginx + HTTPS               | https://github.com/kimpleblog-devops/p09-deploy-ec2      | https://your-domain.com                                  | EC2, Nginx, TLS           |         |
| P10  | Observability & Backup                       | https://github.com/kimpleblog-devops/p10-observability   | —                                                        | Winston, Metrics, Backup  |         |
| P11  | Extras A (S3, Search, RBAC)                  | https://github.com/kimpleblog-devops/p11-extras-a        | —                                                        | S3, Search, RBAC          |         |
| P12  | Extras B & Capstone (E2E, IaC)               | https://github.com/kimpleblog-devops/p12-capstone        | —                                                        | Playwright, Terraform     |         |

---

## แผนงานแบบสัปดาห์ (Roadmap)

-   **W1:** P01 — Static Landing (Deploy → GitHub Pages)
-   **W2:** P02 — Vanilla JS Blog (CRUD + Search)
-   **W3:** P03 — Express API + Docker + CI
-   **W4:** P04 — MongoDB + Compose + Seed
-   **W5:** P05 — Auth & Security (JWT)
-   **W6:** P06 — React Client + Auth flow
-   **W7:** P07 — Monorepo + CI Matrix + Lint/Test
-   **W8:** P08 — GHCR Images + Compose Prod
-   **W9:** P09 — EC2 Deploy + Nginx + HTTPS
-   **W10:** P10 — Observability + Backup
-   **W11–12:** Extras & Capstone (E2E, IaC)

---

## แผงสถานะ (Progress Tracker)

-   [x] P01 — Static Landing
-   [ ] P02 — Vanilla JS Blog
-   [ ] P03 — Express API + CI
-   [ ] P04 — Express + MongoDB
-   [ ] P05 — Auth & Security
-   [ ] P06 — React Client
-   [ ] P07 — Monorepo + CI Matrix
-   [ ] P08 — Dockerize Prod + GHCR
-   [ ] P09 — Deploy EC2 + HTTPS
-   [ ] P10 — Observability + Backup
-   [ ] P11 — Extras A
-   [ ] P12 — Capstone

---

## License

MIT © kimpleblog
