# LibreWolf AI Chat for Hyprland

A minimal AI chat interface configuration that removes the LibreWolf/Firefox toolbar for a clean chat-only experience.

## Features

- Clean, distraction-free chat interface
- Removes browser toolbar using custom userChrome.css (you can just ```$mainMod + C``` and only focus to the chat within the Hyprland window)
- It gives the feeling you're not in a browser you're just looking to the chat's window
- Quick keyboard shortcut integration with Hyprland
- You can use this with any ```tiling window manager```

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

- Hyprland or a tiling window manager
- LibreWolf or Firefox
- You need to set ```toolkit.legacyUserProfileCustomizations.stylesheets``` to ```true```

## License

MIT License
