# Extended Dvorak Layout

## 目的

日本で選択肢が少ない英語キーボードのWindows PC環境に屈すること無く、それを逆手にとってよりよいキーボード環境を構築することを目的としています。また、GPD Pocketでのタイピング環境の改善も同様に考えています。

メリットとしては下記が上げられます。

1. Dvorakによるリズミカルなタイピング
2. 短いSPACEキーとその周辺キーと親指の有効利用
3. キーの多さを活かした中段（ホームポジション列）への左右CTRL配置（**JISキーボード**のみ）
4. CTRLキー以外のアルファベットキー入力における小指使用率の軽減（**Pinky-less Dvorak**のみ）
5. AutoHotKeyによるスペースキーに対するEandC（Enter and Ctrl）実装（**Pinky-less Dvorak**のみ）

## 配列の詳細
伝統的なDvorak配列と、このDvorak配列をベースにしつつ、小指の使用頻度を下げることを目的として現在検討中の「Pinky-less Dvorak」配列の2種類の配列があります。

**Normal Dvorak Layout**
![](https://github.com/tkrworks/ExtendedDvorakLayout/blob/master/JIS/ext-dvorak-4JIS.jpg)

**Pinky-less Dvorak Layout**
![](https://github.com/tkrworks/ExtendedDvorakLayout/blob/master/JIS/ext-pinkyless-dvorak-4JIS.jpg)

上記のキーボー画像は[keyboard-layout-editor.com](http://www.keyboard-layout-editor.com)で作成したものです。
上記サイトでこの画像を再現するjsonファイルも公開しています。

## GPD Pocketに関する考察
Pinky-less Dvorakを考案するきっかけになったGPD Pocketのちょっと特殊なキー配列に関する考察は、下記のQiita記事をご覧下さい。

* [GPD PocketにおけるDvorak使いのためのキー配列考察と実践](https://qiita.com/yamamo2/items/e6ce32fb92ef7a6a66a1)
* [GPD PocketのためにDvorak配列を考え直す](https://qiita.com/yamamo2/items/9ee9782196e8a5644baf#_reference-f21b2182da5513e0bb22)

## .regファイルを読み込む前に必要なこと
下記手順にて、キーボードレイアウトを英語キーボードに変更してください。

1. 「Windowsの設定」を開く
2. 「自国と言語」をクリック
3. 「地域と言語」をクリック
4. 「日本語」をクリックして表示される「オプション」をクリック。
5. 「ハードウェア キーボード レイアウト」を「英語キーボード（101/102キー）」に変更
6. ext-dvorak-4JIS.regをダブルクリックしてレジストリを変更
7. サインアウトしてサインインし直す

※当たりまですが、レジストリをいじるので自己責任でお願いします。
