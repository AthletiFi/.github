# AthletiFi Sport Inc. | The Home of Pleyr 🚀

<img src="/images/pleyr_meta.webp" alt="Pleyr Banner" width="800"/>

Welcome to the official GitHub organization for **AthletiFi Sport Inc.**, the creators of **Pleyr**.

**Pleyr** is a gamified, video-centric social platform designed to give youth athletes ownership of their athletic journey. Our mission is to transform the fragmented moments of youth sports into a structured, longitudinal data asset that empowers players, coaches, and the entire sports ecosystem.

## 🌟 About Pleyr

Pleyr directly addresses the "broken pipeline" issue where young athletes lose access to their own game footage. We provide a centralized **Team Video Vault** where parents, coaches, and teammates can upload full games, giving athletes direct access to clip and share their own highlights.

Beyond video, the platform builds a comprehensive athlete profile through key features like shareable, trading-card-style digital player cards, an athlete-first social feed, and a Game Log for post-game reflections that showcase character and resilience.

To drive long-term use, we've built a robust gamification layer that makes building an athletic legacy as engaging as playing the sport itself.

## 🚀 Core Features

- **Team Video Vault**: A central, shared repository for all team game footage. No more lost moments.
- **Highlight Clipper**: An intuitive tool for athletes to find, clip, and share their best plays directly from full-game videos.
- **Digital Player Cards**: Customizable, trading-card-style profiles that serve as an athlete's digital identity.
- **Athlete-First Feed**: A public social feed where only players can post, keeping the focus on their journey and accomplishments.
- **Game Log**: A private space for post-game reflections, allowing players to document insights, showcase character, and track mental growth.
- **Gamification Engine**: Streaks, badges, and unlockable rewards that encourage consistent content creation and engagement.

## 📈 Our Vision & Business Model

Our ultimate vision is to become the definitive system of record for an athlete's career. By capturing a player's journey from their first goal to their college commitment, we are building a high-value, longitudinal data asset.

Pleyr's multi-phased monetization strategy includes:

1. **Freemium Subscriptions** for families and teams.
2. **B2B Partnerships** and team fundraising tools.
3. A high-margin **Data Marketplace** providing insights and access to college recruiters and sports brands.

## 💻 Our Technology

Pleyr is a **modern, decoupled monolith** built on the Next.js App Router, combining development velocity with clean architectural boundaries. We pride ourselves on building sophisticated, custom solutions to deliver a best-in-class user experience.

### Core Tech Stack

| Category                 | Technology / Service                                     |
| ------------------------ | -------------------------------------------------------- |
| **Framework**            | Next.js 14+ (App Router)                                 |
| **Language**             | TypeScript                                               |
| **Deployment & Hosting** | AWS Amplify / Terraform                                  |
| **Authentication**       | AWS Cognito                                              |
| **Database**             | PostgreSQL on AWS RDS                                    |
| **Data Access**          | **Custom Lightweight ORM & SQL Wrapper**                 |
| **File Storage**         | AWS S3                                                   |
| **Video Processing**     | Mux                                                      |
| **Image Processing**     | Go/WebAssembly (Client-side), AWS Lambda (Server-side)   |
| **Payments**             | Stripe                                                   |
| **Error Monitoring**     | Sentry / Signoz                                          |

#### Technical Differentiators

- **Custom Data Access Layer**: We built a custom, two-tiered data access stack—a secure SQL wrapper and a type-safe lightweight ORM—that provides the performance of raw SQL with the developer experience of modern ORMs.
- **Client-Side Go/WASM**: We compile Go to WebAssembly to perform high-performance image processing directly in the user's browser, offloading server computation and creating a faster, more responsive UI.
- **Robust AWS Infrastructure**: The entire platform is built on a scalable, secure AWS foundation, leveraging services like RDS, S3, Lambda, and Cognito to ensure reliability and performance.

## 🤝 Get Involved

We are building the future of youth sports. Whether you're a developer, investor, or a potential partner, we'd love to connect.

- 🌐 **Visit our website**: [pleyr.com](https://pleyr.com)
- 📧 **General Inquiries**: [info@pleyr.com](mailto:info@pleyr.com)
- 💼 **Investment Inquiries**: [ir@pleyr.com](mailto:ir@pleyr.com)

---

💙 From all of us at AthletiFi & Pleyr, thank you for being a part of this exciting journey!
