Safari-Hiragino Gothic
======================
Safari 6.0でデフォルトフォントの指定が消えてしまい、明朝体が出てくるのがイヤなので
強制的にヒラギノ丸ゴシックを適用するSafari 機能拡張です。
  
使い方
------
### 機能拡張の作り方 ###
- Safariの開発メニューから「機能拡張ビルダー」を開きます
- 左下の「＋」を押し「機能拡張を追加」を選択しエクスポートしたフォルダーを指定します。

※パッケージをビルドするにはSafariの開発署名が必要です
 
### CSSの内容 ###
    body {
      font-family: 'Hiragino Maru Gothic Pro';
    }
  
関連情報
--------
1. [べるべる研究日誌　Safari6の標準フォントを丸ゴシックにする機能拡張](http://d.hatena.ne.jp/bellx2/20120727/p1 "べるべる研究日誌")
   
ライセンス
----------
Copyright &copy; 2012 Bellx2
Distributed under the [MIT License][mit].

[MIT]: http://www.opensource.org/licenses/mit-license.php
