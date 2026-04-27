# Improvement Plan: ahasan09

## Overview
GitHub profile README. Functional but could better showcase skills and activity with richer content and dynamic data. Several areas of expertise (databases, cloud, Java/Kotlin, WebSocket, Docker) are not represented in current public repos at all.

## Full Skill Set (for profile README)

| Category | Expert | Mid |
|---|---|---|
| **Frontend** | Angular, React, TypeScript | — |
| **Backend** | NestJS, Node.js/Express, Django, DRF | Java, Kotlin |
| **Databases** | MongoDB, MSSQL, PostgreSQL | — |
| **Real-time** | WebSocket | — |
| **Cloud** | — | Azure, AWS |
| **DevOps** | Docker, Bitbucket CI/CD | — |
| **Testing** | Playwright, Jest, pytest | — |
| **Languages** | TypeScript, JavaScript, Python, C# | Java, Kotlin |

## Improvements

### Dynamic Content (optional)
- Add a Wakatime or similar coding activity widget if time tracking is in use

### Missing Repos (skills not represented publicly)
The following skills have no public repos demonstrating them — consider adding sample projects:
- **Java / Kotlin** — no public repos exist; a Spring Boot REST API or Android app would fill this gap
- **WebSocket** — no public repos; a simple real-time chat or live dashboard demo would showcase this
- **Docker** — used in projects but no standalone Docker/compose demo; consider Dockerizing `nestjs-task-management` or `express-mongodb-api` and pushing the compose file
- **Azure / AWS** — no cloud deployment configs are public; adding a `terraform/` or deployment workflow to any backend repo would signal cloud experience
- **MSSQL** — no public repos use it; could add a branch to `dotnet-delegate-pipeline` or `csharp-design-patterns` demonstrating Entity Framework + MSSQL
- **Bitbucket CI/CD** — pipelines live in Bitbucket, not visible here; consider mirroring a `bitbucket-pipelines.yml` example or adding equivalent GitHub Actions to existing repos

### Repository Hygiene
- ~~All repo descriptions are now set~~ ✓ done
- Pin these 6 repos using GitHub's pinned repos feature (covers frontend, backend, testing, library, .NET, Python):
  1. `game-hub`
  2. `nestjs-task-management`
  3. `playwright-practice-app`
  4. `angular-signature-pad`
  5. `csharp-design-patterns`
  6. `twitter-clone`
- Add GitHub Topics to all repos for discoverability — suggested topics per repo:
  - `game-hub` → `react`, `typescript`, `vite`, `chakra-ui`, `react-query`
  - `nestjs-task-management` → `nestjs`, `postgresql`, `typeorm`, `jwt`, `rest-api`
  - `playwright-practice-app` → `playwright`, `e2e-testing`, `angular`, `typescript`
  - `angular-signature-pad` → `angular`, `signature-pad`, `canvas`, `npm-package`
  - `csharp-design-patterns` → `csharp`, `dotnet`, `design-patterns`, `gof`
  - `twitter-clone` → `django`, `python`, `twitter-clone`, `full-stack`
  - Apply similarly to remaining repos
