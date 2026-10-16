# RelayOps — Agent Design Workflow

Added by owner request on 2026-10-16. This supplements the v0.1 handoff; it does not authorize application implementation or feasibility spike execution.

## Tooling decision

Use **Impeccable as the primary agent design workflow**. The installed skill was upgraded from 4.3.1 to 4.6.0 on 2026-10-16; engine 0.1.15 passed its engine-probe check. This verifies tooling installation, not frontend quality or project readiness. A fresh agent session is required to discover the updated skill reliably.

Impeccable provides product context, UX planning, visual-system documentation, critique, audits, browser iteration, and deterministic design checks. Research found credible alternatives, but did not establish a universal quality winner through comparative output testing. Retain one primary workflow to keep agent decisions consistent.

Optional references, when a specific task benefits:

- UI UX Pro Max: searchable chart, palette, typography, UX, and stack guidance.
- Emil Kowalski's Design Engineering: focused component and interaction refinement.
- Taste Skill: art direction for the public case study or marketing surface.

These are optional references, not installed dependencies or permission to purchase services. No additional mandatory subscriptions, image generation charges, paid fonts, or runtime API fees may be introduced.

## Workflow and ownership

1. **Complete architecture review first.** Include design risks and critical user journeys in the review. Produce the review brief's five artifacts before application implementation. This addendum is a workflow contract, not an approved visual design.
2. **Establish product context before frontend work.** Use Impeccable's initialization flow to record audience, operating context, goals, constraints, and product truth in `PRODUCT.md`. Derive facts from the handoff and verified decisions. Label assumptions; ask only consequential questions. Do not describe planned features as implemented.
3. **Shape critical journeys before coding.** Plan service status → incident → timeline/evidence → investigation. Plan approval → execution → verified recovery only when that phase is authorized. Specify information hierarchy, navigation, actions, permissions, and failure states. Use realistic synthetic lab content.
4. **Record the visual system.** Follow the installed skill's new-work flow and persist typography, spacing, semantic colors, density, component patterns, and interaction rules in `DESIGN.md` and any sidecar/surface briefs the installed workflow requires. Keep product facts separate from visual direction. Design proposals remain proposals until accepted.
5. **Implement the accepted slice consistently.** Reuse documented components and tokens. Read the installed skill's relevant reference and craft-floor guidance before UI edits. Impeccable guides design; selection of a React component library is a separate engineering decision. Choose it against accessibility, maintainability, licensing, and actual requirements.
6. **Verify in bounded passes.** Build the complete authorized slice, inspect desktop and mobile together, collect defects, and fix them in one batch. Confirm with at most one additional visual verification round, following the installed workflow. Run the mechanical detector on changed UI targets if an automatic hook is unavailable. Record actual commands and outcomes; a detector pass does not prove accessibility or usability.
7. **Hand off evidence.** Record tested viewports, keyboard checks, screenshots, relevant automated checks, unresolved defects, and known limitations. Update visual documentation when accepted decisions change. Do not claim completion from screenshots alone.

The orchestrator owns consistency and review integration. Workers receive bounded surface/component tasks and the same product/design contracts. Coordinate shared token and component edits before writing. Additional tools or workers must remain within the owner's authorized scope.

## Surface priorities

The application uses Impeccable's **Operate** mode: fast scanning, clear hierarchy, predictable interactions, and readable evidence. Choose the public case study's mode separately; its promotional styling must not dictate the operational dashboard.

- Show severity, lifecycle status, data freshness, and provider/investigation state distinctly. Use text or icons alongside color.
- Give incident tables, service lists, evidence excerpts, timestamps, and timelines enough space to remain useful with realistic data volumes and long values.
- Keep deterministic observations, model hypotheses, uncertainty, and verified recovery visually distinguishable. Link evidence references to the observations they cite.
- Expose the exact action, target, parameters, runbook version, expiry, and relevant effects in approval flows. UI state never substitutes for server authorization.
- Design loading, empty, healthy, degraded, stale, offline, timeout, permission-denied, invalid-response, and partial-failure states when relevant to the slice. Avoid success styling before verification.
- Preserve keyboard navigation, visible focus, accessible names, meaningful headings, adequate contrast, reduced-motion preferences, and responsive reading order. Target WCAG 2.2 AA where applicable; verify rather than assert compliance.
- Use synthetic or reviewed/redacted screenshots. Never display real credentials, private logs, or unsupported portfolio claims.

## Frontend acceptance gate

A slice is ready for review when its authorized journeys work with real application state, its relevant failure states are understandable, shared patterns match the documented system, and the recorded browser/keyboard checks pass. Security-sensitive behavior also needs meaningful API/integration verification. Hardcoded dashboard numbers and decorative prototype flows do not count as functioning incident management.

This workflow does not override the project's spending, privacy, isolated-lab, independent-approval, or review-first constraints. It adds no permission to execute infrastructure commands, enable paid providers, or publish the application.

## Sources checked on 2026-10-16

- Impeccable: https://github.com/pbakaus/impeccable
- UI UX Pro Max: https://github.com/nextlevelbuilder/ui-ux-pro-max-skill
- Taste Skill: https://github.com/Leonxlnx/taste-skill
- Emil Kowalski's Design Engineering: https://github.com/emilkowalski/skills/blob/main/skills/emil-design-eng/SKILL.md

Capabilities above are documented by their maintainers; the recommendation is a project-specific judgment. Recheck tooling versions and behavior before later setup changes.
