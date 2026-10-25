# Cancer Screening Coordination Room

## One-sentence benefit
Helps health authorities and care networks coordinate equitable, quality-assured cancer screening programmes.

## Live demo
Run the Java service and Angular application locally to use the complete experience.

## Screenshots
![cancer screening coordination workspace](docs/screenshot.png)

## Main features
Search screening programmes, create a regional rollout, progress readiness actions and monitor approval and high-priority gaps.

## Technology used
Angular, TypeScript, signals, computed state, server rendering, Spring Boot and Java.

## Installation instructions
Start the backend with `cd backend && mvn spring-boot:run`. In another terminal run `npm install && npm start`.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Health authorities, screening centres, laboratories and referral teams need shared evidence for coverage, quality and follow-up.

## Key workflows
Teams can find a screening programme, add a validated regional rollout and advance readiness work to approval.

## Angular framework highlights
The interface uses standalone components, signals, computed values, OnPush change detection, built-in control flow and SSR-safe loading.

## Java backend highlights
The Spring Boot service provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
Angular HttpClient connects signal-based state to the Java API and updates the visible board after every write.

## Accessibility and responsive behaviour
Semantic structure, labelled controls, visible focus, high contrast and compact responsive tables support varied users and devices.

## Verification commands
Use `npm test -- --watch=false`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains the Angular experience, `backend` contains the Java service, and `docs` contains verified media.

## Tradeoffs
Records are held in memory for demonstration speed; operational use would add identity, durable storage and screening programme data integrations.

## Roadmap
Add population registries, quality indicators, referral pathways, authority sign-off, multilingual notices and audit-ready persistence.
