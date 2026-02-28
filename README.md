# <Project Name>

Template baseline repository for doctrine-aligned projects with shared governance, documentation, and CI maturity contracts.

## Status
- Stage: Draft | Active | Stable | Deprecated
- Owner: <Owner>
- License: <License Name>
- Visibility: Public | Private | Internal
- Reason: <Why this visibility level is correct>
- Promotion criteria to Public: <What must be true before public release>

## What This Project Is
- A canonical base template for governance and documentation conventions.
- A foundation for derived language/platform templates.

## Why It Exists
- Keep template maturity consistent across the template family.
- Provide stable defaults for docs, policy, and repository hygiene.

## Maturity Baseline
- Shared doctrine context (`AI_CONTEXT.md` + `docs/doctrine/*`).
- Core and advisory validation via `tools/validate-template.sh`.
- Core-gated CI with non-blocking advisory checks.

## Quickstart

### Prerequisites
- Bash shell
- `rg` (ripgrep)

### Run Validation
```bash
bash tools/validate-template.sh core
bash tools/validate-template.sh advisory
```

## Repository Layout
- `docs/` project documentation and doctrine snapshot
- `examples/` runnable examples (recommended)
- `tools/` helper scripts
- `.github/` issue templates and CI workflows

## Documentation
- [Overview](docs/overview.md)
- [Architecture](docs/architecture.md)
- [ADRs](docs/adr/)
- [Doctrine Snapshot](docs/doctrine/README.md)

## Validation
```bash
bash tools/validate-template.sh
```

## Contributing
See `CONTRIBUTING.md`.
