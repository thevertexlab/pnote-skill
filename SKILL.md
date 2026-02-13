---
name: promptie
description: Manage PromptNote prompts, notes, and snippets via CLI
allowed-tools: Bash(promtie *)
user-invocable: true
argument-hint: <command> [options]
---

# promtie - PromptNote CLI

Manage your prompts and notes from the terminal. Requires `npm install -g promtie` and authentication via `promtie auth token <your-pat>`.

## Available Commands

!`promtie --help`

## Quick Reference

**List & Search:**
- `promtie notes` - list all notes
- `promtie notes --tag "AI/art"` - filter by tag
- `promtie search "query"` - search notes and snippets

**Read & Copy:**
- `promtie notes get <id>` - get note with snippet
- `promtie snippet copy <id>` - copy to clipboard

**Create & Manage:**
- `promtie notes create "Title"` - create note
- `promtie snippet add <id>` - add snippet from stdin
- `promtie tags rename "old" "new"` - rename tag

**PIN Protection:**
For protected notes, set `PROMTIE_PIN` env var or use `-p <pin>` flag.

## Execute

Run the user's command:

```bash
promtie $ARGUMENTS
```
