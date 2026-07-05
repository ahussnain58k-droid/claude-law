# YAML Storage Standard

Every skill stores workflow state in YAML.

Rules:

- Use `unknown` instead of guessing.
- Preserve keys unless schema change is requested.
- Use `review_required: true` for unresolved legal risk.
- Keep privileged notes separate from business summaries.
