## ファイル探索ルール

Markdownファイルの探索は以下のルールに従って行われます：

1. 指定されたディレクトリ内のすべてのファイルとフォルダを再帰的に探索します
2. `.md`拡張子を持つファイルのみを処理対象とします
3. サブディレクトリも含めて探索を行います
4. 実行時には指定されたフォルダ階層の構造が維持されます