### 1.终端下执行下面命令

显示全部文件 

defaults write com.apple.finder AppleShowAllFiles -bool true osascript -e 'tell application "Finder" to quit' 

不显示全部文件 

defaults write com.apple.finder AppleShowAllFiles -bool false osascript -e 'tell application "Finder" to quit

