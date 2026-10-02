# SalesOS runtime bundle

The JSON file in this folder is the **approved, public-safe sales-methodology package** consumed by SalesOS.

Rules:
- It contains sales principles, call flow, coaching boundaries and evaluation logic only.
- It must never contain raw calls, names, phone numbers, student records, private fee sheets, private scholarship rules or other lead/institute-sensitive data.
- SalesOS pins a specific bundle commit inside its private CRM repository. Live calls never fetch the latest GitHub branch automatically.
- Updating this repo does not silently change production. A manager/reviewer must approve a new bundle version, then SalesOS updates its pinned snapshot.
- Current institutional facts live in the private SalesOS institute bundle after being verified in the manager Google Doc.

This separation keeps research/playbook evolution auditable while protecting operational data and preventing stale or unapproved school facts from entering live AI responses.
