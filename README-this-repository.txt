== このリポジトリで対応するブランチ一覧

この作業手順では以下のような方針でブランチを運用する．
* master
  後述するupstreamとchanges/*，localを全てマージしたもの．
* upstream
  upstreamの最新ソースコードを入れるブランチ．
* changes/*
  このリポジトリで機能追加あるいは不具合修正を行うブランチ．
  * changes/add-bin_dir-to-PATH
    ~/.multiruby/install/1.8.6-p368/binを環境変数PATHの先頭に追加
* local
  リポジトリ固有のupstreamには有益でないと思われる変更を行うブランチ．
