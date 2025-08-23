# nvim

A suckless NeoVim Config

Requires NeoVim 0.11.2 or later.

Copy and enjoy it with:

```bash
mkdir -p ~/.config/nvim
curl -fsSL https://raw.githubusercontent.com/pappasbrent/nvim/master/init.lua \
  -o ~/.config/nvim/init.lua
```

Update your `vim` and `editor` alternatives to point to `nvim` with:

```bash
sudo update-alternatives --install /usr/bin/vim vim /usr/local/bin/nvim 100
sudo update-alternatives --install /usr/bin/editor editor /usr/local/bin/nvim 100
```

## Uninstall

Remove neovim binary and installed files:

```bash
sudo rm /usr/local/bin/nvim
sudo rm -r /usr/local/share/nvim/
```

Delete configuration:

```bash
rm -rf ~/.config/nvim
```

Delete cache and data:

```bash
rm -rf ~/.local/share/nvim
rm -rf ~/.cache/nvim
```

Remove `nvim` from your `vim` and `editor` alternatives:

```bash
sudo update-alternatives --remove vim /usr/local/bin/nvim
sudo update-alternatives --remove editor /usr/local/bin/nvim
```
