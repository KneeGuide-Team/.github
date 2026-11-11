# KneeGuide Project Governance

## Ownership

The KneeGuide GitHub organization is administered by its designated organization owners. Repository write and administrative access is granted explicitly according to project responsibilities.

## Decision areas

- Clinical-domain decisions require review from the clinical/medical lead.
- Architecture, backend, security and deployment decisions require engineering-owner review.
- UI/UX and product-experience decisions require design and engineering review.
- AI and IoT changes require explicit safety, privacy, validation and failure-mode review.

## Access principles

- Public repositories are readable by reviewers and the community.
- Public visibility does not grant modification access.
- Organization base permissions should remain `None` unless a documented need is approved.
- Write, maintain and admin permissions follow least privilege.
- Secrets and production credentials must never be stored in repositories.

## Change management

Significant changes should be proposed through an issue or pull request and should document scope, risk, verification and rollback considerations. Database, authentication, permission, deployment, sensor and AI changes require proportionate review and testing.

## Prototype boundaries

KneeGuide documentation must distinguish implemented functionality, partial implementation, demonstration/mock data, planned work and unverified hardware. The organization does not claim clinical effectiveness, medical-device certification, regulatory approval or autonomous medical decision-making.
