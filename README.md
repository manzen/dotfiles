# dotfiles

## githubの初期化

移行元のPCから以下のファイルを移植

~/.sshに以下のファイルを配置

config
github_id_rsa
github_id_rsa.pub
known_hosts

以下コマンドで確認

ssh -T git@github.com

これで成功
origin	git@github.com:manzen/dotfiles.git (fetch)
origin	git@github.com:manzen/dotfiles.git (push)

