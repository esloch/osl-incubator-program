# OSL Incubator

The OSL Incubator helps open source projects move from early-stage
proof of concept to sustainable, production-ready projects.

It is a **pre-incubation layer** designed to prepare projects for
ecosystem standards and potential progression into programs such as:

- CNCF
- Apache
- pyOpenSci
- rOpenSci

## Purpose

This repository is the source of truth for the incubator program:

- stage definitions
- review criteria
- application and evaluation flow
- contributor and reviewer guidance
- reusable templates

## Quick start

1. Read [docs/overview/vision.md](docs/overview/vision.md).
2. Read [docs/overview/lifecycle.md](docs/overview/lifecycle.md).
3. Use the checklist for the stage you are targeting.
4. Open an issue with the matching application template.

## Repository layout

| Path | Purpose |
| --- | --- |
| `README.md` | Program entry point and repository guide |
| `LICENSE` | Repository license |
| `CONTRIBUTING.md` | Contribution rules for this repository |
| `docs/overview/` | Vision and lifecycle documentation |
| `docs/stages/` | Stage descriptions for POC, incubation, and graduation |
| `docs/criteria/` | Checklists used during evaluation |
| `docs/applications/` | Application and review process docs |
| `docs/guides/` | Guidance for mentors, reviewers, and maintainers |
| `docs/templates/` | Baseline templates for projects, governance, and security |
| `.github/` | Issue and pull request templates |

## Lifecycle

The incubator uses a three-stage model:

1. [POC](docs/stages/poc.md)
2. [Incubation](docs/stages/incubation.md)
3. [Graduation](docs/stages/graduation.md)

Each stage has a matching checklist in `docs/criteria/` and a
corresponding application flow where appropriate.

See [docs/overview/lifecycle.md](docs/overview/lifecycle.md) for the
canonical lifecycle description.

## Apply

Open an issue using one of the templates:

- [POC application](https://github.com/esloch/osl-incubator-program/issues/new?template=apply-poc.md)
- [Incubation application](https://github.com/esloch/osl-incubator-program/issues/new?template=apply-incubation.md)
- [Graduation application](https://github.com/esloch/osl-incubator-program/issues/new?template=apply-graduation.md)

Promotion requests use:

- [Promote stage](https://github.com/esloch/osl-incubator-program/issues/new?template=promote-stage.md)

The application and evaluation process is documented in
[docs/applications/application-process.md](docs/applications/application-process.md)
and [docs/applications/evaluation-process.md](docs/applications/evaluation-process.md).

## Working with this repo

- Use concise, checklist-driven changes.
- Update the stage docs when criteria change.
- Keep the README as the top-level entry point, not a second copy of the lifecycle doc.
