1\. Change the Screen Shot Save File Location in Mac OS X

```
defaults write com.apple.screencapture location ~/Pictures/
```

2\. Hit the return key to set ~/Pictures as the location.

3\. You'll need to follow it up with a SystemUIServer relaunch too:

```
killall SystemUIServer
```
