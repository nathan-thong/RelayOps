# RelayOps agent instructions

RelayOps is in planning and architecture review. Read README.md for current status. Complete the architecture review before implementing an owner-authorized slice; report proposed features and measured results separately.

## Working boundaries

- Keep mandatory additional spending at zero. Paid integrations require explicit owner approval.
- Limit fault injection and recovery actions to designated disposable lab assets. Do not administer the workstation or home network, scan networks, or expose privileged services publicly.
- Keep detection and incident management usable without AI. Model tools must be bounded and read-only; recovery needs independent policy checks and explicit human approval of the exact action and target.
- Keep secrets and private logs out of the repository. Use synthetic or reviewed, redacted examples.
- For each task, record its scope, acceptance criteria, actual checks and results, and unresolved risks. Keep edits small and reviewable.

## Design and copy

Before frontend planning or UI changes, read docs/handoff/DESIGN_WORKFLOW.md and use the installed Impeccable skill. Use Humanizer when editing public prose, preserving technical facts, commands, and links.

## Agent skills

### Issue tracker

Track specs and tickets in nathan-thong/RelayOps GitHub Issues. Read docs/agents/issue-tracker.md before tracker operations.

### Triage labels

Use bug and enhancement as category labels. Read docs/agents/triage-labels.md before triage; the owner chose a simpler workflow without state labels.

### Domain docs

Use a single root GLOSSARY.md and docs/adr/. Read docs/agents/domain.md before exploring domain terms or making architecture decisions.
