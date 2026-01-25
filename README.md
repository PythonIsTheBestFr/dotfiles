
# 🚀 Modern Tmux Configuration

A high-performance Tmux environment featuring **Ctrl + Space** ($C-Space$) as the primary prefix, "prefix-less" Alt navigation, and the Catppuccin theme. 

Designed for speed, this setup eliminates the clunky `Ctrl + B` default and adds sane defaults inspired by `tmux-sensible`.

---

## 🛠 Installation

### 1. Prerequisites
Ensure you have `tmux` (version 3.1 or higher recommended) and `git` installed.

### 2. Clone the Plugin Manager (TPM)
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

```

### 3. Deploy Configuration

Create the directory and place the config file:

```bash
mkdir -p ~/.config/tmux
# Place your config file at ~/.config/tmux/tmux.conf

```

### 4. Install Plugins

1. Open Tmux: `tmux`
2. Press `Ctrl + Space` then `Shift + i` (Capital I) to install the theme and plugins.
3. Press `Ctrl + Space` then `r` to reload the config.

---

## ⌨️ Keybindings & Usage

### ⚡ Prefix-less Navigation

No prefix required! Just hold **Alt (Meta)** for instant movement.

| Action | Shortcut |
| --- | --- |
| **Switch Panes** | `Alt` + `W A S D` |
| **Kill Current Pane** | `Alt` + `x` |
| **Open Pane** | `Alt` + `v` |
| **Next Window (Tab)** | `Alt` + `c` |
| **Previous Window (Tab)** | `Alt` + `z` |
| **Toggle Mouse Mode** | `Alt` + `m` |


### 🛠 Management (Prefix: `Ctrl + Space`)

Press `Ctrl + Space`, release, then press the following:

| Action | Key |
| --- | --- |
| **Split Vertical** | `\` |
| **Split Horizontal** | `-` |
| **New Window** | `v` |
| **Kill Window** | `x` |
| **Reload Config** | `r` |
| **Save Session** | `s` |
| **Restore Session** | `r` |


---

## ✨ Features

* **Zero Escape-Time:** Optimized for Vim/Neovim users (no mode-switching lag).
* **Auto-Renumbering:** Windows automatically reorder themselves when one is closed.
* **Persistence:** Uses `tmux-resurrect` to keep your workspace alive after a reboot.
* **Modern UI:** Powered by the Catppuccin Mocha theme for a clean, readable interface.

---

## 📝 Configuration Note

The configuration file is located at `~/.config/tmux/tmux.conf`. If you are using an older version of Tmux (< 3.1), you may need to move the file to `~/.tmux.conf`.
