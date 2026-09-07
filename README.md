# agent-plugins

Claude Code and Codex plugins by [@lodev09](https://github.com/lodev09).

## Add Marketplace

Claude Code:

```sh
claude plugin marketplace add lodev09/agent-plugins
```

Codex:

```sh
codex plugin marketplace add lodev09/agent-plugins
```

The repo includes native manifests for both clients:

- Claude Code: `.claude-plugin/marketplace.json`
- Codex: `.agents/plugins/marketplace.json`

## Available Plugins

### agent-sounds

Sound feedback for Claude Code and Codex — plays Warcraft-style voice lines on session events.

Claude Code:

```sh
claude plugin install sounds@lodev09
```

Codex:

```sh
codex plugin add sounds@lodev09
```
