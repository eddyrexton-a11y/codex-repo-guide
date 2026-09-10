# Codex Repo Guide

An installable Codex skill that explains unfamiliar repositories and gives users a verified, safe first-start plan.

## Use it

Install the `codex-repo-guide` folder as a Codex skill, then ask:

> Use `$codex-repo-guide` to explain this repository and tell me how to start safely.

The skill reads the repository's own documentation and configuration, distinguishes verified commands from inferences, identifies setup blockers, and suggests one small first task. It does not edit files or request secrets by default.

The skill analyzes repository files available in the current Codex workspace. A GitHub page open in a browser is not automatically the workspace; clone, download, or open the repository files before running it.

## Contents

- `SKILL.md` — the skill instructions
- `agents/openai.yaml` — Codex interface metadata
