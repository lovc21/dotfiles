# Dotfiles 📂

![Update Submodules](https://github.com/lovc21/dotfiles/actions/workflows/update-submodules.yml/badge.svg)

My dotfiles configuration for managing multiple machines with different operating systems and use cases.

## Machines 💻

| Status | Name | OS | Version | Hardware |
| --- | --- | --- | --- | --- |
| 1️⃣  Main | [bine](https://github.com/lovc21/dotfiles-bine) | [NixOS](https://nixos.org/) | 25.11 | [Framework Laptop 13](https://frame.work/si/en/laptop13) |
| 2️⃣  Backup | [razor](https://github.com/lovc21/dotfiles-razor) | [Ubuntu](https://ubuntu.com/) | 24.04 | [ROG Zephyrus G15](https://rog.asus.com/laptops/rog-zephyrus/rog-zephyrus-g15-series/spec/) |

## Dotfiles 📂 Bine ❄️

**[dotfiles-bine](https://github.com/lovc21/dotfiles-bine)**

My main laptop runs NixOS 25.11.

### Structure

- **Flake-based** - using nixpkgs-unstable as the primary channel
- **[home-manager](https://github.com/nix-community/home-manager)** - User-level dotfiles management
- **Basic scaffolding** - Organized into hosts/, home/, overlays/, and pkgs/

## Dotfiles 📂 Razor 🟠

**[dotfiles-razor](https://github.com/lovc21/dotfiles-razor)**

My backup laptop runs Ubuntu 24.04.

### Structure

- **Ansible playbooks** - Automated installation of system packages, services, and prerequisites for Ubuntu, Fedora & macOS
- **Chezmoi** - Manages home directory configuration including shell, editor, GTK themes, and terminal profiles
- **Scripts** - Custom automation for common tasks

## License 📄

[WTFPL](https://github.com/JakobDekleva/dotfiles-bine/blob/master/LICENSE)
