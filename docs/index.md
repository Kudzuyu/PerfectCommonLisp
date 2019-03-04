# Perfect CommonLispとは

Common Lispの基本から応用までをまとめたもの(予定)

## 構成

* Environments: Lispの開発環境を整える
* Learning: Lispの書き方について学ぶ
* Using: Lispを使って実用的なプログラムを書く

## コードについて

文章中でコードは以下のように示す

```lisp
(print "Welcome to Perfect-CommonLisp!")
```

実行結果の場合は>が行頭にあり、続く行で結果を示す。

```lisp
> (print (+ 1 2))
3
```

また、;(セミコロン)より後はコメントとなる。コメントはプログラム中で特定の行に関するちょっとした説明などで使う。コメントはプログラムの実行に一切影響を与えない。

```lisp
(princ "コメントは実行時には無視される") ;ここはコメント
```

## 開発

このサイトは[github](https://github.com/Kudzuyu/PerfectCommonLisp)上で開発されている。
