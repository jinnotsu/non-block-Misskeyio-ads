# Non-block Misskey.io Ads

<h3 align="center"><a href="abp:subscribe?location=https://raw.githubusercontent.com/jinnotsu/non-block-Misskeyio-ads/main/nonblock.txt&amp;title=Non-block%20Misskey.io%20Ads">フィルタを購読する(Brave非対応)</a></h3>
<h3 align="center"><a href=https://github.com/jinnotsu/non-block-Misskeyio-ads/blob/main/README.md#Braveで購読する>Braveでフィルタを購読する方法</a></h3>

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

### Braveで購読する

1. [brave://adblock](brave://adblock)を開く
2. 「URLを使用してフィルターリストを追加」を押して以下をコピペする
```
https://raw.githubusercontent.com/jinnotsu/non-block-Misskeyio-ads/main/nonblock.txt
```
