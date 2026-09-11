# Tmux Configuration

![Made with Tmux](https://img.shields.io/badge/Made%20with-Tmux-1BB91F?logo=tmux&logoColor=white)
![Plugin Manager: TPM](https://img.shields.io/badge/Plugin%20Manager-TPM-4C91F0)
![Theme: Catppuccin](https://img.shields.io/badge/Theme-Catppuccin-FFC0CB)
![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)
![Config only](https://img.shields.io/badge/Configuration-Personal-informational)

---

This repository contains my personal configuration for [Tmux](https://github.com/tmux/tmux), a terminal multiplexer that allows efficient window, pane, and session management from the command line.

The configuration is visually themed with [Catppuccin](https://github.com/catppuccin/tmux) and powered by the [Tmux Plugin Manager (TPM)](https://github.com/tmux-plugins/tpm).

## 📸 Preview

> Replace this with your screenshot or terminal cast:

![Tmux Screenshot](./screenshot.png)

## 🎯 Purpose

This setup is tailored for daily terminal use with a clean UI, sensible keybindings, and plugin support.  
It is shared publicly for inspiration — feel free to **fork** and **adapt** it to your own needs!

> **Note:** This is a personal configuration. Contributions are not accepted.

---

## 💾 Installation

### 1. Install Tmux

#### macOS

```bash
brew install tmux
```

#### Debian/Ubuntu

```bash
sudo apt install tmux
```

#### Arch Linux

```bash
sudo pacman -S tmux
```

### 2. Clone this configuration

```bash
git clone https://github.com/MikePapaSierra/tmux ~/.config/tmux
```

### 3. Link the configuration

Symlink `.tmux.conf`:

```bash
ln -s ~/.config/tmux/tmux.conf ~/.tmux.conf
```

Or directly copy it:

```bash
cp ~/.config/tmux/tmux.conf ~/.tmux.conf
```

### 4. Install TPM (Tmux Plugin Manager)

```bash
git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
```

### 5. Install plugins

Start Tmux, then press:

```text
Prefix (Ctrl-a in this config) + I
```

This installs the remaining plugins via TPM.

---

## 🧱 Structure

- `tmux.conf` — main configuration file
- `.config/tmux/` — repo location (if cloned this way)
- Uses TPM to manage plugins in `~/.config/tmux/plugins/`
- Includes the [Catppuccin](https://github.com/catppuccin/tmux) theme via TPM

---

## ⌨️ Keybindings

The prefix is `Ctrl-a`. Pane navigation follows Vim keys: `Prefix h`, `j`,
`k`, and `l` focus the left, down, up, and right pane.

| Action | Binding |
| --- | --- |
| New window | `Prefix c` |
| Split into stacked panes | `Prefix -` or `Prefix a` |
| Split into side-by-side panes | `Prefix \|` or `Prefix v` |
| Last active pane | `Prefix ;` |
| Copy mode | `Prefix [` |
| Zoom/unzoom pane | `Prefix z` |

`Prefix a` and `Prefix v` are base-layer aliases for the Corne split
keyboard. The original symbol-layer split keys remain available, so the same
configuration is comfortable on a conventional laptop keyboard.

---

## 🔧 Dependencies

- [Tmux](https://github.com/tmux/tmux) — required
- [TPM](https://github.com/tmux-plugins/tpm) — required for plugin management
- [Catppuccin Tmux Theme](https://github.com/catppuccin/tmux) — installed via TPM
- TPM-managed plugins are installed locally in `~/.config/tmux/plugins/` and are not tracked by this repository

---

## 📎 License

This project is shared under the [MIT License](LICENSE), but primarily for reference. Fork freely!
