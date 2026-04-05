# hammerspoon-config

My Hammerspoon configuration for macOS automation. [Hammerspoon](http://www.hammerspoon.org) is a powerful macOS automation tool driven by Lua.

## Features

- **Window management** — keyboard shortcuts for moving and resizing windows
- **Chooser toolbar** — quick launcher for apps and actions
- **Hue motion sensor** — Philips Hue integration for office motion detection
- **Office motion** — presence-based automation
- **Reachability menu** — network status menu bar item
- **Status LEDs** — visual status indicators in the menu bar
- **StreamDeck / OBS integration** — via legacy config (see `__old_streamdeck.lua`)

## Installation

1. Install [Hammerspoon](https://www.hammerspoon.org/)
2. Clone this repo to `~/.hammerspoon/`:
   ```sh
   git clone https://github.com/wkoszek/hammerspoon-config ~/.hammerspoon
   ```
3. Reload Hammerspoon config (`⌘⌥⌃R` or via menu)

## Notes

- `private.lua` is not included in this repo — it contains work-related configuration
- Requires Hammerspoon 0.9.x or later
- ZeroBrane Studio debug support is commented out in `init.lua`

## Author

Wojciech Koszek — [wojciech@koszek.com](mailto:wojciech@koszek.com)
