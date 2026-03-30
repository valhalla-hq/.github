# Valhalla HQ

Valhalla HQ is the operating home for the private system-of-record repositories behind the Valhalla and Valkyrie ecosystem.

We use this organization to coordinate AI systems, infrastructure, automation, agent workflows, and operational documentation across a small but growing repo family.

## What lives here

- Infrastructure and homelab operations for the Proxmox-based environment
- Control-plane contracts and operator-safe automation boundaries
- Reusable agents, skills, and MCP building blocks
- Data-platform architecture, runbooks, and policy surfaces
- Runtime and product repositories for the Valkyrie system

## Working style

- Private-by-default for infrastructure, operations, and control-plane truth
- Documentation and runbooks are treated as first-class assets
- Automation is preferred when it improves safety and repeatability
- Cross-repo changes are handled deliberately rather than ad hoc

## Core repo families

- `proxmox-homelab-ops`: infrastructure, diagnostics, runbooks, and operational procedures
- `valhalla-control`: planner contracts, control-plane guardrails, and orchestration boundaries
- `valkyrie-agents`: reusable skills, subagents, and MCP building blocks
- `valkyrie-data-platform`: data-platform architecture and operating model
- `valkyrie` and `valkyrie-runtime`: planning and runtime/product surfaces

## Public footprint

Most repositories in this organization are intentionally private because they contain infrastructure, operational procedures, or internal system design.

Public-facing artifacts are published selectively when they are ready to stand on their own.
