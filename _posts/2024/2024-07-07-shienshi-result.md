---
title: 情報処理安全確保支援士試験に合格した
date: 2024-07-27
layout: post
mermaid: true
---

4月に受けた情報処理安全確保支援士試験に合格しました。

![](/assets/images/posts/2024-07-07-sc-result.png)

以前のブログで「もし合格していたら、「一週間で合格する情報処理安全確保支援士」というタイトルで記事でも書こう」と言っていたけれど、あまりにおすすめできないのでやめておきます。

過去問は解いたほうがいいです絶対。

とりあえず勉強方法だけメモします。

### 午前II

お世話になったのは下記3つ。

- [情報処理安全確保支援士過去問道場](https://www.sc-siken.com/sckakomon.php)
- [情報処理教科書 情報処理安全確保支援士 2024年版](https://www.shoeisha.co.jp/book/detail/9784798183534)
- [Youtube　まさるの勉強部屋【サクッと学べる支援士対策】シリーズ](https://www.youtube.com/watch?v=vmRkn5JNqa0&list=PLfrpqyRFsglL3WgvYiZsBO7Al1YsE64DI)

初見で過去問道場を解く→間違えたところを参考書で調べるという流れで、知識の漏れを拾うように勉強しました。

通勤電車などのスキマ時間には、Youtubeで基本知識をざっとさらいました。

まさる様の動画は本当にクオリティが高く「これが無料で見れていいのか」と驚きました。
特にメール認証周りは仕組みがあやふやだったので、分かりやすくまとめてくださって感謝です。

布教↓

<iframe width="560" height="315" src="https://www.youtube.com/embed/BPhDorZgR8U?si=xjT7PmL0iAwL5AxS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### 午後問

実務経験が活きました。言い換えると運が良かったです。

午後問は全4問から2問選択する形式で、私は問1のAPIセキュリティに関する問題と、問3のWebセキュリティに関する問題を選択しました。

XSS、CSRF、認可周り気にしながらWebアプリ開発したことあれば、上記問題は対策なしである程度得点できると思います。

本読むより、フレームワーク使いつつクラウド上にAPIサーバ立てるのが一番試験対策になりそう。

あとIPAの[安全なウェブサイトの作り方](https://www.ipa.go.jp/security/vuln/websecurity/about.html)は読んでいて良かった。

今回ネットワーク周りは出なかったのですが、CISCOのPacket Tracer使ってLAN作るといいんじゃないでしょうか。

書いていて、参考になりそうな内容全然なくて悲しくなりました。

でもIPAの高度試験は実務知識の定着度測定ぐらいに挑むのがいいんだろうなあと思います。