# test-gfm-without-front-matter

- front matter を持たないGFMファイルのサンプル。
- https://github.com/benbalter/jekyll-optional-front-matter を組み込めば HTML に変換してくれる。
- デフォルトで上記プラグインが有効になっているので、この markdown もデフォルトでHTMLに変換される。
- README.md も front matter を持たないGFMとなっているが、上記プラグインの標準の除外ファイルに指定されているため、HTMLに変換されない。
  - 元の `.md` ソースファイルは `_site` 以下にコピーされる点に注意。

