# St. Mary's Sales Memory

A versioned, evidence-aware knowledge base for St. Mary's admissions telecalling, lead follow-up, sales coaching, and call analysis.

## Purpose

This repository is not a collection of internet sales tricks. Its job is to turn useful sales ideas into a St. Mary's-specific operating system by separating:

1. **Externally validated principles** — supported by peer-reviewed research or large conversation datasets.
2. **Operational hypotheses** — plausible techniques that must be tested on St. Mary's calls before becoming policy.
3. **Rejected / modified claims** — hype, manipulation, overstatement, or practices that do not fit education admissions.
4. **Internal evidence** — what St. Mary's own call and conversion data eventually proves works for our leads.

## Core rule

> Never promote a technique to "St. Mary's standard" only because a creator says it works. It should be evidence-supported, locally validated, or clearly marked as an experiment.

## Repository structure

- `knowledge/validated-principles.md` — canonical sales principles and evidence status.
- `knowledge/source-audit-2026-09-18.md` — review of the first five YouTube-derived transcripts.
- `playbooks/st-marys-telecalling-v0.1.md` — first St. Mary's-specific call flow.
- `evaluation/call-review-rubric-v0.1.md` — 100-point human/AI call review rubric.
- `evaluation/call-review-schema.json` — machine-readable output contract for future call analysis.
- `experiments/README.md` — how St. Mary's should test uncertain techniques using its own calls.

## Evidence labels

- **A — Strong:** peer-reviewed synthesis/meta-analysis or multiple strong sources; directly useful as a principle.
- **B — Good/transferable:** good evidence or large observational conversation data, but not specifically St. Mary's admissions.
- **C — Hypothesis:** creator experience, anecdote, or plausible mechanism; test locally before standardizing.
- **D — Reject / do not operationalize:** unsupported overclaim, deceptive/manipulative framing, or poor fit for education admissions.

## Privacy boundary

This repository is public as of 2026-09-18. Do **not** commit raw call recordings, phone numbers, student names, parent names, application details, or identifiable transcripts here.

Store only sanitized playbooks, schemas, aggregate learnings, and anonymized examples. Raw call data should stay in a private system (for example, the CRM/private database/private repository) with appropriate access controls.

## How the learning loop works

`New source -> source audit -> principle status -> controlled St. Mary's test -> call analytics -> promote / modify / reject -> versioned playbook`

Future call reviews should reference principle IDs from the canonical knowledge file so coaching remains consistent over time.
