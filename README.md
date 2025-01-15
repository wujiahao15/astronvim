# AstroNvim Template

**NOTE:** This is for AstroNvim v4+

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

### Make a backup of your current nvim and shared folder

- MacOS and Linux
  - ```shell
    mv ~/.config/nvim ~/.config/nvim.bak
    mv ~/.local/share/nvim ~/.local/share/nvim.bak
    mv ~/.local/state/nvim ~/.local/state/nvim.bak
    mv ~/.cache/nvim ~/.cache/nvim.bak
    ```
- Windows
  - ```powershell
    Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
    Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
    ```

### Clone the repository

- MacOS and Linux
  - ```shell
    git clone https://github.com/wujiahao15/astronvim.git ~/.config/nvim
    ```
- Windows
  - ```powershell
    git clone https://github.com/wujiahao15/astronvim.git $env:LOCALAPPDATA\nvim
    ```

## Start Neovim

```shell
nvim
```
