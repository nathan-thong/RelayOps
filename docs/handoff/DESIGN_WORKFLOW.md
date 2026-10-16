# RelayOps design workflow

The owner requested this workflow on 2026-10-16 as an addition to the v0.1 handoff. Application implementation and feasibility experiments still need separate authorization.

## Tooling decision

Use Impeccable as the primary design workflow. On 2026-10-16, the installed skill was upgraded from 4.3.1 to 4.6.0, and engine 0.1.15 passed its engine-probe check. Frontend quality and project readiness remain untested. Start a fresh agent session to load the updated skill reliably.

Impeccable covers product context, UX planning, design documentation, critique, audits, browser iteration, and deterministic design checks. The tooling review compared documented capabilities; it did not test competing tools on the same design task. Keep one primary workflow so workers follow the same design decisions.

Consult these references when the task calls for them:

- UI UX Pro Max has searchable guidance on charts, palettes, typography, UX, and implementation stacks.
- Emil Kowalski's Design Engineering covers component details and interactions.
- Taste Skill can help with art direction for the public case study or marketing pages.

These references are optional and have not been installed. Their inclusion does not authorize purchases. The project must not require additional subscriptions, paid image generation, paid fonts, or runtime API fees.

## Workflow and ownership

1. Complete architecture review before application implementation. Cover design risks and critical user journeys in the review brief's five documents. This workflow does not approve a visual design.
2. Before frontend work, use Impeccable's initialization flow to record the audience, operating context, goals, constraints, and verified product facts in `PRODUCT.md`. Use the handoff and accepted decisions as sources. Label assumptions, ask consequential questions, and describe planned features as plans.
3. Plan the path from service status to an incident, its timeline and evidence, and investigation. Once the recovery phase is authorized, plan approval, execution, and verified recovery too. Specify navigation, information hierarchy, actions, permissions, and failure states with realistic synthetic lab content.
4. Follow the installed skill's new-work flow. Record typography, spacing, semantic colors, density, component patterns, and interaction rules in `DESIGN.md`, along with any required sidecar files or surface briefs. Keep product facts separate from visual direction and identify proposals awaiting acceptance.
5. Build the agreed scope with the documented components and tokens. Read the relevant skill reference and craft-floor guidance before UI edits. Select a React component library separately, based on accessibility, maintainability, licensing, and project requirements.
6. Inspect the completed work on desktop and mobile in one pass. Collect defects, fix them together, and use at most one further visual check, following the installed workflow. If no automatic hook is active, run the mechanical detector on changed UI targets. Record commands and results. Check accessibility and usability separately from detector results.
7. Record tested viewports, keyboard checks, screenshots, automated checks, unresolved defects, and limitations. Update the design documentation when accepted decisions change. Completion needs working behavior and check results as well as screenshots.

The orchestrator keeps the work consistent and combines review findings. Give each worker a specific surface or component task and the same product and design documents. Coordinate edits to shared tokens and components before writing. Use additional tools or workers only within the owner's authorized scope.

## Surface priorities

Use Impeccable's Operate mode for the application. Operators need to scan service state, read evidence, and find the next action quickly. Choose a mode for the public case study separately, and keep its promotional styling out of the operational dashboard.

- Show severity, lifecycle status, data freshness, and provider or investigation state separately. Pair color with text or icons.
- Test incident tables, service lists, evidence excerpts, timestamps, and timelines with realistic data volumes and long values.
- Make collected observations, model hypotheses, uncertainty, and verified recovery distinguishable. Link evidence references to their observations.
- Approval flows must show the exact action, target, parameters, runbook version, expiry, and relevant effects. The server must authorize actions independently of UI state.
- Cover loading, empty, healthy, degraded, stale, offline, timeout, permission-denied, invalid-response, and partial-failure states wherever they apply. Show success only after verification.
- Support keyboard navigation, visible focus, accessible names, meaningful headings, adequate contrast, reduced motion, and responsive reading order. Target WCAG 2.2 AA where applicable and verify any compliance claims.
- Use synthetic screenshots or review and redact them before publication. Exclude real credentials, private logs, and unsupported portfolio claims.

## Ready for review

Submit a slice for review when its agreed user journeys work with real application state, failure states are understandable, shared patterns match the design system, and recorded browser and keyboard checks pass. Verify security-sensitive behavior through API or integration checks too. A functioning incident workflow needs real state changes; hardcoded numbers and decorative prototypes do not demonstrate it.

The project's spending, privacy, lab isolation, independent approval, and architecture review requirements still apply. Executing infrastructure commands, enabling paid providers, and publishing the application require separate authorization.

## Sources checked on 2026-10-16

- Impeccable: https://github.com/pbakaus/impeccable
- UI UX Pro Max: https://github.com/nextlevelbuilder/ui-ux-pro-max-skill
- Taste Skill: https://github.com/Leonxlnx/taste-skill
- Emil Kowalski's Design Engineering: https://github.com/emilkowalski/skills/blob/main/skills/emil-design-eng/SKILL.md

The linked projects document these capabilities. The recommendation is specific to RelayOps. Recheck tool versions and behavior before changing the setup.
