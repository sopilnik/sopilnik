# Alexandr Sopilnik

I build web, desktop and mobile apps and fix broken ones, including apps generated with AI tools that now need to work for real users. I use TypeScript, React and Next.js for the web, Tauri for desktop and React Native for mobile. On the backend it's Node.js and Rust.

## What I work on

- New web apps and sites with my own interface design, coded by hand
- Desktop apps with Tauri and mobile apps with React Native
- Bug fixes and cleanup in existing React, Next.js and Node.js projects
- Apps built with AI tools: flaky logins, failing payments, missing access rules, code nobody wants to touch
- Backends and APIs in TypeScript or Rust, payment and third-party integrations, PostgreSQL with row-level security
- Rust CLI tools and scrapers
- Performance fixes for slow pages, endpoints and queries

## Public work

- [Formline](https://formline.sopilnik.dev): a demo poster store built with Next.js and TypeScript. It has a collection filter, search, a cart and a Stripe checkout in test mode. The [source](https://github.com/sopilnik/poster-store) has unit and end-to-end tests that run in CI on every push.
- [reqwest-rotate](https://github.com/sopilnik/reqwest-rotate): a reqwest client with proxy rotation, per-host rate limiting and retries with backoff. Published on [crates.io](https://crates.io/crates/reqwest-rotate), with 101 tests and an MSRV check in CI.

Most of my Rust time goes into a tactical management game built on Bevy ECS. The repository is private for now.

## Client work (under NDA, so no names)

- Backend for an educational platform: axum microservices with Kafka between them, PostgreSQL and Redis, gRPC for internal calls and REST for the frontend.
- Rewrote a legacy PHP backend in Node.js/TypeScript and kept the public API compatible, so the frontend needed no changes. Median response time on the main endpoints dropped roughly 3×.
- Moved a jQuery frontend to React page by page while the product stayed live.
- Worked on paid access enforced inside PostgreSQL with row-level security policies and a separate role for each subscription tier.

## How I work

I work async, with no calls. I write down the scope before I start and send a short written update at the end of each working day. My working hours are 10:00–22:00 UTC+5.

## Hire me

I list my services, starting prices and contact details on [sopilnik.dev](https://sopilnik.dev).

You can also hire me on these sites:

- [Upwork](https://www.upwork.com/freelancers/sopilnik) for hourly or fixed-price work
- [Fiverr](https://www.fiverr.com/sopilnik) if you want to order a fixed-price gig
- [Kwork](https://kwork.com/user/sopilnik), where each service shows its price and delivery time
