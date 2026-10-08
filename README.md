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
| Mobile client | React Native, JavaScript | [link](https://github.com/...) |
| Web API | PHP, MySQL | [link](https://github.com/...) |
| [Admin / other part] | [stack] | [link](https://github.com/...) |

---

## My contribution

[Pick ONE of these framings and be specific:]

<!-- If you mainly did the API -->
I designed and built the PHP REST API — endpoint structure, request
validation, and the MySQL queries backing product listing and order
creation. I also handled session-based authentication for the mobile client.

<!-- If you mainly did mobile -->
I built the React Native mobile client — product browsing, cart state,
and the checkout flow that consumes the REST API. I also handled the
API integration layer and error states.

<!-- If you did a mix -->
I worked across the stack: [X] on the mobile client, [Y] on the API,
and [Z] on integration between the two.

---

## Screenshots

<!-- Add 2-3 images here. Mobile app + API response + maybe a schema diagram -->

| Mobile | API | Database |
|---|---|---|
| ![mobile](docs/mobile.png) | ![api](docs/api.png) | ![schema](docs/schema.png) |

---

## Tech stack

- **Frontend:** React Native, JavaScript
- **Backend:** PHP, REST
- **Database:** MySQL
- **Auth:** [session-based / JWT / whatever you used]

---

## Context

Built as a high school capstone project (2024) with a team of [N].
Course requirements split each component into a separate repository;
this repo consolidates the architecture for portfolio purposes.

---

## Links

- Mobile: [repo URL]
- API: [repo URL]
- [Other]: [repo URL]
