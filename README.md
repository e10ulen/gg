#   これなに
`` gg `` というアプリケーションです。

コミット関係を自動化したいなと思って作成しました。

絶対にリファクタリングは必要ですが今の所困ってないのでこのままで行きます。

#  gg a
git add .と同等です

# gg c <commitmessage>
git commit -m "<commitmessage>"と同等です

# gg p
git push -uと同等です

# gg f <commitmessage>
上記３つのコマンドを一度に実行します。
