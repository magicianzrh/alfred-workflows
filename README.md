# alfred-workflows
BE CAREFUL IF YOU USE

- Time Machine Controller

```
only support start and stop
```

- Refresh DNS command

```
shell command to clipboard(NEED SUDO)
```

- Clear Open With Duplicate

```
just try to clear, may relaunch Finder (alt + Right-click)
```

- Clear Xcode Dev Folder.alfredworkflow

```
delete ~/Library/Developer/Xcode/DerivedData and ~/Library/Developer/Xcode/iOS DeviceSupport
```

- LaunchPad Reset.alfredworkflow

```
rm ~/Library/Application\ Support/Dock/*.db
rm "/$TMPDIR/../0/com.apple.dock.launchpad/db/db*"
defaults write com.apple.dock ResetLaunchPad -bool true; killall Dock
```