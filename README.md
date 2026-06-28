> [!IMPORTANT]
> https://luciy-scratch.github.io/Warframe_Prime-Relics-Search/ で公開中です

# Warframe_Prime-Relics-Search
任意のPrimeアイテム(Voidレリックが存在するフレーム/武器に限る)について、抽選可能性のあるレリックを"パーツ・設計図"と"抽選確率"で分類してテーブル形式で表示します。

---

## データリソース
DEが公開しているドロップテーブル[^1]…を解析してjson形式のデータで公開している **Warframe Drop Data**[^2] さんを利用しています。
サイトへのアクセス時にアクセスユーザー側でjsonデータをダウンロードしてデータリソースとして利用しています。
短時間に何十回もページやデータの更新を行うとデータリソース側に負担を掛けることになりますのでご注意ください。

## 実装機能
- ドロップテーブルのjsonデータを取得する機能
- 取得したjsonデータの解析機能
- 検索対象のPrimeアイテムの構成要素(パーツ・設計図)をドロップテーブルの抽選アイテムデータから抽出する機能
- 検索対象の構成要素とレリックからの抽選割合でXY軸で分類してレリック名称を表示する機能
- 完了した検索結果をpngファイル形式で出力する機能

[^1]: https://warframe-web-assets.nyc3.cdn.digitaloceanspaces.com/uploads/cms/hnfvc0o3jnfvc873njb03enrf56.html
[^2]: https://drops.warframestat.us