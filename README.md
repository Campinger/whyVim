# why.nvim is good config?
## It's a very bad config!! (pls don't use)
**Hi**, I just learn and setting up neovim





**Before install:**
  ⚡️ Requirements
**Neovim** >= **0.9.0** (needs to be built with LuaJIT)
**Git** >= 2.19.0 (for partial clones support)
**a Nerd Font**(v3.0 or greater) (optional, but needed to display some icons)
lazygit **(optional)**
a **C compiler** for nvim-treesitter. See here
for **telescope.nvim** (optional)
live grep: **ripgrep**
find files: **fd**
a terminal that support true color and undercurl:
kitty (Linux & Macos)
**wezterm** (Linux, Macos & Windows)
**alacritty** (Linux, Macos & Windows)
iterm2 (Macos)

#Okay, How to install this чудо-юдо?

Let's Start!

Windows:

  Use Powershell:
  `
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
`- We're backup current nvim config

`git clone https://github.com/Campinger/whyVim $env:LOCALAPPDATA\nvim` - install this configuration

`Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force` - remove **.git** folder

And Start nvim!


Linux:
Backup current nvim config - `mv ~/.config/nvim{,.bak}
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}`
install this configuration - `git clone https://github.com/Campinger/whyVim ~/.config/nvim`
remove **.git** folder - `rm -rf ~/.config/nvim/.git`

# Enjoy
Ok, we are install this config, what's next? Idk, lol

