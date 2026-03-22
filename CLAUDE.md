# CLAUDE.md

This file provides guidance to Claude Code when working with code in this repository.

## Git Workflow

- Always create a feature branch before making changes — never commit directly to master
- Branch naming: `feature/<short-description>` or `fix/<short-description>`
- Make code changes without touching git unless explicitly asked
- Use the workflow commands below to manage the git lifecycle

## Workflow Commands

| Command | What it does |
|---|---|
| `/status` | Show current branch, uncommitted changes, and open PRs |
| `/commit` | Stage and commit locally only (rewind checkpoint) |
| `/ship` | Branch → commit → push → open PR → poll CI results |
| `/merge` | Verify CI is green, then merge and sync master |

## General Rules

- Never push directly to master
- Never commit `.env` files or secrets
- Never skip CI checks before merging
- Keep commit messages descriptive — explain what changed and why

## Project Setup

<!-- TODO: Add project-specific setup instructions here -->

## Architecture

<!-- TODO: Add project-specific architecture notes here -->
