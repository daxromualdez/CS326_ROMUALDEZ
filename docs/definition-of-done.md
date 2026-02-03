(# Definition of Done

This document describes the criteria that must be met for work (user stories, tasks, or features) to be considered "done" for this project. Meeting the Definition of Done (DoD) ensures consistent quality, readiness for release, and clear expectations across the team.

## General Criteria

- **Code complete:** Implementation matches the accepted design and passes a self-review by the author.
- **Automated tests:** Unit and integration tests added where applicable; all tests pass locally and in CI.
- **Code review:** Changes reviewed and approved by at least one other team member.
- **Static analysis / linting:** Code passes linting and style checks configured for the project.
- **Build:** Project builds successfully in CI with no errors or warnings considered blocking.

## Documentation

- **User-facing docs updated:** Any user-visible behavior changes have updated README, usage notes, or help text.
- **Developer docs updated:** Setup, configuration, or architecture notes updated when relevant.

## Acceptance and QA

- **Acceptance tests / criteria met:** Feature satisfies the acceptance criteria defined in the ticket.
- **Manual QA (if required):** Basic manual verification completed for UI flows or critical paths.
- **No critical defects:** No open critical/blocker bugs associated with the work.

## Deployment & Operations

- **CI green:** Continuous Integration job(s) pass for the change.
- **Migration scripts:** Any required DB or config migrations are included and tested.
- **Rollback plan:** For risky changes, a rollback/mitigation approach is documented.

## Security & Privacy

- **Security checks:** Known security issues addressed; dependencies checked for high/severe vulnerabilities.
- **Data/privacy:** Changes comply with any applicable data handling requirements.

## Optional (project/phase-specific)

- **Performance tested:** For performance-sensitive work, basic benchmarks or load checks completed.
- **Accessibility checked:** UI changes meet baseline accessibility expectations.

## Done Definition for Releases

- Release candidate is merged to the release branch, CI passing, release notes drafted, and sponsor/instructor acceptance obtained where required.

If a work item meets all applicable items above, mark it as Done. Items that are not applicable for a specific ticket should be explicitly noted on the ticket.
)

