# Changelog

All notable changes to this agent are tracked here.

## [1.1.0] - 2026-11-12

- Add a clear-communication rule to the Claude Code and Codex definitions. User-facing explanations use simple English, or the language the user requests, with short sentences and familiar words. Explain terms and acronyms on first use. Describe what a change does so a non-programmer can follow it, and keep exact file paths, names, evidence, risks and technical detail for developers.
- Name the orchestrator MyDevFactory in those definitions, the README, and this snapshot. The analyst role, file formats, and `.engineering-workflow.json` mapping are unchanged. The v1.0.0 snapshot still says Engineering Judgment.

## [1.0.0] - 2026-11-04

- Initial public, platform-specific Claude Code + Codex distribution.
- MIT license and step-by-step project/personal installation instructions.
- Version declarations and immutable versioned release snapshots.
- Derived from the software-architect agent: keeps its evidence-first, simplest-design decision rules and adds requirements work (explore before asking, questions with recommended answers, PRD, vertical slices with contracts, glossary terms, sparing ADRs, read-only data checks) and an Engineering Judgment analyst mode.
