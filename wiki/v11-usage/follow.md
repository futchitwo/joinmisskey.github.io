---
title: フォローなど
description: フォロー・ミュート・ブロック、非公開アカウントについて。
layout: wiki
rank: 2
prev: /wiki/v11-usage/timelines
next: /wiki/v11-usage/list
---
## フォローなどを行う
それぞれの操作は、対象のユーザーのページで行える。

### フォロー
フォローをすると、その人のノートをホームタイムラインおよびソーシャルタイムラインで表示できる。ただし、他のユーザーに対する返信は含まれない。  

### ミュート
ユーザーをミュートすると、そのユーザーに関する次のコンテンツがMisskeyに表示されなくなる:

- タイムラインやノートの検索結果内の、そのユーザーのノートおよびそれらのノートに対する返信やリノート
- そのユーザーからの通知
- メッセージ履歴一覧内の、そのユーザーとのメッセージ履歴

ミュートを行ったことは相手に通知されず、ミュートされていることを知ることもできない。

`設定` > `ミュート/ブロック` から、自分がミュートしているユーザー一覧を確認できる。

### ブロック
ユーザーをブロックすると、そのユーザーは自分へのフォローができなくなる。すでにフォローされている場合はフォローが外れる。

`設定` > `ミュート/ブロック` から、自分がブロックしているユーザー一覧を確認できる。

## 鍵アカウント（フォローを承認制にする）
`設定` > `プロフィール`で「フォローを承認制にする」を有効にすると、自分へのすべてのフォローが承認制になる。  
Botからのフォローだけ承認制にすることもできる。  
これらの設定を有効にすると、メニューに「フォロー申請」が現れ、これを開くとフォローの申請を承認か拒否できる。

自動的にノートが非公開になるわけではなく、適切な[公開範囲](post#公開範囲を設定する)を設定する必要がある。