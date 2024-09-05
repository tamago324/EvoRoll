# EvoRoll

左側を haqua34、右側を EvoRoll として使うことを想定している

> NOTE: KiCad 7 を使用しています

![](./assets/main_pic.JPEG)



## 特徴

* GameBall のボールを使用したトラックボール付きキーボード
* マウスキーが独立している
* [monkeypad/pmw3360-breakout](https://github.com/monkeypad/pmw3360-breakout) を使用

## 部品

|部品|リンク|備考|
|---|---|---|
|PMW3360ブレークアウトボード|[monkeypad/pmw3360-breakout](https://github.com/monkeypad/pmw3360-breakout)|Booth で購入したら、ピンヘッダーもついていたけど、おそらく[これ](https://www.hirosugi-net.co.jp/shop/c/c12103211/)|
|ピンソケット 8ピン|https://www.hirosugi-net.co.jp/shop/c/c12111211/|FSR-41085-08 / 8.5mmのものを使用する|
|スペーサー M2 5mm|https://www.hirosugi-net.co.jp/shop/c/c10141012/|トッププレートとボトムプレートを止めるために使用する|
|ねじ M2 3mm|https://wilco.jp/products/F/FX-EB.html#page3|トッププレートとボトムプレートを止めるために使用する|
|タッピングネジ M2 8mm|https://wilco.jp/products/F/FPP-N.html|FPP-0000N / ボトムプレートとボールケースを止めるために使用する。JLCPCBのレジンに使えるタッピングネジ|
|RP2040-Zero|||
|ダイオード|||
|chocソケット|||
|TRRSソケット|||


### ボールケース関連

ボールケースは [trackmacro](https://github.com/tamago324/trackmacro/tree/main/stl) のケースを使用している

|部品|リンク|備考|
|---|---|---|
|ベアリング|https://amzn.asia/d/8OED4Yl|DDL-520ZZW52 / 内径2mm、外形5mm、幅2.5mm|
|ねじ M2 8mm||なべ小ねじならなんでもOK (頭径3.5mm、高さ1.3)|
|ナット M2||1種のナットを使っている|
|磁石 3x2mm|https://amzn.asia/d/gBrgy0N|ボールケースの上下に瞬間接着剤 (アロンアルフア EXTRA 速効多用途) でつけている|


## 3Dプリント

* JLCPCB の3Dプリントを使う想定
* stl 内の stl ファイルを SLA(Resin) で発注する


## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">クリエイティブ・コモンズ 表示 - 非営利 4.0 国際 ライセンス</a>の下に提供されています。

> 表示 — あなたは 適切なクレジットを表示し、ライセンスへのリンクを提供し、変更があったらその旨を示さなければなりません。これらは合理的であればどのような方法で行っても構いませんが、許諾者があなたやあなたの利用行為を支持していると示唆するような方法は除きます。
>
> 非営利 — あなたは営利目的でこの資料を利用してはなりません。