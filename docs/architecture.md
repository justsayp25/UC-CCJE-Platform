# Architecture

Draft. To be settled as Phase 0 finishes.

## Principles

- Private by default. Access only for approved users.
- Local AI. No research data is sent to a cloud service.
- One platform, many committees. Shared code lives in `platform/`; each committee adds its own screens and data.
- Runs on one Windows machine first, then a UC IT server.

## Parts

- **Platform:** login, roles, approvals, audit log, file storage, PDF export, AI.
- **Committees:** each has its own records, forms, and reports.
- **Database:** records and full papers.
- **Local AI:** summaries and follow-up questions.

## To decide

- Final stack for the shared platform
- Where full papers are stored (database or file storage)
- Backup plan on the UC server
