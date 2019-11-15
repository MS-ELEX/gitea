###【Mac用】HomeBrew でインストールしたGitea の自動起動
......意外とハマったので備忘録

brew install gitea

sudo launchctl load /Library/LaunchDaemons/homebrew.gitea.plist 
