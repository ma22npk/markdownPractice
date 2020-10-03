````
「```」とバッククオート３つで囲むと等幅フォント字下げを行う
````

```
［Command］＋［K］→［V］でVSCode上でマークダウン記法のプレビューを開くことができる。
```

# h1 は「#1 個で見出しを表現できる」

## h2 は「#2 個で見出しを表現できる」

### h3 は「#3 個で見出しを表現できる」

#### h4 は「#4 個で見出しを表現できる」

##### h5 は「#5 個で見出しを表現できる」

###### h6 は「#6 個で見出しを表現できる」

# h1 は「下段に = 1 個で見出しを表現できる」

```
（例）
h1 は「下段に = 1個で見出しを表現できる」
=
```

## h2 は「下段に - 1 個で見出しを表現できる」

```
h2 は「下段に - 1個で見出しを表現できる」
-
```

# p タグ(パラグラフ)の表現

## 次のパラグラフに行きたい場合は空文字列の行を入力する

hello.
hello.hello.hello.hello.hello.hello.hello.

hello.hello.hello.hello.hello.hello.hello.hello.

```
hello.hello.hello.hello.hello.hello.hello.hello.

hello.hello.hello.hello.hello.hello.hello.hello.
```

## 第一パラグラフの中で改行する場合は半角スペースを二つ増やす。

hello.  
hello.hello.hello.hello.hello.hello.hello.

```
hello.(半角スペース二個)
hello.hello.hello.hello.hello.hello.hello.
```

# 引用文を表現

## HTML タグでいうところの blockquote のこと。

> quote. quote.quote.quote.quote.quote.quote.quote.

## 文の先頭に>をいれる

```
>quote. quote.quote.quote.quote.quote.quote.quote.
```

# 区切り線をつける

html でいうところの hr タグ
ハイフン 3 つ以上
（その場合見出しの表現とかぶらないように 1 行開ける）

---

アスタリスク 3 つ

---

アンダースコア 3 つ

---

```
ハイフン3つ以上
（その場合見出しの表現とかぶらないように1行開ける）

---
アスタリスク3つ
***
アンダースコア3つ
___

```
