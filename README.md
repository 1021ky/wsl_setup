# このリポジトリについて

* 自分のwsl ubuntu内でのセットアップ用のansibleスクリプト
* 移行のときにやりやすくするためのもの
* wslのホストはwingetでセットアップする前提
* ` ansible-playbook --ask-become-pass -i inventory site.yml` でプロビジョンする
* role指定で実行するときは `ansible localhost --ask-become-pass -i inventory  -m include_role -a name={ロール名}`
