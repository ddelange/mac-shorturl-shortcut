# AppleScript to shorten links using the bitly API in a smart way directly with a keyboard shortcut

## Requirements
- Account at bitly.com
- Mac running OS X 10.7+
- (optional) Dropbox app

## Installation
- Copy the script over:
```bash
git clone https://github.com/ddelange/mac-smart-bitly-shortcut.git ~/git/mac-smart-bitly-shortcut
cp -r ~/git/mac-smart-bitly-shortcut/ShortURL.workflow ~/Library/Services
open ~/Library/Services/ShortURL.workflow
```
- Fill in your bitly credentials
- Set your preferred shortcut under `System Preferences/Keyboard/Services/Text/ShortURL` (I like ⌃⌥⌘V)
- (optional) Setup Dropbox direct-link screen shot sharing
  - Tick `Share screenshots using Dropbox` in the `Import` tab of Dropbox preferences
  - Screenshots will now be automatically moved to `~/Dropbox/Screenshots`, its link copied to the clipboard ready for shortening
