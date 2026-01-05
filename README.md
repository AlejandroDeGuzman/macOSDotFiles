# macOS Dotfiles

My personal macOS configuration files and setup.
<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/e3c3865d-6ee7-4fbf-b339-da677d7183ac" />
<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/cdd21b77-7357-43a2-9dbc-3c6b40f185a5" />
<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/573e5861-20e4-4905-9f1c-a1ce3c09ac46" />




## What's Included

- **Fish Shell** - Shell configuration with custom functions and plugins
- **Neovim** - LazyVim-based editor configuration
- **Aerospace** - Window manager configuration
- **iTerm2** - Terminal emulator settings
- **Sketchybar** - Menu bar customisation
- **Oh My Fish** - Fish shell framework

## Installation

1. Clone this repository:
```bash
git clone https://github.com/AlejandroDeGuzman/macOSDotFiles.git
cd macOSDotFiles
```

2. Create symlinks to your `.config` directory:
```bash
# Backup your existing configs first!
ln -s ~/path/to/macOSDotFiles/fish ~/.config/fish
ln -s ~/path/to/macOSDotFiles/nvim ~/.config/nvim
ln -s ~/path/to/macOSDotFiles/aerospace ~/.config/aerospace
ln -s ~/path/to/macOSDotFiles/sketchybar ~/.config/sketchybar
```

3. Install Fish plugins:
```bash
fisher update
```

4. Install Neovim plugins:
```bash
nvim
# LazyVim will auto-install plugins on first run
```

## Requirements

- macOS
- [Fish Shell](https://fishshell.com/)
- [Neovim](https://neovim.io/) (0.9.0+)
- [Fisher](https://github.com/jorgebucaran/fisher) (Fish plugin manager)
- [Aerospace](https://github.com/nikitabobko/AeroSpace) (Window manager)
- [Sketchybar](https://github.com/FelixKratz/SketchyBar) (Menu bar)

## License

Feel free to use and modify as needed.
