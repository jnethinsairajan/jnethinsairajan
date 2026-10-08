# CivicPulse AI

**Make public-project progress and spending easier for citizens to understand and scrutinize.**

CivicPulse AI is a civic transparency platform concept that brings public-project progress, spending, milestones, locations, and citizen feedback into one place. It is designed to help citizens, journalists, civil-society groups, and public officials understand project status and identify issues that deserve closer review.

## Planned capabilities

- **Project directory:** browse public projects by location, department, category, and status.
- **Progress tracking:** compare planned milestones and timelines with reported progress.
- **Budget transparency:** display sanctioned budgets, reported expenditure, and budget deviations when reliable data is available.
- **Map and timeline views:** understand where projects are happening and how they are progressing.
- **Citizen feedback:** submit and review project-related reports and recurring concerns.
- **AI-assisted analysis:** flag potential delays, budget deviations, and repeated complaint themes for human review.
- **Auditability:** show data sources, update dates, and evidence behind important flags wherever possible.

## Important data principle

CivicPulse AI is intended to support public scrutiny, not to make unsupported accusations. A flagged deviation is an indicator for review, not proof of wrongdoing. Clearly distinguish verified records, user-submitted reports, estimates, and AI-generated observations.

## Intended architecture

The project bundle supplied for this repository references a TypeScript application with a React/Vite client, an Express server, shared types, and a MySQL database integration. The original application source files are not included in the combined text export currently available, so this repository README does **not** claim that the application is already runnable.

## Development status

**Repository setup / source import pending.**

To turn this repository into a runnable application, add the original project directory and its source files, including at minimum:

- `package.json` and the package-manager lockfile
- `client/` frontend source
- `server/` backend source
- `shared/` types and utilities, if used
- `vite.config.*`, `tsconfig.json`, and other required configuration
- database schema/migrations and a sample environment file such as `.env.example`

Do not commit real credentials, API keys, production database passwords, or private environment files.

## Suggested next steps

1. Import the complete original source tree.
2. Review environment variables and database setup.
3. Install dependencies and run the project's checks/build.
4. Add sample data clearly labelled as demo data.
5. Configure deployment only after the app builds and secrets are stored securely.

## Project motto

**Transparency. Accountability. Public trust.**
