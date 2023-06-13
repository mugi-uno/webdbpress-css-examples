# WEB+DB PRESS Vol.134 「乗りこなせ！モダンフロントエンド（第１回）」

WEB+DB PRESS Vol.134 掲載「乗りこなせ！モダンフロントエンド / 新機能で CSS の書き方が変わる？── 新たな擬似クラス、Cascade Layers、Container Queries」に含まれるソースコードの完全版です。

---

## 訂正

### `:has()` のサンプルの説明について

`:has()` 擬似クラスの解説内に次の記述があります。

> CSS ではフォーカス状態は:focus または:focus-visible 擬似クラスで判断できます。しかし:has()を用いない場合、CSS のみでは親に該当するセクションに対してスタイルを適用する方法はありません。

しかし、`:focus-within` 擬似クラスを利用することで同等のことが実現可能です。

[:focus-within - CSS: カスケーディングスタイルシート | MDN](https://developer.mozilla.org/ja/docs/Web/CSS/:focus-within)

記事内で紹介した `:has()` を用いる方法でも可能ですが、`:focus-within` もモダンブラウザであれば利用可能ですので、併せてご確認頂ければと思います。
