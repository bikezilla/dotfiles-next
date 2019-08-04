# Clean install a mac
1. Download the new image, then
2. Do the following to a usb drive:
```
sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/Untitled -- /Applications/Install\ macOS\ Mojave.app

```
3. Restart holding option
4. Launch disk utility, erase HDD
5. Go back and install

# Applications

## Misc
- 1Password
- CommanderOne
- Kindle
- LibreOffice
- Spotify
- VLC

## Toolbar
- iTerm
- Fluor (function key remap - choose function keys for VIM)
- Karabiner (keybord remap tilde and +-)
- Bartender (hides icons)
- spectacle (window management)
- Caffeine

## Dev tools
- iTerm2
- Docker
- Dash (requires license)
- Markoff
- htop
- hub (github console client)jsonviewj

## Work
- Tunnelblick
- Slack
- Zoom.us

## Chrome
- Adblock
- jsonview
- livereload
- page load time
- react dev tools
- pocket
- vimium
- momentum

## Firefox
- 1pass
- adblock plus
- multi-account containers
- react dev tools
- vimium

## GIS and bikes
- Google Earth Pro
- Garmin BaseCamp
- Garmin MapManager and MapInstall
- FBX Review (3D model view)
- DraftSight


# Install command history
    1  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    2  brew install cask
    4  brew cask install google-chrome
    5  brew cask install firefox
    8  brew cask install 1password
   10  brew cask install commander-one
   12  brew install rbenv
   29  brew cask install spectacle
   33  brew install caffeine
   34  brew cask install caffeine
   52  brew install macvim

# Notes
- macvim needs to be linked after install
- Monaco for Powerline and Menlo for Powerline need to be installed
- need to change default shell like this: 
```
$ sudo echo "$(which zsh)" >> /etc/shells
$ chsh -s $(which zsh)
```
