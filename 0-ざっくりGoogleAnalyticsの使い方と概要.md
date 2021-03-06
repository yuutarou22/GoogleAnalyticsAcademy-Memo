# 【ざっくり理解】GoogleAnalyticsの使い方と概要

## 【目的を明確にして使う】

仮説を持った上でアクセス解析をすることが重要。

アクセス解析をどうみるか、ではない。

アクセス解析を眺めて改善点を見つける、みたいな使い方は適していない。

アクセス解析をして何をどう改善したいのか、明確にしてやる。

## 【用語】
### ●セッション
ユーザがサイトを訪問してから終わるまでの一連の流れ

途中で何ページ閲覧しても1回の訪問であればセッションは１。

サイト訪問し、離脱して、再度訪問すればセッションは２。

### ●ユニークユーザ
サイトの訪問人数。

同じ人が何度訪れても１。

PCとスマホからであれば２になる。

## ●ページビュー（PR）
ユーザがサイト内で閲覧したページ数。

1人のユーザが10ページ閲覧した場合は、

ユーザ数１、ページビュー10となる。

### ●離脱率
ユーザが最後に閲覧したページの割合。

離脱率が高いページは、ユーザが離脱する最後の出口となっている。

そこを改善すれば離脱率を下げ、ページビューを増やす対策ができる。

### ●直帰率
ユーザが1ページだけ閲覧し離脱した割合のこと。

内部リンクをクリックして、別のページに遷移したら直帰にならない。

### ●ページ滞在時間
ユーザがページを閲覧している時間のこと。

閲覧開始時間と別ページに遷移するまでの時間

離脱したページの滞在時間は０となる。

※アナリティクス側はいつ離脱したのか計測できないため。


## 【初心者向けレポート一覧】

### ●リアルタイム＞概要
リアルタイムでアクセスしているユーザの行動が可視化される。

トレンドで急上昇した際は確認する


### ●ユーザ＞ユーザフロー
ユーザが最初に訪問したページからのページ遷移がわかるレポート。

ユーザの行動がわかる。

わかりやすいように「ランディングページ」を選択しておくと良い。


### ●ユーザ＞ユーザ属性

訪問したユーザの年齢や性別がわかる。

コンテンツ内容の参考にできる。

レポート画面を開いて有効化しておかないと使えないので要注意。


### ●ユーザ＞モバイル＞概要
PC、タブレット、スマホなどアクセスした媒体のデータが確認できる。


### ●集客＞概要＞すべてのトラフィック＞チャネル
どこからユーザがアクセスしているのかがわかる。

アクセスが増加したときに確認する。

どこからアクセスが増えているのか把握しておくことが重要。

- Referral
  - 別サイトからリンク経由で訪問
- Direct
  - ブックマークから訪問
- Social
  - SNSから訪問
- Organic Search
  - 検索エンジンからの検索で訪問（リスティング広告を除外）
- Paid Search
  - リスティング広告から訪問
- Other
  - 不明なものはOtherになる


### ●集客＞概要＞すべてのトラフィック＞参照元/メディア
アクセス元をさらに細かく見れる。

ブラウザ、SNSなどどこからどれくらいアクセスされているかわかる。

どこのドメインからのアクセスなのかも細かく確認できる。


### ●集客＞概要＞ソーシャル＞ユーザフロー
各SNS経由でどのページにアクセスされているのかわかる。

改善するなら流入が多いページを改善していく。


### ●行動＞概要
一番みることが多いレポート。

- 全体のPV
- 平均滞在時間
- 直帰率

重要なデータを確認できる。


### ●行動＞サイトコンテンツ＞すべてのページ
上記とほぼ同じ。

直帰率は平均40%となる。

ただ、直帰率はページの役割による。

ランディングページは極端に直帰率が高い。

QAサイトも直帰率が高い。


### ●行動＞サイトコンテンツ＞ランディングページ
ランディングページとは、ユーザが最初に訪問したページのこと。

ユーザが一番最初に訪問したページがわかる。

この最初に訪問したページを改善すれば、直帰率の低下につながるため効率が良い。


### ●行動＞サイトコンテンツ＞離脱ページ

離脱率が高いページは改善が必要になる（場合もある）


### ●行動＞サイトの速度＞概要
読み込みやサーバの応答時間を確認できる。

目安は「2秒以内」がよい。

3秒以上読み込みに時間がかかるとユーザの離脱が極端に上昇する。

- 平均読み込み時間
  - ページの読み込み開始から終了までの総待ち時間
- サーバの応答時間
  - サーバ負荷が高くなると時間が長くなる
- ページの平均ダウンロード時間
  - HTMLやリソースが最適化されていないと時間が長くなる


### ●行動＞サイトの速度＞速度についての提案

各ページの平均読み込み時間、Page Speedスコアなどを確認できる。

レポートないの提案をクリックするだけで「Page Speed Insights」に飛べる。
