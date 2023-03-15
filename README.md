# Non-block Misskey.io Ads

### 購読する

フィルターURL
```
https://raw.githubusercontent.com/jinnotsu/non-block-Misskeyio-ads/main/nonblock.txt
```

#### Braveで購読する
1. `brave://adblock`を開く
2. 「URLを使用してフィルターリストを追加」を押してURLをコピペする

### what

広告ブロッカーでブロックされるMisskey.io上の広告を表示するフィルターです。
既存のフィルターに上書きして表示（許可）させるようにしてます。

スマホの場合いちいち手動で更新するのがめんどくさいのでつくった！！！

### 動作確認

* uBlock
* Brave Android

それ以外の環境は確認してません。

### 方針

* Misskeyが提供している広告だけを表示させる
* アクセス解析は無視
* [csp-reports](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/report-to)は無視
* 外部サイトのスクリプトやファイルは無視
* 自分用のためは気づいたら更新する
