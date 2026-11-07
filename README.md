# UC-CCJE Platform

The College Platform of the College of Criminal Justice Education (CCJE), University of the Cordilleras.

One private system for the college's committees, records, and reports. It started as the research repository and is now the base for every committee.

## Committees

| # | Committee | Folder | Status |
|---|-----------|--------|--------|
| 1 | Research | [committees/01-research](committees/01-research) | Built |
| 2 | Community Extension | [committees/02-community-extension](committees/02-community-extension) | Planned |
| 3 | Alumni | [committees/03-alumni](committees/03-alumni) | Planned |
| 4 | Student Development | [committees/04-student-development](committees/04-student-development) | Planned |
| 5 | Faculty Development | [committees/05-faculty-development](committees/05-faculty-development) | Planned |
| 6 | Quality Assurance | [committees/06-quality-assurance](committees/06-quality-assurance) | Planned |
| 7 | Other Programs | [committees/07-other-programs](committees/07-other-programs) | Planned |

## Shared features

- **Full papers database.** Complete papers are stored in the database, not just their records.
- **Program Chair content validation.** Nothing is published until a Program Chair approves it. See [docs/content-validation.md](docs/content-validation.md).
- **Roles and approvals.** Only admins add, delete, and approve. Everyone else requests changes.
- **Privacy first.** Private access only. AI runs locally, not on a cloud service.

## Repository layout

```
UC-CCJE-Platform/
├── README.md
├── ROADMAP.md
├── docs/
│   ├── architecture.md
│   └── content-validation.md
├── platform/          shared code: auth, roles, database, AI, exports
├── committees/        one folder per committee
└── data/              local data only, never committed
```

## Privacy

The repository must be private. Research data, full papers, and spreadsheets stay out of Git. `data/` is ignored in `.gitignore`.

## Roadmap

See [ROADMAP.md](ROADMAP.md).
