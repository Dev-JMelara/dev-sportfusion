# dev-sportFusion

A full-stack sports supply platform built as a team capstone project.
Customers browse and purchase sports equipment through a React Native mobile
app backed by a PHP + MySQL REST API.

> **Note:** The original source was split across three repositories to meet
> course submission requirements. This repo serves as an index and architecture
> overview. Each component links to its own repository below.

---

## Architecture

    ┌─────────────────┐      HTTPS       ┌──────────────────┐
    │  Mobile Client  │ ───────────────▶ │   Web API        │
    │  React Native   │                  │   PHP + MySQL    │
    └─────────────────┘                  └──────────────────┘
                                                  │
                                                  ▼
                                         ┌──────────────────┐
                                         │   MySQL Database │
                                         └──────────────────┘

- **Mobile client** — React Native app for browsing products and placing orders
- **Web API** — PHP REST endpoints handling authentication, products, and orders
- **Database** — MySQL schema for users, products, orders, and inventory

---

## Components

| Component | Stack | Repo |
|---|---|---|
| Mobile client | React Native, JavaScript | [link](https://github.com/Dev-JMelara/SportsFusion_Android-app.git) |
| Web API | PHP | [link](https://github.com/Dev-JMelara/SportFusion.git) |
| [Database] | MySQL | [link](https://github.com/Dev-JMelara/SportsFusion-DB.git) |

---

## My contribution

I built the React Native mobile client — product browsing, cart state,
and the checkout flow that consumes the REST API. I also handled the
API integration layer and error states.


---

## Screenshots
(<img width="366" height="665" alt="image" src="https://github.com/user-attachments/assets/6f514ede-a7d8-4633-8103-13cc553c9968" /> <img width="357" height="767" alt="image" src="https://github.com/user-attachments/assets/916c7856-1bb9-4584-91bd-3c144cea99b3" />

---

## Tech stack

- **Frontend:** React Native, JavaScript
- **Backend:** PHP, REST
- **Database:** MySQL

---

## Context

Built as a high school capstone project (2024) with a team of [N].
Course requirements split each component into a separate repository;
this repo consolidates the architecture for portfolio purposes.

---

## Links

- Mobile: [link](https://github.com/Dev-JMelara/SportsFusion_Android-app.git)
- API: [link](https://github.com/Dev-JMelara/SportFusion.git)
- Database: [link](https://github.com/Dev-JMelara/SportsFusion-DB.git)

