# Creates Solarized and Dracula themes fot tmux

A tmux Solarized and Dracula themes.

### Install with [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

Add plugin to the list of TPM plugins in `.tmux.conf`:

    set -g @plugin 'oriolgg/tmux-themes'

Hit `prefix + I` to fetch the plugin and source it. The plugin should now be working.

3 themes are provided so you can pick and choose via `.tmux.conf` option:

- `set -g @colors-oriolgg 'oriolgg-solarized-light'`
- `set -g @colors-oriolgg 'oriolgg-solarized-dark'`
- `set -g @colors-oriolgg 'oriolgg-dracula'`
