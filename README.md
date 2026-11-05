# ERP Source Collection

This public repository collects **three third-party open-source ERP codebases** as separate, attributed source snapshots for technical evaluation and integration research.

**These are not original projects by this repository owner.** No claim is made to authorship, exclusive ownership, production readiness, or entitlement to sell exclusive source-code rights.

## Upstream projects

| Folder | Upstream | Stack | Upstream license |
| --- | --- | --- | --- |
| `projects/myerp/` | [amerfathullah/MyERP](https://github.com/amerfathullah/MyERP) | .NET / Angular | MIT |
| `projects/accountgo/` | [AccountGo/accountgo](https://github.com/AccountGo/accountgo) | .NET / React | AGPL-3.0-only |
| `projects/mini-erp/` | [vsiqueiravh-cell/mini-erp](https://github.com/vsiqueiravh-cell/mini-erp) | ASP.NET Core / React | MIT |

Each project is kept under its own folder with its original `LICENSE`, notices, and attribution. The licenses **apply independently**, and there is no single blanket license for the combined collection. AccountGo's AGPL terms require particular care with proprietary modifications and network deployments.

An import workflow at `.github/workflows/import-erp-sources.yml` downloads upstream repositories, records upstream commit hashes in `SOURCES.md`, and commits unmodified snapshots into the folders above.

## Important

- No application has been independently validated as production-ready or compliant with Brazilian tax rules.
- Integration with any existing ERP Core requires independent architecture, interface, security and migration review.
- Consult the applicable third-party licenses before modifying, distributing, hosting or selling related services.
