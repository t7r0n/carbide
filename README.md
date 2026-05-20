# Carbide

A typed, auditable generative UI runtime for agentic apps — every rendered component carries a capability scope, every re render is a stable diff, and every action is logged with a cryptographic intent trail.

![Carbide working dashboard](outputs/project_working.svg)

## Why it exists

Carson's whole pitch is "the UI is generative." But every artifact on usecarson.com — the prospect pane, the deck editor, the workflow builder — looks like a pre designed React surface that the LLM populates, not a layout the model invents per task. That's the gap between the marketing and the reality.

The project is intentionally built as a local replay harness instead of a slide. It creates fixtures, plants realistic failure modes, produces citation-locked evidence, and turns the result into a dashboard a reviewer can inspect without credentials or hosted services.

## What is inside

- Deterministic fixture generation for the company-specific risk surface.
- Strategy code in `src/carbide/strategy.py` with project-specific scoring and visual evidence.
- Citation-locked reports where every decision claim points to a generated evidence ID.
- Two regenerated visual artifacts: `outputs/project_working.svg` and `outputs/evidence_map.svg`.
- A portable demo pack with JSON, CSV, Markdown, HTML, SVG, benchmark, and test artifacts.

![Carbide evidence map](outputs/evidence_map.svg)

## Signals it measures

- `carson coverage`
- `whole risk`
- `pitch precision`
- `generative latency`

## Failure modes it plants

- carson drift
- whole gap
- pitch misroute
- generative blindspot

## Run it locally

```bash
uv sync
uv run carbide all
uv run pytest -q
uv run ruff check .
```

## Outputs worth opening

- `outputs/dashboard.html`
- `outputs/project_working.svg`
- `outputs/evidence_map.svg`
- `outputs/operator_brief.md`
- `outputs/decision_report.md`
- `outputs/strategy_model.json`
- `outputs/demo_pack.zip`

## Sources

- https://usecarson.com
- https://github.com/sidkmenon
- https://www.linkedin.com/in/sidkmenon/
- https://www.cedarpolicy.com/

## Boundary

Everything runs locally against synthetic fixtures. There are no credentials, no customer records, no outreach files, and no hosted API dependency.
