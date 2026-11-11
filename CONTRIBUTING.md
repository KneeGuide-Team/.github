# Contributing to KneeGuide

Thank you for your interest in KneeGuide. This organization contains a medical-technology prototype, so contributions must preserve technical accuracy, patient safety, privacy and clear prototype boundaries.

## Before contributing

1. Read the target repository README completely.
2. Search existing issues before opening a new one.
3. Do not submit real patient records, health information, credentials, tokens, OTP values or production database content.
4. Do not describe experimental capabilities as clinically validated.
5. For security concerns, follow [`SECURITY.md`](./SECURITY.md) rather than opening a public issue.

## Repository scope

- `kneeguide-frontend`: React product experience, routes, UI, localization and API clients.
- `kneeguide-backend`: Django REST APIs, authentication, persistence, permissions and deployment.
- `.github`: organization profile, governance and community-health files.

## Suggested workflow

1. Fork the relevant public repository.
2. Create a focused branch from the default branch.
3. Keep application and documentation changes logically separate.
4. Add or update tests for behavior changes.
5. Run the repository's documented checks.
6. Open a pull request explaining the problem, solution, verification and any medical/safety implications.

## Pull-request expectations

- No secrets, private data or generated credentials.
- No database migrations without a documented schema requirement.
- No weakening authentication, authorization, CSRF, CORS, password, OTP or transport security.
- No medical claims without appropriate evidence and team review.
- UI work must preserve English/Arabic support, responsive behavior and accessibility.
- AI work must include role controls, source-aware context, safety constraints, validation and escalation.
- IoT work must document calibration, timestamps, units, data validation, device identity and integrity.

Maintainers may request changes or decline contributions that exceed the prototype's safety, privacy or architectural scope.
