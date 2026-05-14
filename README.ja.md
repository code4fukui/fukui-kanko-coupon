# fukui-kanko-coupon

このプロジェクトは、新型コロナウイルス感染症の影響を受けた地元の観光事業者を支援する福井県のキャンペーン「ふくいdeお得クーポン」の利用データを可視化したものです。

## デモ

[**クーポン利用のインタラクティブ1kmメッシュマップ**](https://code4fukui.github.io/fukui-kanko-coupon/)

デモでは、クーポンの利用データをインタラクティブなマップ上で可視化しています。日付範囲、利用者の都道府県、年代、性別、カテゴリーでデータをフィルタリングすることができます。

## 機能

- **インタラクティブマップ:** ズーム可能なマップ上で、福井県全体のクーポン利用金額を可視化します。
- **地理空間データの集約:** データを1km²の地理メッシュ（Geo3x3）に集約し、利用のホットスポットを表示します。
- **動的フィルタリング:** 以下の条件で取引データをフィルタリングできます:
    - 日付範囲（2023-01-10 ～ 2023-08-05）
    - 利用者の都道府県
    - 利用者の年代
    - 利用者の性別
    - カテゴリー

## オープンデータ

本プロジェクトでは、分析や再利用のために以下のオープンデータセットを提供しています。

- **利用者データ（CC BY）**
    - [`users.csv`](users.csv): 利用者リスト（ユーザID、都道府県、性別、利用回数、利用金額、年代）。
    - [`users_amount.csv`](users_amount.csv): 利用金額順にソートされた利用者データ。
    - [`users_count.csv`](users_count.csv): 利用回数順にソートされた利用者データ。

- **取引データ（CC BY）**
    - [`mesh-tr.csv`](mesh-tr.csv): 全取引リスト（取引日時、ユーザID、取引種別、金額、取消フラグ、カテゴリー、カテゴリー2、Geo3x3）。
    - [`mesh-tr-total.csv`](mesh-tr-total.csv): メッシュごとの集約利用金額（Geo3x3、カテゴリー、利用金額）。

- **地理空間データ（CC0）**
    - [`mesh-geo3x3.geojson`](mesh-geo3x3.geojson): 可視化に使用する1kmメッシュグリッドを定義したGeoJSONファイル。

## 「ふくいdeお得クーポン」について

- [ふくいdeお得クーポンキャンペーン（公式サイト）](https://fukui-de-coupon.jp/)
- [キャンペーン再開のお知らせ（福井県）](https://www2.pref.fukui.lg.jp/press/view.php?cod=d76b8D167287688524&whence=72)

## データソース

参加店舗の基本データは、<a href=https://www.fukui-digital.co.jp/>株式会社ふくいのデジタル</a>のリストを基に、<a href=https://www.ftu-fukui.or.jp/>福井県観光連盟</a>および<a href=https://code4fukui.github.io/>Code for FUKUI</a>が提供したものです。

## 関連プロジェクト

- [福井県観光アンケート（福井県観光連盟）](https://code4fukui.github.io/fukui-kanko-stat/)

## ライセンス

MIT License — [LICENSE](LICENSE) を参照してください。
