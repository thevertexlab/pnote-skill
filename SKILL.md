---
name: promptie
description: Manage PromptNote prompts, notes, and snippets via CLI
allowed-tools: Bash(promptie *)
user-invocable: true
argument-hint: <command> [options]
---

# promptie - PromptNote CLI

Manage your prompts and notes from the terminal. Requires `npm install -g promptie` and authentication via `promptie auth token <your-pat>`.

## Available Commands

!`promptie --help`

## Quick Reference

**List & Search:**
- `promptie notes` - list all notes
- `promptie notes --tag "AI/art"` - filter by tag
- `promptie search "query"` - search notes and snippets

**Read & Copy:**
- `promptie notes get <id>` - get note with snippet
- `promptie snippet copy <id>` - copy to clipboard

**Create & Manage:**
- `promptie notes create "Title"` - create note
- `promptie snippet add <id>` - add snippet from stdin
- `promptie tags rename "old" "new"` - rename tag

**PIN Protection:**
For protected notes, set `PROMPTIE_PIN` env var or use `-p <pin>` flag.

## Execute

Run the user's command:

```bash
promptie $ARGUMENTS
```
