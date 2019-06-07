# HTTPでやりとりする仕組み

<!-- Markdown記法のヒント

コード記法（1行の中に埋めたい場合）

`code`

コードブロック記法（複数行）

```
print('a')
print('b')
```

-->

## 実習でやったこと (Y)

HTTPレスポンスを確認してlessで見る

## 自分で調べたこと

HTTPで調べること

## HTTPメッセージ (kd.txt) のうち、最も重要だと思う部分を貼り付けてください

```
GET / HTTP/1.0 

HTTP/1.0 200 OK　

Date: Fri, 07 Jun 2019 01:37:34 GMT

Server: Apache　　　　　　　　　　　　　　　　　　

X-Cached: Fri, 07 Jun 2019 01:37:34 GMT

X-Pingback: https:/xmlrpc.php

Last-Modified: Fri, 07 Jun 2019 01:37:34 GMT

X-Accel-Expires: 0
                                              
Cache-Control: max-age=300

Expires: Fri, 07 Jun 2019 01:42:34 GMT

Vary: Accept-Encoding

Connection: close

Content-Type: text/html; charset=UTF-8          
```

## それはなぜですか？

この部分はHTTPの基本だから
GET / HTTP/1.0 はリクエスト行で
HTTP/1.0 200 OK　はリスポンス行です
Server: ApacheからContent-Type: text/html; charset=UTF-8まではメッセージヘッダーです。

## わかったこと・気づいたこと

HTTPの基本は大切です。
