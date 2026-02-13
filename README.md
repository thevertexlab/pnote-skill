# promptie-skill

Claude Code skill for [PromptNote](https://promptnoteapp.com/) CLI.

## Installation

### 1. Install the CLI

```bash
npm install -g promptie
```

### 2. Authenticate

Get your Personal Access Token from [PromptNote Settings](https://promptnoteapp.com/settings), then:

```bash
promptie auth token pn_your_token_here
```

### 3. Use the Skill

In Claude Code, use `/promptie` to invoke:

```
/promptie notes
/promptie search "AI art"
/promptie snippet copy abc123
```

## What This Skill Does

This skill wraps the `promptie` CLI to let Claude help you:

- **List and search** your notes and snippets
- **Read and copy** prompt content to clipboard
- **Create and manage** notes, tags, and versions
- **Access PIN-protected** notes securely

## CLI Commands

| Command | Description |
|---------|-------------|
| `promptie notes` | List all notes |
| `promptie notes get <id>` | Get note with snippet |
| `promptie search <query>` | Search notes and snippets |
| `promptie snippet copy <id>` | Copy snippet to clipboard |
| `promptie tags` | List all tags |

See `promptie --help` for full documentation.

## Links

- [PromptNote App](https://promptnoteapp.com/)
- [Feedback & Bugs](https://iohpo.featurebase.app/?b=695f9152f13092ad189fb4de)

## License

MIT
