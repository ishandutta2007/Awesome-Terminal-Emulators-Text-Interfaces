# Awesome-Terminal-Emulators-Text-Interfaces

# Top Terminal Emulators & Text Interfaces Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on GPU-Accelerated Terminal Emulators, Cross-Platform Shells, Text-Based User Interfaces (TUIs) & CLI Utilities*  
**Last updated: November 2026**

This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Terminal Emulators & Text Interfaces**. These tools provide ultra-low-latency GPU rendering, Kitty/Sixel inline graphics, split-pane workspace layouts, cross-platform SSH orchestration, and rich interactive CLI/TUI experiences.

**Examples** include Warp, Termius, iTerm2, Hyper, Alacritty, Kitty, Windows Terminal, Tabby, WezTerm, and Rio (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for Rust/Zig/C/Go terminal emulators, platform-native consoles, interactive CLI/TUI tools, and terminal graphics engines — ideal for developers, systems engineers, DevOps teams, and command-line power users.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Warp](https://warp.dev)**  
  Modern, Rust-based terminal emulator featuring integrated AI agents, block-based command grouping, collaborative Warp Drive notebooks, and team workflow sync.

- **[Termius](https://termius.com)**  
  Cross-platform SSH, Mosh, and SFTP terminal client offering end-to-end encrypted vault synchronization, shared team host groups, and mobile/desktop apps.

- **[SecureCRT (VanDyke Software)](https://vandyke.com)**  
  Commercial terminal emulator and SSH/Telnet client designed for enterprise network administration with session management, scripting, and FIPS-validated security.

- **[ZOC Terminal (EmTec)](https://emtec.com)**  
  Commercial SSH/Telnet terminal emulator for macOS and Windows supporting tabbed sessions, extensive terminal emulations (xterm, VT220, TN3270), and REXX scripting.

- **[Tabby Sync / Cloud Plugins](https://tabby.sh)**  
  Cloud-based configuration, profile, and SSH connection synchronization services extending the Tabby terminal emulator across multiple machines.

- **[Wave Terminal Cloud / Enterprise](https://waveterm.dev)**  
  AI-native open-core terminal emulator combining shell panes with inline web browsers, file previews, and cloud-assisted AI command blocks.


## Open-Source GitHub Projects

- **[Alacritty (`alacritty/alacritty`)](https://github.com)**  
  Cross-platform, OpenGL-accelerated terminal emulator written in Rust focused on extreme speed, minimal latency, and clean YAML/TOML configuration.

- **[Kitty (`kovidgoyal/kitty`)](https://github.com)**  
  Fast, feature-rich, GPU-based terminal emulator written in C and Python supporting programmable kittens, splits, tabs, ligatures, and the Kitty graphics protocol.

- **[WezTerm (`wez/wezterm`)](https://github.com)**  
  GPU-accelerated cross-platform terminal emulator and multiplexer written in Rust with Lua configuration, native SSH/TLS domains, and rich font ligature rendering.

- **[Windows Terminal (`microsoft/terminal`)](https://github.com)**  
  Modern, fast, open-source terminal application for Windows featuring DirectWrite/DirectX GPU text rendering, tabs, split panes, and custom profiles for PowerShell, WSL, and CMD.

- **[iTerm2 (`gnachman/iTerm2`)](https://github.com)**  
  Feature-packed macOS terminal emulator supporting split panes, hotkey drop-down windows, `tmux` integration, shell integration, triggers, and Python scripting.

- **[Ghostty (`ghostty-org/ghostty`)](https://github.com)**  
  Fast, native, cross-platform terminal emulator written in Zig using platform-native UI frameworks, GPU acceleration, and `libghostty` embeddable core libraries.

- **[Rio (`raphamorim/rio`)](https://github.com)**  
  Hardware-accelerated GPU terminal emulator written in Rust capable of running natively on desktop or in the browser via WebAssembly with built-in splits and retro CRT shaders.

- **[Tabby (`Eugeny/tabby`)](https://github.com)**  
  Highly configurable cross-platform terminal emulator, SSH client, and serial console built with TypeScript and web technologies with an extensive plugin ecosystem.

- **[Hyper (`vercel/hyper`)](https://github.com)**  
  Extensible terminal emulator built on HTML, CSS, and JavaScript/Electron offering split panes, custom keymaps, and thousands of community themes and plugins.

- **[Foot (`dnkl/foot`)](https://codeberg.org)**  
  Fast, lightweight, and minimalist Wayland-native terminal emulator written in C featuring server/daemon mode, Sixel graphics support, and low memory usage.

- **[Contour (`contour-terminal/contour`)](https://github.com)**  
  Modern, cross-platform, GPU-accelerated C++20 terminal emulator supporting VT320/xterm sequences, Sixel graphics, font ligatures, and runtime profile switching.

- **[Konsole (`KDE/konsole`)](https://github.com)**  
  Full-featured, open-source terminal emulator for the KDE desktop environment offering split views, bookmarkable SSH sessions, profile switching, and search highlighting.

- **[Tilix (`gnunn1/tilix`)](https://github.com)**  
  Tiling terminal emulator for Linux built with GTK3 allowing arbitrary horizontal and vertical pane splits, persistent layouts, and drop-down quake mode.

- **[Terminator (`gnome-terminator/terminator`)](https://github.com)**  
  Open-source Linux terminal emulator engineered for arranging multiple terminals in customizable grids with broadcast keystroke grouping.

- **[Extraterm (`sedwards2009/extraterm`)](https://github.com)**  
  Open-source terminal emulator introducing command output frames, inline image viewing, and deep shell integration for filtering and reusing previous command output.

- **[Cool Retro Term (`Swordfish90/cool-retro-term`)](https://github.com)**  
  GPU-accelerated terminal emulator built with QML and Qt that mimics the look, feel, phosphor glow, and scanlines of classic cathode-ray tube (CRT) monitors.

- **[Heretic (`p-e-w/heretic`)](https://github.com/p-e-w/heretic)**  
  Open-source Python CLI and interactive text interface tool for automated, training-free language model modification using directional ablation and Optuna TPE optimization.

- **[st — Simple Terminal (`suckless.org`)](https://suckless.org)**  
  Ultra-minimalist terminal emulator for X11 written in clean C by the suckless community, customized directly via source code patches and `config.h`.

- **[xterm.js (`xtermjs/xterm.js`)](https://github.com)**  
  High-performance TypeScript terminal front-end component used by VS Code, Hyper, and cloud IDEs to render full POSIX terminals inside web browsers.

### Additional Strong Open-Source Options

- **[Terminal Multiplexers & Window Managers](https://github.com)** like **tmux**, **Zellij**, **TUIOS (`Gaurav-Gosain/tuios`)**, and **cmux (`manaflow-ai/cmux`)** for persistent sessions and modal pane orchestration.
- **[Terminal Graphics & Media Viewers](https://github.com)** including **chafa (`hpjansson/chafa`)**, **viu**, **timg**, and **ueberzugpp** for rendering images and video inside terminal emulators.
- **[Shell Prompts & Line Editors](https://github.com)** such as **Starship**, **Oh My Posh**, **Powerlevel10k**, **Atuin**, and **Ble.sh** for syntax-highlighted, context-aware prompts.
- **[TUI Frameworks & Libraries](https://github.com)** like **Ratatui (Rust)**, **Bubble Tea (Go)**, **Textual (Python)**, and **Ink (React/Node.js)** for building rich text-based interfaces.
- Many community **Nerd Fonts** (JetBrainsMono, FiraCode, Iosevka, Hack) and **Base16 / Catppuccin Terminal Color Schemes**.

**Frameworks for building custom systems**: Combine **Ghostty**, **WezTerm**, or **Alacritty** for GPU-accelerated rendering, **tmux** or **Zellij** for session multiplexing, and **Starship + Atuin** for a fast, modern command-line environment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Terminal emulators execute shell commands and process escape sequences directly on your host OS; keep terminal binaries updated to mitigate ANSI/OSC escape-sequence injection vulnerabilities.
- When using cloud-synced terminal configurations or SSH vaults, enable end-to-end encryption and strong multi-factor authentication.

---

**Made for terminal enthusiasts, systems programmers, DevOps engineers, and open-source builders.**  
Let's make terminal emulators and text interfaces faster, sharper, and more open.
