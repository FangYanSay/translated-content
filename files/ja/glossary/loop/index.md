---
title: Loop (ループ)
slug: Glossary/loop
tags:
  - CodingScripting
  - Glossary
  - control flow
  - programming
  - プログラミング
  - 制御フロー
  - 用語集
translation_of: Glossary/loop
---
ループは、{{Glossary("computer programming","コンピュータプログラミング")}}において、一定の条件に遭遇するまで継続的に繰り返される一連の命令です。例えば、データ項目を取得して加工しながら、カウンターが所定の値に達するなどいくつかの{{Glossary("conditional","条件")}}をチェックするというような処理です。

## 例

### for ループ

#### 構文:

```
for (文1; 文2; 文3){
 実行コードブロック
}
```

- 文 1 は、コードブロックが実行される前に一度実行されます。
- 文 2 は、コードブロックを実行するのに必要な条件を定義します。
- 文 3 は、コードブロックが実行されるたびに実行されます。

#### 例:

```js
for(var i = 0; i < 10; i++){
    console.log(i)
}
//このループは数字の 0-9 の数字を表示し、条件に合う (i = 10) と停止します
```

上記の例では、構文は以下のようになっています。

- 文 1 (var i = 0) はループの変数を設定しています。
- 文 2 (i < 10) はループの条件を設定しています。
- 文 3 (i++) はコードブロックが実行されるたびに i の値を増加させます。

### while ループ

#### 構文:

```
while (条件){
 実行コードブロック
}
```

- このコードブロックは条件が真である限り、継続します。

#### 例:

```js
var i = 0;
while(i < 5){
    console.log(i)
    i++
}
//このループは 0-4 の数字を表示し、条件 (i >=5) が偽になると停止します
```

上記の例では、構文は以下のようになっています。

- コードブロックは変数 (i) が 5 未満である限り、実行が継続します。

1.  General Knowledge

    1.  Wikipedia の {{Interwiki("wikipedia", "制御構造#ループ", "制御構造")}}

2.  [MDN Web Docs 用語集](/ja/docs/Glossary)

    1.  {{Glossary("Loop", "ループ")}}