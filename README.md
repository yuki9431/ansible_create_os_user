Rename defalut OS user name.
===
## 概要
LinuxOSのデフォルトユーザ名を変更する 
1. Install ssh key for root access
1. Make sure root can ssh in
1. Kill processes by user
1. Move home directory
1. Rename user
1. Restore sshd config

## 動作確認済み環境
Rasbian 9.3

## 変数
```
ssh_key        # rootログイン用の公開鍵ディレクトリ
old_username   # 変更前のユーザ名
new_username   # 変更後のユーザ名
```

## 依存関係
なし
