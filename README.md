# Ali Legal Skills v4 Tools

Ali Legal Skills v4 Tools is a public, model-agnostic library of executable `SKILL.md` legal workflow tools.

This release follows a strict tool-first design:

- Every skill has one specific legal job.
- Every skill has explicit trigger phrases.
- Every skill has command-style actions such as `list`, `add`, `edit`, `review`, `route`, `trace`, or `export`.
- Every skill uses YAML storage format.
- Every skill includes obligations analysis and routing.
- Every skill requires section references for findings.
- Every skill avoids silent mode inference. If intent is unclear, show the command menu.
- AI governance skills include role/tier per system and substantial-modification logic.
- Privacy and contract skills route obligations into impact assessments, DPA review, AI review, safety review, or human-review gates.

## Structure

```text
ali-legal-skills/
├── README.md
├── SKILLS_INDEX.md
├── LICENSE
├── NOTICE.md
├── SECURITY.md
├── CONTRIBUTING.md
├── docs/
├── skill-template/
├── commercial-legal/
├── privacy-legal/
├── ai-governance-legal/
├── law-student/
├── legal-research/
├── legal-safety-review/
└── skill-builder-hub/
```

## Legal boundary

These skills are workflow tools, not final legal advice. Outputs are drafts for qualified human review.

Generated: 2026-07-05
