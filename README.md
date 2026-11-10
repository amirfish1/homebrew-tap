# homebrew-tap

Homebrew tap for [Claude Command Center (CCC)](https://github.com/amirfish1/claude-command-center): it puts coding agents on call for your product.

## Install

```bash
brew install amirfish1/tap/ccc
```

Then either:

```bash
ccc                              # foreground
brew services start ccc          # brew-managed background
ccc --install-service            # CCC's own launchd agent
```

Open <http://localhost:8090>.

Already tapped `amirfish1/ccc` before the rename? It keeps working; GitHub
redirects the old repository.

## License

[MIT](LICENSE)
