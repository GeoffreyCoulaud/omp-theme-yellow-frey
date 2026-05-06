# yellow-frey
A yellow theme for [Oh My Posh](https://ohmyposh.dev) based on [emodipt-extend](https://ohmyposh.dev/docs/themes#emodipt-extend)

## Zsh install

![A screen capture of the prompt](shell-prompt.png)

1. Install Oh My Posh following the official instructions 
2. Add the following line to your `.zshrc`, replacing the default Oh My Posh init

```sh
eval "$(oh-my-posh init zsh --config https://github.com/GeoffreyCoulaud/omp-theme-yellow-frey/raw/main/yellow-frey.omp.json)"
```

3. Close your shell and re-open it

## Claude Code statusline install

![A screen capture of the Claude Code statusline](claude-status-line.png)

1. Install Oh My Posh following the official instructions
2. Set the `statusLine.command` in your `~/.claude/settings.json` (or project-level `.claude/settings.json`)

```json
{
  "statusLine": {
    "type": "command",
    "command": "oh-my-posh claude --config https://github.com/GeoffreyCoulaud/omp-theme-yellow-frey/raw/main/yellow-frey-claude.omp.json",
    "padding": 0
  }
}
```

3. That's it! The statusline updates live in Claude Code 🎉

## Helpful links

- [Box drawing characters](https://en.wikipedia.org/wiki/Box-drawing_characters)
- [Nerd fonts cheatsheet](https://www.nerdfonts.com/cheat-sheet)
