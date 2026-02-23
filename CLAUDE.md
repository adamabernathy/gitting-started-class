# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This is a teaching repository for the "Gitting Started" class — used to practice Git workflows (branching, pull requests, merging). There is no build system, test suite, or application code.

## Repository Structure

- `team.md` — The primary file students edit. Contains the list of class participants.
- `README.md` — Minimal project title only.
- `.gitignore` — Python-oriented gitignore (standard GitHub template).

## Workflow Convention

Changes to `team.md` are made via feature branches and pull requests, following this pattern observed in the commit history:

1. Create a branch named for the change (e.g., `issue-2-add-dallas-alice`)
2. Add the team member name as a list item in `team.md`
3. Open a PR into `main` with a descriptive commit message (e.g., `Add [Name] to team roster`)
