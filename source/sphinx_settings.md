# Sphinxの設定

- 参考サイト 
    - https://qiita.com/tutuz/items/88a32d94d700b33dc3ea
    - https://sky-joker.github.io/github_sphinx_example/#docs
- github pagesで公開するにはdocsフォルダにあると便利。なのでxcopyでbuild後にdocsに移動させる
- テーマはread the docs
    - ```pip install sphinx-rtd-theme```
- Markdownで書く
    - rstも優れたフォーマットだが、文法がrstよりやや冗長
    - ```pip install recommonmark```
    - 書いてあるとおりやればだいたいできる https://github.com/readthedocs/recommonmark

# Markdown

- 数式入りのMarkdownをMath MLに対応させる
    - https://qiita.com/yohm/items/f14f03ccee918d4d7213
    - epubはmathmlに対応しているため(mathjaxが使えないように見える)
    - markdownをpandocでhtmlに変換してから、calibreなどのepubコンバータで変換すると数式がちゃんと表示される
    - kindleで表示したい場合はkindler previewerでmobiなどに変換できる
- [https://qiita.com/pashango2/items/cd78658bc16240ef23d8](https://qiita.com/pashango2/items/cd78658bc16240ef23d8)