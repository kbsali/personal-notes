# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is an Obsidian vault - a personal knowledge management system using markdown files. The vault is version-controlled with git via the obsidian-git plugin.

## Structure

- **00 - Inbox/** - Quick capture, to be filed later
- **01 - Projects/** - Active projects (Clapclap, Regadata, PRO/consulting)
- **02 - People/** - Person-centric notes
  - **Team/** - 1-1s with direct reports/colleagues
  - **Network/** - External contacts & networking
- **03 - Areas/** - Ongoing life areas (Perso, EDU, Asso-action, LPN)
- **04 - Resources/** - Reference material (Tech notes, Templates)
- **05 - Archive/** - Completed projects
- **.obsidian/** - Obsidian configuration (plugins, settings, workspace)

## Git Integration

The vault uses obsidian-git plugin with automatic backups:
- Commit message format: `vault backup: YYYY-MM-DD HH:mm:ss`
- Sync method: merge (pull before push enabled)

## Installed Plugins

- **obsidian-git** - Git version control
- **obsidian-outliner** - Enhanced list editing
- **templater-obsidian** - Note templates (configured at root `/`)

## Working with Notes

- All notes are markdown (`.md`) files
- Use wiki-style links: `[[Note Name]]`
- Avoid modifying `.obsidian/` configuration files unless specifically requested
