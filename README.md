# Vanilla Tabless Firefox

## Features
- Hide horizontal tab bar.
- MacOS window control buttons.
- Hide unnecessary address bar buttons: bookmark, container context.
- Easy to maintain, widely compatible with Firefox themes.


## Setup
### Firefox's `userChrome.css` setup:
  1. In Firefox, go to `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `True`
  2. Create `chrome` directory in your Firefox profile directory
      - Linux - `$HOME/.mozilla/firefox/XXXXXXX.default-XXXXXX/`
      - Windows - `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
      - macOS - `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX`
  3. Copy paste `userChrome.css` in the `chrome` directory created in previous step

### Other setup:
  1. Install `Sidebery` Firefox extension, for vertical tabs.
  2. Install `Tabliss` Firefox extension, for new tab theme.
  3. Customize toolbar and move all extension & other icons in overflow menu space.


## Preview
![Screenshot 1](screenshots/screenshot%201.png "View 1")
![Screenshot 2](screenshots/screenshot%202.png "View 2")
![Screenshot 3](screenshots/screenshot%203.png "View 3")
![Screenshot 4](screenshots/screenshot%204.png "View 4")
![Screenshot 5](screenshots/screenshot%205.png "View 5")

### Tested on
  1. Windows 11 + Firefox 108