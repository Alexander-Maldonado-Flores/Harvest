# AGENTS.md — Harvest

## 1. Project

Harvest is a mobile-first financial planning application.

- Prototype deadline: December 1, 2026.
- Future: iOS, Android, and eventual web expansion.
- Preserve agricultural design, savings plants, seeds, debt pruning trees, Harvest Balance, and Harvest Projected Balance.
- Permanent slogan: "You reap what you sow."

Figma reference (design, not production code):
https://www.figma.com/make/XnmkUwvwJMI5VSejHaC6mx/Harvest-Savings-App

## 2. Architecture

- Mobile: React Native, JavaScript, Expo, Expo Router.
- Backend: Python, Flask, SQLite, Flask-SQLAlchemy.
- Forecasting: Python; communication: REST/JSON.
- Testing: pytest and mobile application testing.

Evaluate alternatives objectively. Do not change approved architecture, requirements, or dependencies without appropriate authorization.

## 3. Engineering Rules

- Base decisions on evidence, requirements, constraints, and trade-offs.
- Avoid unnecessary complexity, dependencies, duplication, and unrelated changes.
- Prioritize financial accuracy, reliability, security, maintainability, and usability.
- Inspect relevant files first; expand investigation when necessary.
- Reuse verified information, but never assume existing or generated code is correct.
- Disclose assumptions, conflicts, errors, risks, limitations, and technical debt.
- Preserve team contributions and applicable academic integrity requirements.
- Do not reduce necessary verification to conserve resources.

Consult the interim report, Kanban V2.0, approved engineering decisions, Figma, and technical documentation. Preserve all six user stories and 22 acceptance tests. Report missing or conflicting requirements rather than inventing resolutions.

## 4. Financial Rules

- Implement only approved financial calculation rules.
- Distinguish actual, planned, and hypothetical transactions.
- Separate financial account balances from bucket allocations.
- Prevent duplicate transactions and double counting.
- Use appropriate monetary precision.
- Verify calculations against independent expected results.
- Stop affected implementation when unresolved rules threaten financial accuracy or data integrity.

## 5. Repository Rules

Repository: Alexander-Maldonado-Flores/Harvest

Default branch: main

Foundation branch: setup/repository-foundation

- Verify repository, branch, Git state, and existing code before editing.
- Preserve history, existing contributions, and unrelated changes.
- Use descriptive branches with task IDs where applicable: feature/, bugfix/, docs/, test/, setup/, refactor/.
- Maintain mobile/, backend/, and docs/ unless restructuring is authorized.
- Never commit secrets, credentials, populated environment files, or private financial data.
- Do not modify the team repository, repository settings, or permissions without authorization.
- No unauthorized pull requests, merges, force-pushes, or history rewrites.
- Keep the foundation branch separate until integration is authorized.

## 6. Kanban Rules

- Maintain exactly 40 tasks: H-01 through H-40.
- Preserve task IDs, owners, and assignments.
- Do not modify Done or In Progress tasks.
- Revise To Do tasks only when authorized.
- Associate implementation work with its Kanban task.
- Obtain human approval before marking tasks complete.

## 7. Execution and Definition of Done

For each authorized task:

1. Review requirements, dependencies, and relevant code.
2. Implement only the authorized scope.
3. Write and execute relevant tests.
4. Review changes and update affected documentation.
5. Report files changed, decisions, dependencies, test results, acceptance criteria, risks, and remaining work.

A task is complete only when acceptance criteria are satisfied, relevant tests pass, no critical defects affect the task, documentation is current where necessary, and a human reviewer approves.

Distinguish passed, failed, and unexecuted tests. Never weaken tests to conceal defects.

Do not begin application implementation until the development foundation is authorized.

"You reap what you sow."
