# Ryan MacLean

Developer advocacy, observability, agent systems, and lower-level systems research.

## Current projects

- **[bop](https://github.com/ryanmaclean/bop)** — filesystem-native work/run identity and agent orchestration
- **[smolFire](https://github.com/ryanmaclean/smolfire)** — tiny BSD microVM/runtime and temporal-storage research
- **[moth](https://github.com/ryanmaclean/moth)** — small reusable agent execution harness
- **[genoa](https://github.com/ryanmaclean/genoa)** — reproducible image/artifact build, deployment, verification, and receipts
- **[skills](https://github.com/ryanmaclean/skills)** — shared agent skills, policy, evaluations, project registry, RFCs, and benchmark schemas
- **[vibecode-webgui](https://github.com/ryanmaclean/vibecode-webgui)** — user-facing IDE/control surface

Experimental/control work includes **agent-jail**, **Gas Town**, **Tundra**, and **autoresearch**.

## Design direction

A recurring rule across the active projects:

> Prefer the lowest layer that can own a primitive once.

That means avoiding duplicate canonical state across orchestration, filesystems, queues, databases, telemetry, and lineage. BOP owns work identity; Moth executes; smolFire supplies the runtime; Genoa builds and attests artifacts; filesystem-native history carries durable versions; Datadog observes; OpenLineage is a projection.

The shared cross-project registry and terminology live in [ryanmaclean/skills](https://github.com/ryanmaclean/skills).

## Elsewhere

- [ryanmaclean.com](https://ryanmaclean.com)
- [LinkedIn](https://linkedin.com/in/ryanmaclean)
- [GitHub](https://github.com/ryanmaclean)
