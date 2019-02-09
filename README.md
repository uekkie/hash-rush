# イベントのハッシュタグツイートを加速
イベントやカンファレンスで「このハッシュタグでつぶやいてください」とよく言われます。
参加できなかった人へ少しでも情報共有できればとおもうのですが、

- ハッシュタグが長い
- 打ち間違いが起きやすい

などの問題があります。
つぶやく回数に比例して、その手間が積み上がっていきます。
なんとかしたい。その想いでこのツールを作りました。

運営サイドがあらかじめQRコードを発行して、会場からカメラで読み取れる位置に投影しておくか、
配布資料の一部にコードを印刷しておくと、参加者は上記の悩みから解放され、運営側もつぶやきによるシェアを加速できます。

参考
- [QRを読みこんだらツイート画面が開くアレの作り方まとめ](https://matome.naver.jp/odai/2145647751444573301/2145647915746320903)

以下を自動化する。
- ハッシュ付きツイートを生成するURLをつくる
- メッセージ部分のエンコード（UTF8）
- QRコードをつくる

### アプリURL
https://hash-rush.herokuapp.com/
