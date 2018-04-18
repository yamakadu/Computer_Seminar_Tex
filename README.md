# コンピューターゼミ2018(第3回 Tex)

## 宿題
このリポジトリに入っているhomework_example.pdfと同じレイアウトのものをhomework.texに作成しgithub上でpushすることで提出．

## 提出方法
0.初回のみ

    git config --global user.name "name"
    git config --global user.email "example@hiroshima-u.ac.jp"

として個人の識別情報を入力


1.自分のリポジトリへリモートリポジトリ（森原のリポジトリ)からfork

2.自分のリポジトリからファイルをclone
（ブランチの切り替えをしたい人は任意で）

3.編集

4.編集した結果を自分のリポジトリへcommitしpush.**（pdfファイルとtexファイルのみ.**
中間ファイルであるdviファイルなどは削除した状態で）

5.確認してもらう

## 参考資料
・資料[システム工学実験2015年度　Tex演習](http://www.robotics.hiroshima-u.ac.jp/exp/tex/index.html)

・資料：[Latexコマンド集](http://www.latex-cmd.com/)

・資料：[Latex入門](https://texwiki.texjp.org/?LaTeX%E5%85%A5%E9%96%80%2F%E7%B0%A1%E5%8D%98%E3%81%AA%E6%95%B0%E5%BC%8F%281%29)

・資料：[Texあれこれ](http://wiki.rel.hiroshima-u.ac.jp/index.php?TeX%A4%A2%A4%EC%A4%B3%A4%EC)

## コンパイル方法
cloud9上では

    platex homework.tex

を実行するとdviファイルなどができるのでその後

    dvipdf homework.dvi

とすることでpdfを出力可能．

一応これらの作業をまとめたlatexmkというものもあるがcloud9では現状インストールできないので保留で．
