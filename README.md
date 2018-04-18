# コンピューターゼミ2018(第3回 Tex)

## 宿題
このリポジトリに入っているhomework.pdfと同じレイアウトのものをhomework_name.tex上（nameの部分は自分の名前に書き換える)に作成しgithub上でpull requestを送ることで提出．

## 提出方法
1.自分のリポジトリへリモートリポジトリ（森原のリポジトリ)からfork

2.自分のリポジトリからファイルをclone
（ブランチの切り替えをしたい人は任意で）

3.編集

4.編集した結果を自分のリポジトリへcommitしpush.**（pdfファイルとtexファイルのみ.**
中間ファイルであるdviファイルなどは削除した状態で）

5.自分のリポジトリからfork元のリポジトリへpull request

## 参考資料
・資料[システム工学実験2015年度　Tex演習](http://www.robotics.hiroshima-u.ac.jp/exp/tex/index.html)

・資料：[Latexコマンド集](http://www.latex-cmd.com/)

・資料：[Latex入門](https://texwiki.texjp.org/?LaTeX%E5%85%A5%E9%96%80%2F%E7%B0%A1%E5%8D%98%E3%81%AA%E6%95%B0%E5%BC%8F%281%29)

・資料：[Texあれこれ](http://wiki.rel.hiroshima-u.ac.jp/index.php?TeX%A4%A2%A4%EC%A4%B3%A4%EC)

## コンパイル方法
cloud9上では

    platex homework_name.tex

を実行するとdviファイルなどができるのでその後

    dvipdf homework_name.dvipdf

とすることでpdfを出力可能．

一応これらの作業をまとめたlatexmkというものもあるがcloud9では現状インストールできないので保留で．
