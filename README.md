# Dark AMOLED Dotfiles (⌐■_■)

A sleek collection of dotfiles crafted for Arch Linux, my love letter for AMOLED aesthetics.

## 🌟 What's Inside

This repository contains carefully curated configurations for a modern Arch Linux desktop experience:

### Core Components

**Hyprland** - Smooth animations and soft borders.

**Waybar** - Clean, minimal, and informative without being cluttered + Music control.

**Wofi** - Application launcher.

**Ghostty** - Personalized for optimal readability.

**Brave Nightly** - Coonfiguration file for main settings.

### 🎨 Theme Philosophy

The entire setup revolves around a **Dark AMOLED** theme that's designed to:
- Reduce eye strain during extended use
- Provide true blacks that look stunning on OLED displays
- Create a cohesive visual experience across all applications
- Maintain excellent contrast for readability

## 🚀 Installation

### Prerequisites

```bash
# Core components
sudo pacman -S hyprland waybar wofi

# Additional requirements
yay -S ghostty-bin brave-nightly-bin
```

### Quick Setup

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/arch-dotfiles.git
   cd arch-dotfiles
   ```

2. **Deploy configurations**
   ```bash
   # Copy configurations to their respective locations
   cp -r hypr ~/.config/
   cp -r waybar ~/.config/
   cp -r wofi ~/.config/
   cp -r ghostty ~/.config/

## License

These dotfiles are shared under the MIT License. Use them, modify them, share them!

---

* Happy theming (˘▾˘) *
