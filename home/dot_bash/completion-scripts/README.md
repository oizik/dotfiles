# Completion Scripts

Directory exists to store completion scripts for various programs.

When a program is installed it should generate a completion script and output to this director with extension
`.bash-completion`.

```bash
poetry completions bash >> $HOME/.bash/completion-scripts/poetry.bash-completion
```

In `~/.bash_completion` a `for` loop sources all files in this directory which end with `.bash-completion`
