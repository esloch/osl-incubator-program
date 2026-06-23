# OSL Incubator

OSL Incubator is a lightweight program for moving open source projects
from an experimental starting point to a stable, maintainable, and
adoptable project.

It is a pre-incubation layer that prepares projects for external
ecosystem expectations without copying those ecosystems' rules into this
repository.

## Purpose

This repository is the source of truth for:

- stage definitions
- checklist-based review criteria
- the application and promotion workflow
- role definitions for authors, reviewers, and editors
- ecosystem guidance for Python, R, and DevOps projects
- reusable templates and issue forms

## Start here

1. Read [docs/overview/vision.md](docs/overview/vision.md).
2. Read [docs/overview/lifecycle.md](docs/overview/lifecycle.md).
3. Read [docs/workflows/global-workflow.md](docs/workflows/global-workflow.md).
4. Pick the checklist for your target stage in `docs/criteria/`.
5. Open the matching issue template from `.github/ISSUE_TEMPLATE/`.

## Canonical model

The program uses three active stages:

1. [POC](docs/stages/poc.md) - sandbox / experimental
2. [Incubation](docs/stages/incubation.md) - stabilization
3. [Graduation](docs/stages/graduation.md) - adoption and maturity

An archive path may be added later for inactive projects, but it is not
an active stage today.

## Roles

- [Authors](docs/guides/authors.md) build the project and respond to feedback.
- [Reviewers](docs/guides/reviewers.md) validate evidence against the checklist.
- [Editors](docs/guides/editors.md) maintain criteria and approve transitions.

## Ecosystems

OSL defines the baseline. External ecosystems define deeper validation.

- [Python guidance](docs/ecosystems/python.md)
- [R guidance](docs/ecosystems/r.md)
- [DevOps / Infra guidance](docs/ecosystems/devops.md)

## Apply

Open an issue using one of the templates:

- [POC application](https://github.com/esloch/osl-incubator-program/issues/new?template=apply-poc.md)
- [Incubation application](https://github.com/esloch/osl-incubator-program/issues/new?template=apply-incubation.md)
- [Graduation application](https://github.com/esloch/osl-incubator-program/issues/new?template=apply-graduation.md)
- [Promote stage](https://github.com/esloch/osl-incubator-program/issues/new?template=promote-stage.md)

## Repository layout

| Path | Purpose |
| --- | --- |
| `README.md` | Program entry point and navigation |
| `CONTRIBUTING.md` | Repository contribution rules |
| `docs/overview/` | Vision, lifecycle, and website mapping |
| `docs/workflows/` | Canonical application and due-diligence flow |
| `docs/stages/` | Stage definitions |
| `docs/criteria/` | Stage checklists |
| `docs/guides/` | Role-based guidance |
| `docs/ecosystems/` | Ecosystem-specific guidance |
| `docs/templates/` | Baseline templates |
| `.github/ISSUE_TEMPLATE/` | Application and promotion issue forms |

## Working in this repo

- Keep changes checklist-driven and easy to review.
- Update the linked stage, workflow, and criteria docs together.
- Do not add policy that is not already supported by the repo or the
  referenced ecosystem guidance.
