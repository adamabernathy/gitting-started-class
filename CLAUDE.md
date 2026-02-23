# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This is a teaching repository for the "Gitting Started" class — used to practice Git workflows (branching, pull requests, merging). There is no build system, test suite, or application code.

## Repository Structure

- `team.md` — The primary file students edit. Contains the list of class participants.
- `README.md` — Minimal project title only.
- `.gitignore` — Python-oriented gitignore (standard GitHub template).

## GitHub Issues Workflow

When working on a GitHub issue:

1. **Create a branch** named `Issue-N` where `N` is the issue number before starting any work.

   ```sh
   git checkout -b Issue-N
   ```

2. **Work on the issue** on that branch.

3. **Tag the issue** at the bottom of every commit message related to the issue:

   ```sh
   Closes #N
   ```

   Example commit message:

   ```sh
   Fix license expiration validation logic

   Closes #42
   ```
