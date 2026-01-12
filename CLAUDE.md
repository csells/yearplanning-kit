# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Year Planning Kit - a Claude Code command that guides users through a structured annual planning ceremony. It's a methodology/prompt package, not traditional code.

## Structure

- `.claude/commands/yearplanning.md` - The main planning ceremony command (invoked via `/yearplanning`)
- `year-[YYYY]-planning/` - Working directory created during planning sessions containing:
  - `00-personal-context.md` through `06-final-plan.md` - Phase outputs
  - `07-session-reflection.md` - Optional reflection notes

## Usage

Run `/yearplanning` to start the annual planning ceremony. The command uses YAML frontmatter for tool permissions (AskUserQuestion, Read, Write, Edit, Glob, Bash, TodoWrite).

## Planning Phases

1. Context Gathering - Review previous year
2. Capacity Mapping - Calculate realistic working days
3. Open-Mind Intentions - Surface authentic desires via interview
4. Big Rocks Definition - Define 3-4 major goals with slogans/outcomes
5. Board Simulation - Stress-test plan through 6 virtual advisors (REQUIRED)
6. Final Commit - Compile final plan
7. Session Reflection - Optional process improvement
8. Next Steps - Quarterly planning handoff

## Key Concepts

- **Big Rocks**: Outcome-based (not project-specific) goals with slogan + outcome + value statement
- **Board Members**: The Architect (strategy), Guardian (wellbeing), Catalyst (growth), Realist (finance), Sage (inner wisdom), Coordinator (chairman)
- **Through-Line**: Organizing principle that unifies all rocks (emerges from Board simulation)
- **Destination Postcard**: Year-end visualization exercise that becomes mission foundation
