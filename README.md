# mac-setup
*Specific System: Macbook Pro late 2016, Sierra 10.12*

## Preferences
+ **Mission Control >** Disable Automatically rearranging Spaces
+ **Language & Region >** Enable 24hr time
+ **Security & Privacy > FileVault** On
+ **Security & Privacy > Firewall** On
+ If using [Magnet](https://itunes.apple.com/us/app/magnet/id441258766?mt=12), **Security & Privacy > Privacy > Accessibility  >** Enable Magnet
+ If using [coconutBattery](http://www.coconut-flavour.com/coconutbattery/), **Energy Saver >** Don't show battery status in menu bar
+ **Keyboard > Customize Control Strip >** Replace Siri Button with Play/Pause Button
+ **Keyboard > Modifier Keys >** Remap Caps Lock Key to Escape action
+ **Keyboard > Shortcuts > Mission Contol >** Enable 'Switch to Desktop #' as ^# <sup>*</sup>
+ **User & Groups > Login Items >** Enable Spotify, Lastpass

**Show Hidden Files in Finder**
```
defaults write com.apple.finder AppleShowAllFiles YES
```
**Show Finder Path**
```
defaults write com.apple.finder ShowPathbar -bool true
```
**Show Finder Status Bar**
```
defaults write com.apple.finder ShowStatusBar -bool true
```

<sup>*</sup> *These options are shown depending on the amount of Workspaces currently enabled. I temporarily enabled Workspaces 1-10 in order to map them to ^1-10.*

## Homebrew
Installation
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
Making sure it works
```
brew doctor
```
### handy commands
Installation of packages/formulae
```
brew install <formula>
```
Uninstalling formulae
```
brew remove <formula>
# or
brew rm <formula>
# or
brew uninstall <formula>
```
Update Homebrew's directory of formulae
```
brew update
```
Seeing outdated packages
```
brew outdated
```
Updating a package
```
brew upgrade <formula>
```
Cleaning old versions of packages
```
brew cleanup
```
Seeing list of install package w/ version number
```
brew list --versions
```
## Inspiration
This guide was inspired by the following resources:
+ https://github.com/taniarascia/mac
+ http://sourabhbajaj.com/mac-setup/
+ https://www.reddit.com/r/apple/comments/5kei73/a_complete_guide_to_securing_yourself_your_mac/
