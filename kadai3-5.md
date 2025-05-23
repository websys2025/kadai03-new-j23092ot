## 自動販売機（データ構造と各種処理）のミニレポート
### Q5-1. 自動販売機の商品データついて説明せよ。
* データ構造（各項目とその説明）
 *idは商品番号　nameは商品名　priceは金額　stockは在庫数 
* 連想配列の配列として定義するメリット
 *キーが文字列のため、何の情報なのかわかりやすい 
### Q5-2. showItemListの処理内容について説明せよ。
* 配列の繰り返し処理
  *商品番号、商品名、金額、在庫数を表示する
* 連想配列の参照方法
  *items[i].id など　配列名[i].要素名で配列のi番目の要素を取り出すことができる
### Q5-3. buyItemの処理内容について説明せよ。
* 商品購入の可否判定
  *itemsのstockの値を確認し、0ならば、在庫がありませんと表示する 
* 商品在庫を減らす処理
  *itemsのstockの値を確認し、0より大きいならば、stockの値を減らす
* 商品番号のエラー処理
  * 現在登録されている番号以外の番号が引数となった場合エラー文を呼び出す。
### Q5-4. プログラムの考察
* データ構造について
 * 商品一覧表示と購入処理が関数になっており、データは連想配列に格納されている
* 商品一覧表示と購入処理を関数化したメリット
 * 商品を一覧表示するときに商品が増えたときにも対応でき、大量のデータを一文で呼び出すことができる。購入処理も関数を呼び出すだけで、在庫を管理することができる。
### Q5-5. 感想
* 今回の課題で苦労したこと
 *配列の指定の要素数を取り出すやり方が分からず、苦労しました。 
* 演習を通して理解できたこと
 *連想配列の使い方を理解できました。 
* この自動販売機プログラムの追加機能や課題など
 *金額の要素をつかっていないので、自動販売機に入った金額とお釣りを計算する機能があればよいと思います。 
