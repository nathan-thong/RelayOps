# RelayOps

RelayOps is a planned incident response lab that runs locally. The goal is to detect failures in test services, collect evidence, and support recovery after human approval. It is an engineering portfolio project.

## Current status

The project is in planning and architecture review. This repository contains documentation; there is no working application, deployed infrastructure, or evaluation results yet.

The first milestone is to stop an isolated test service, detect the outage, and save an incident that survives a restart. AI investigation using collected evidence and recovery after human approval come later.

## Constraints

- Run on existing hardware without mandatory paid services.
- Limit faults and recovery actions to disposable lab assets. Leave the workstation and home network alone.
- Keep detection and incident management usable with AI disabled.
- Require independent policy checks and explicit human approval for recovery actions.
- Complete architecture review and agree on a specific scope before writing application code.

## Design workflow

Use Impeccable to plan and check the interface. See [the design workflow](docs/handoff/DESIGN_WORKFLOW.md).

## Project tracking

Track work in this repository's GitHub Issues. Agent workflow configuration is still being set up.
