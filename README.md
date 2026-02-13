# promtie-skill

Claude Code skill for [PromptNote](https://promptnoteapp.com/) CLI.

## Installation

### 1. Install the CLI

```bash
npm install -g promtie
```

### 2. Authenticate

Get your Personal Access Token from [PromptNote Settings](https://promptnoteapp.com/settings), then:

```bash
promtie auth token pn_your_token_here
```

### 3. Use the Skill

In Claude Code, use `/promptie` to invoke:

```
/promptie notes
/promptie search "AI art"
/promptie snippet copy abc123
```

## What This Skill Does

This skill wraps the `promtie` CLI to let Claude help you:

- **List and search** your notes and snippets
- **Read and copy** prompt content to clipboard
- **Create and manage** notes, tags, and versions
- **Access PIN-protected** notes securely

## CLI Commands

| Command | Description |
|---------|-------------|
| `promtie notes` | List all notes |
| `promtie notes get <id>` | Get note with snippet |
| `promtie search <query>` | Search notes and snippets |
| `promtie snippet copy <id>` | Copy snippet to clipboard |
| `promtie tags` | List all tags |

See `promtie --help` for full documentation.

## Links

- [PromptNote App](https://promptnoteapp.com/)
- [Feedback & Bugs](https://iohpo.featurebase.app/?b=695f9152f13092ad189fb4de)

## License

MIT
