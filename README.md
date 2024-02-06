# tmux_config

My custom Catppuccin-themed Tmux config, designed to pair nicely with my [Neovim config](https://github.com/JackDerksen/viis-lazyvim). Inspired by Dreams Of Code and DevOps Toolbox.
Requires tpm for packages, and a nerd font if you want icons. There are two styles in the tmux.conf file, un-comment whichever you prefer!

The leader key is set to `ctrl + space`, the only correct option.

To install on Linux, place tmux.conf in ~/.config/tmux/ , then install packages via tpm with `<leader> + i`.

### Keymaps:
- `<leader> + r` to source/refresh the Tmux config file
- `<leader> + -` to split window horizontally
- `<leader> + |` to split window vertically
- Vim style highlighting
