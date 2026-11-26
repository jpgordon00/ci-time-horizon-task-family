# How much does an AI time-horizon estimate change if one task family is omitted?

Measure the sensitivity of published 50% task-completion time horizons to the mixture of task families.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/time-horizon-task-family/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-time-horizon-task-family/pulls)

## Why this matters

METR publishes data and methods for estimating how long a human would take on tasks that agents can complete with a given probability. Closely related tasks can influence a fitted horizon together.

## What to contribute

Pin the public TH1.1 scored runs and analysis code. Reproduce the released baseline for two models, then refit after leaving out one task family at a time using the same fit settings.

## How reviewers check it

Publish task and run counts, baseline and per-family estimates, and any failed or poorly determined fits. Check the same code reproduces the baseline before interpreting changes.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/time-horizon-task-family
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/time-horizon-task-family/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-time-horizon-task-family/security/advisories/new) for security reports.

## Sources

- [METR time-horizon methods and data](<https://metr.org/time-horizons/>)
- [METR public analysis repository](<https://github.com/METR/eval-analysis-public>)
- [METR November capability update](<https://metr.org/blog/2026-11-20-q4-2026-capability-update/>)
