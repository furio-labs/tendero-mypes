# tendero-mypes — Product Specs & Guides

Documentation-only repo (no runnable code, no build, no tests). Audience: the team and Danilo (Contador Auditor). Language: Spanish.

> Read the mono-repo root `../AGENTS.md` first.

## Contents

| File | Purpose |
|---|---|
| `summary.md` | Product spec for the MYPE offering |
| `guia-auditor-contable.md` | Accountant's guide |
| `auditoria-contable.skill` | **Source bundle** (zip) of the audit skill. The usable, unzipped copy lives at the mono-repo root: `../.claude/skills/auditoria-contable/`. If you change the skill, update both (edit the unzipped copy, then re-zip here). |

## Canonical numeric spec

The accounting model spec (formulas, chart of accounts, KPIs) is **not** here — it's the Excel at `../docs/tendero-mypes-v4-simulacion-spec.xlsx`, validated by Danilo.

## Editing rules

- Spanish (Chilean), plain language — Danilo is the primary reader.
- Normative claims (tasas, plazos, NIIF) must cite the root skill `../.claude/skills/chile-normativa/` or its references — never from memory.
