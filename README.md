# LibreWolf AI Chat for Hyprland

A minimal AI chat interface configuration that removes the LibreWolf/Firefox toolbar for a clean chat-only experience.

## Features

- Clean, distraction-free chat interface
- Removes browser toolbar using custom userChrome.css
- Quick keyboard shortcut integration with Hyprland

## Installation

1. Copy the userChrome.css to your LibreWolf/Firefox profile directory:
```/.mozilla/firefox/[profile-id]/chrome/userChrome.css```

2. Place the ai.sh script in your user scripts directory:
```~/.config/hypr/UserScripts/ai.sh```

3. Add the following line ```bind = $mainMod, C, exec, $UserScripts/ai.sh # Opens chatbot```

to your Hyprland keybinds configuration:
```~/.config/hypr/configs/Keybinds.conf```


## Usage

Press `Super + C` to open the AI chat interface in LibreWolf/Firefox with a clean, toolbar-free view.

## Configuration Files

- `userChrome.css`: Hides the browser toolbar
- `ai.sh`: Launch script for the chat interface
- `Keybinds.conf`: Hyprland keyboard shortcut configuration

## Requirements

- Hyprland
- LibreWolf or Firefox
- Properly configured userChrome.css support

## License

MIT License
