## ディレクトリ処理ルール

ディレクトリの処理は以下のルールに従って行われます：

1. `rules`フォルダ直下のサブディレクトリごとにMDCファイルが生成されます
2. 先頭に`@`がついているフォルダは処理から除外されます。
3. 出力先のディレクトリ（`.cursor/rules/`）が存在しない場合は自動的に作成されます
4. 各サブディレクトリごとに並行処理が行われ、効率的にファイルが生成されます