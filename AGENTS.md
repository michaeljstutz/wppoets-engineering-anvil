# WPPoets Engineering - Agent Instructions

## Overview

This is the anvil (AI workspace) for the WPPoets engineering/infrastructure repo. The actual source code lives in `bench/` which is a separate git repo (`wppoets/wppoets-engineering`).

## Structure

- `anvil/` - AI artifacts, research notes, architectural decisions (tracked here)
- `bench/` - Rust services, infrastructure code, internal tooling (separate git repo, excluded from this repo)

## Working with This Project

- When making code changes, work in `bench/`
- When saving research, decisions, or AI artifacts, save to `anvil/`
- This repo is private - infrastructure code, API services, and licensing logic live here
- Rust services are not WordPress derivatives and are not GPL-bound
