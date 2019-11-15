<div align="center"><img src="https://try.gitea.io/img/gitea-lg.png" width="300"/></div>

<h2>【Mac用】HomeBrew でインストールしたGitea の自動起動 </h2>
......意外とハマったので備忘録

```
brew install gitea

sudo launchctl load /Library/LaunchDaemons/homebrew.gitea.plist 
```
