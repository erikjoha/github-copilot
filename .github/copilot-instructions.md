# Repository instructions for GitHub Copilot

This repository is my central GitHub Copilot agent repository.

## Purpose

Use this repository to define, improve, and document reusable GitHub Copilot agents, prompts, workflows, and conventions.

The main goals are:

- Create specialized Copilot agents for different work types.
- Keep reusable prompts and instructions version controlled.
- Standardize how Copilot should help with coding, documentation, data analysis, Power BI, Microsoft Fabric, and repository maintenance.
- Prefer clear plans before code changes.
- Prefer small, reviewable pull requests.

## General behavior

When working in this repository:

- First understand the requested task.
- Ask for clarification only when required.
- Prefer a short plan before making changes.
- Keep changes minimal and focused.
- Do not rewrite unrelated files.
- Use Markdown for agent and prompt files.
- Explain assumptions in pull request summaries.
- Include validation steps when relevant.

## File conventions

Repository-level Copilot instructions live in:

```text
.github/copilot-instructions.md
