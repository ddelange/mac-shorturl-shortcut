# AppleScript to shorten links using the bitly API in a smart way directly with a keyboard shortcut
Currently still using bitly API v2.0.1

#### Shortens links after percent-encoding them
![simpleshorten](https://user-images.githubusercontent.com/14880945/51790918-b281a880-219b-11e9-86e6-9caa7f4e397d.gif)

#### Changes Dropbox links for direct-view/direct-download
![screenshotshorten](https://user-images.githubusercontent.com/14880945/51790920-b44b6c00-219b-11e9-9d93-57f8717bd33c.gif)

## Requirements
- Account at [bitly.com](bitly.com)
- Mac running OS X 10.7+
- (optional) Dropbox app

## Installation
- Copy and open the script:
```bash
git clone https://github.com/ddelange/mac-shorturl-shortcut.git ~/git/mac-shorturl-shortcut
cp -r ~/git/mac-shorturl-shortcut/ShortURL.workflow ~/Library/Services
open ~/Library/Services/ShortURL.workflow
```
- Fill in your bitly username & [Generic Access Token](https://bitly.com/a/oauth_apps)
- Set your preferred shortcut under `System Preferences/Keyboard/Services/Text/ShortURL` (I like ⌃⌥⌘V)
- (optional) Setup Dropbox direct-link screen shot sharing
  - Tick `Share screenshots using Dropbox` in the `Import` tab of Dropbox preferences
  - Screenshots will now be automatically moved to `~/Dropbox/Screenshots`, its link copied to the clipboard ready for shortening
