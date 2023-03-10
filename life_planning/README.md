# テーマ「FPとオンラインで相談しながらライフプランを考えていきたい」

ライフイベントを実現するための資金計画を、オンラインかつ非同期でやり取りしながら進められるようにしたい

→忙しい人でもスキマ時間さえあればライフプランを立てていくことが可能になるよ！というてい

# 用語集

## 相談者
ライフプランを立てたい！と考えている人。ユーザの1人。

## FP
ファイナンシャルプランナー。ライフプランを実現すべく、資金計画を立てる専門家のこと。ユーザの1人。

## ライフプラン
生きていく上で起こる数々のイベントをどのように実現するか示した案。生きていく上でお金は必要なので、ライフプランの実現のためには資金計画が必要となる。

ライフプランの実現考える上で、ライフイベント表、キャッシュフロー表、個人バランスシートといったツールを使って資金計画を立てていく必要がある。

## ライフイベント表
家族の将来のライフイベントと、それに必要な資金の額を時系列にまとめた表。

## キャッシュフロー表
ライフイベント表と現在の収支にもとづいて、将来の収支状況と貯蓄残高の予想をまとめた表。収入には年収ではなく給与収入を使う。

## 個人バランスシート
一定時点における資産と負債のバランスをみるための表。

## 給与収入
いわゆる可処分所得のこと。

## 可処分所得
年収から社会保険料（健康保険料、厚生年金保険料、雇用保険料など）と所得税および住民税を差し引いた金額。

# ドメインモデリングしていく上でドメインの理解について繋がったことメモ
## ユースケース図
### 「複数FPに相談するケースがあるか?」という疑問が湧いた
実際に調べてみると、ライフプランニングにおいても複数FPに相談するケースがあることがわかった。(お医者さんのセカンドオピニオン的なノリだろう)
そこから、「相談者」だけだったアクターから「会員」「相談者」にわけた。

### 「ライフプランは1つだけで良いのだろうか？」という疑問が湧いた
例えば家族で子供を1人だけ授かる場合と、2人授かる場合ではライフプランも変わってくるだろう。
よってライフプランは複数作れるものとし、上にプロジェクトの概念を作成した。