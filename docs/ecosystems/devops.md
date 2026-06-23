# DevOps / Infra Guidance

## Purpose

This page describes the baseline OSL expectations for DevOps and
infrastructure projects.

## Scope

Use it for tooling, deployment, and infrastructure projects that may
later be compared against CNCF-style expectations.

## OSL baseline

- reproducibility is documented
- deployment or operation steps are clear
- important behavior is observable
- security-relevant settings are visible
- the project can be reviewed without hidden infrastructure knowledge

## Delegated depth

CNCF-style programs can provide deeper validation for reproducibility,
security, observability, and operational maturity.

OSL should only set the baseline needed to evaluate stage readiness.

## Reviewer focus

- setup steps are repeatable
- the operational model is understandable
- logs, metrics, or other observability signals are described when they
  matter
- security and deployment assumptions are not hidden
