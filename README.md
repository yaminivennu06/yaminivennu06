Yamini Vennu

I build reproducible software for **agentic AI evaluation, coding-agent benchmarks, secure execution, and developer tooling**.

My portfolio focuses on the engineering details behind trustworthy agent evaluation: task and scenario design, deterministic scoring, protected evaluation boundaries, failure classification, reproducibility, and evidence-driven reporting.

## Featured portfolio

### [Agentic Coding RL Environment — Public Edition](https://github.com/yaminivennu06/agentic-coding-rl-environment-public)

Public-safe task validation and execution infrastructure with typed TOML configuration, unified-diff intake, SHA-256 manifests, Git worktrees, Docker policy construction, and trusted verification reports.

### [Agentic Code Review & Red-Team Benchmark — Public Edition](https://github.com/yaminivennu06/agentic-code-review-redteam-benchmark-public)

A structured review benchmark with finding schemas, severity and evidence quality, precision/recall/F1 scoring, false-positive measurement, and reproducible JSON reports.

### [Automated Coding Agent Evaluation & Scoring Platform — Public Edition](https://github.com/yaminivennu06/automated-coding-agent-evaluation-public)

An evaluation platform with agent adapters, concurrent orchestration, SQLite experiment storage, weighted metrics, confidence intervals, JSON exports, and leaderboard reporting.

## How the projects fit together

The public projects are complementary layers rather than a falsely claimed integrated deployment:

```text
Execution environment  ->  Review / red-team quality  ->  Experiment orchestration
       task safety              finding quality                 scoring and comparison
```

Protected benchmark data remains in separate private source repositories. The public editions use fresh Git histories and newly authored demonstration datasets.

## Technical focus

- Python package design with type hints and strict mypy
- Pytest, negative testing, and CI quality gates
- Docker execution policy and fail-closed boundaries
- Git patch validation, worktrees, and SHA-256 manifests
- Benchmark schemas, scenario authoring, and deterministic matching
- Precision, recall, F1, severity, evidence, regression, and weighted scoring
- SQLite experiment tracking, JSON reports, and leaderboard aggregation
- Mermaid architecture documentation and reproducible workflows

## Current focus

I am continuing to improve safe public/private benchmark separation, audited isolation runners, executable public task fixtures, and statistically stronger agent comparisons.

## Links

- [GitHub repositories](https://github.com/yaminivennu06?tab=repositories)
- [Public execution environment](https://github.com/yaminivennu06/agentic-coding-rl-environment-public)
- [Public review benchmark](https://github.com/yaminivennu06/agentic-code-review-redteam-benchmark-public)
- [Public evaluation platform](https://github.com/yaminivennu06/automated-coding-agent-evaluation-public)
