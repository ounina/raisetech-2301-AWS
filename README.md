# raisetech-2301-AWS
raisetechAWS第2回提出用課題

1　gitダウンロード
2　git設定
　git --version
git version 2.39.1.windows.1

　ユーザーとメール設定
git config --global user.name "ユーザー名"
git config --global user.email "メールアドレス"
git config --global --list
ユーザー名とメールアドレス確認

3　Windows 11に GitHubdesktopインストール
　GitHubdesktopダウンロード
　Windows (64bit)
4  GitとPowerShell設定
　powershell管理員身分開く
　下記のコマンド実行
　①Get-ExecutionPolicy　なら
　RemoteSigned→設定される
　なかった場合、下記のコマンド実行
　②Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned -Force
5　Posh-gitインストール
　①Install-Module posh-git -Scope CurrentUser -Force
　②Import-Module posh-git
　③Add-PoshGitToProfile -AllHosts
　

