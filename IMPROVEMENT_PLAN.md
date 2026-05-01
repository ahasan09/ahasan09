# Improvement Plan: ahasan09

## Goal
Update `README.md` so it mirrors the narrative, section order, and professional tone of `ahasan09.github.io/index.html`, while staying GitHub-profile friendly (Markdown-first, no custom CSS dependency).

## Success Criteria
- README has the same strategic flow as the website: Hero -> Impact -> Experience -> Stack -> Selected Work -> Recommendations -> Education -> Contact.
- Messaging is evidence-based (numbers, outcomes, scale) instead of generic skill claims.
- Skill coverage reflects full capability set (including Java/Kotlin, WebSocket, Docker, Azure/AWS, MSSQL, Bitbucket CI/CD).
- Featured repositories and public proof align with claims.

## Source-of-Truth Mapping (Website -> README)
1. Hero
  - Keep role headline, location/context, and current company.
  - Keep concise positioning statement around nation-scale frontend architecture.
2. Impact
  - Include measurable highlights: 13+ years, 10K+ Norwegian archive users, 100K+ EU fintech users, 5 parallel Angular migrations.
3. Experience
  - Preserve case-study style for Cefalo and SELISE (Problem/Approach/Outcome or Scale/Ownership).
  - Keep earlier career compressed to avoid visual overload.
4. Stack
  - Present grouped stack categories exactly as in website intent: Frontend, Backend, Data & Messaging, Cloud & Delivery, Quality & Practice.
5. Selected Work
  - Keep curated and opinionated (not full repo dump).
6. Recommendations
  - Keep 2-4 strong quotes with attribution.
7. Education & Certification
  - Keep concise, tabular or card-like Markdown.
8. Contact
  - End with clear hiring/collaboration CTA and links.

## Execution Plan

### Phase 1: Information Architecture Alignment
- Rewrite README section order to match the website.
- Remove decorative noise that weakens scannability.
- Keep profile badges minimal and relevant.

### Phase 2: Content Rewrite (High-Impact)
- Replace broad claims with outcome-backed statements.
- Normalize tone to senior/staff level: leadership + delivery + architecture.
- Use concise bullets and short paragraphs for recruiter readability.

### Phase 3: Skills and Evidence Consistency
- Ensure each major claimed skill appears in:
  - Stack section, and
  - either Experience or Selected Work evidence.
- Call out gaps where public repo evidence is still missing.

### Phase 4: Final Polish
- Verify links, badges, and image endpoints.
- Ensure mobile readability on GitHub.
- Validate section headers for quick skim.

## Full Skill Set (for README)

| Category | Expert | Mid |
|---|---|---|
| Frontend | Angular, React, TypeScript | — |
| Backend | NestJS, Node.js/Express, Django, DRF | Java, Kotlin |
| Databases | MongoDB, MSSQL, PostgreSQL | — |
| Real-time | WebSocket, SignalR, RabbitMQ | Kafka, ActiveMQ |
| Cloud | Azure | AWS |
| DevOps | Docker, GitHub Actions, Azure DevOps | Bitbucket CI/CD, Jenkins |
| Testing | Playwright, Jest, pytest | Jasmine, Karma |
| Languages | TypeScript, JavaScript, Python, C# | Java, Kotlin |

## Gaps in Public Proof (Repo Opportunities)
The following capabilities are weakly represented in public repositories and should be improved over time:
- Java/Kotlin: publish a focused Spring Boot or Kotlin service demo.
- WebSocket: publish a small real-time app (chat/live dashboard).
- Docker: add a clear Docker + docker-compose setup to one flagship backend repo.
- Azure/AWS: expose infra/deployment artifacts (workflow, IaC, or deployment docs).
- MSSQL: add one sample with EF/Core + SQL Server.
- Bitbucket CI/CD: mirror equivalent pipeline patterns in GitHub Actions docs/workflows.

## Repository Hygiene
- Repository descriptions: done.
- Pin these 6 repos for profile breadth:
  1. `game-hub`
  2. `nestjs-task-management`
  3. `playwright-practice-app`
  4. `angular-signature-pad`
  5. `csharp-design-patterns`
  6. `twitter-clone`
- Add Topics to all repositories for discoverability.

## Definition of Done
- `README.md` mirrors the website's narrative structure.
- Claims are backed by measurable outcomes or linked repositories.
- Skill matrix and experience sections are internally consistent.
- Profile is optimized for recruiters/hiring managers scanning in under 60 seconds.
