# Codex Ability Demo

A curated repository that demonstrates Codex capabilities through focused, runnable examples.

## Goals
- Showcase Codex workflows: specification → implementation → tests → documentation.
- Provide small, independent demos that are easy to understand and run.
- Offer a clear structure for extension and evaluation.

## Quick Start
```bash
./scripts/setup.sh
./scripts/run_all.sh
```

## Demos
| Demo | Focus | Path |
| --- | --- | --- |
| CLI Tool | Spec → code → tests | `demos/01-cli-tool` |
| Web UI | UI generation + styling | `demos/02-web-ui` |
| Data Pipeline | ETL + validation | `demos/03-data-pipeline` |
| Refactor | Cleanup + tests | `demos/04-refactor` |

See `docs/demos.md` for detailed instructions.

## Repository Map
- `docs/` — documentation and walkthroughs.
- `demos/` — self-contained demo modules.
- `scripts/` — setup and orchestration scripts.
- `tests/` — shared or cross-demo tests.

## License
MIT
