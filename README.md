# bemtemplate
```
 _                    _                       _       _
 | |__   ___ _ __ ___ | |_ ___ _ __ ___  _ __ | | __ _| |_ ___
 | '_ \ / _ \ '_ ` _ \| __/ _ \ '_ ` _ \| '_ \| |/ _` | __/ _ \
 | |_) |  __/ | | | | | ||  __/ | | | | | |_) | | (_| | ||  __/
 |_.__/ \___|_| |_| |_|\__\___|_| |_| |_| .__/|_|\__,_|\__\___|
                                        |_|
```
## Description
bemtemplate は LaTeX スライドドキュメントクラス Beamer のテンプレートファイルである. 一般的な Beamer の記法に加えて tex2mp4 のための特殊なコメントアウト "%!" が記載されている. tex2mp4 を使わない場合は特殊なコメントアウトは一般的なコメントアウトと同じである.

## install
TeX Live すでにインストールしているならばbemtemlate 使用に伴い, 特に追加のインストールは必要ない. TeX Liveをインストールしていない場合は
[TeX Live - Quick instal](https://tug.or/texlive/quickinstall.html)に従って TeX Liveをインストールする.

## Folder Structure
bemtemplate
│  kikinagasi_math1.pdf
│  kikinagasi_math1.tex
│  README.md
└─fig
        1.png
        2.png
        3.png
        4.png
        5.png
        6.png

## USAGE
TeX Liveをインストールしているならば, ターミナルで bemtemplate フォルダへ移動し,
次のコマンドを順次実行すれば参考文献・索引付きの PDF を生成することができる.
```
$ lualatex bemtemplate.tex
```