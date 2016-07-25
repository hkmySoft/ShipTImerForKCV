ShipTimerForKCV
======================
[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/hkmySoft/ShipTimerForKCV/master/LICENSE)
<!--[![Release]()]()-->

iPhone版「[艦これタイマー](https://itunes.apple.com/jp/app/shiptimer/id684642180?l=ja&ls=1&mt=8)」に遠征・入渠・建造時間を自動セットする  
[KanColleViewer](http://grabacr.net/kancolleviewer)用プラグインです。

## 機能
* 遠征・入渠・建造の完了時間をiPhone版「[艦これタイマー](https://itunes.apple.com/jp/app/shiptimer/id684642180?l=ja&ls=1&mt=8)」に自動連携します。
* 連携する項目は設定にて変更可能です。  

## 必要動作環境

##### KanColleViewer （提督業も忙しい！）
* **[Ver 4.6](http://grabacr.net/kancolleviewer)** 以降
* その他 動作環境は KanColleViewer に準拠します。

##### iPhone版 艦これタイマー （艦Colleタイマー for 艦これ）
* **[Ver 10.0](https://itunes.apple.com/jp/app/shiptimer/id684642180?l=ja&ls=1&mt=8)** 以降
* iOS 7 以上

##### その他
* Googleアカウント(デバイス認証に使用します)  

## インストール

* "ShipTimerForKCV.dll"をKanColleViewerの"Plugins"ディレクトリに移動してください。
* 以下のDLLを **すべて** KanColleViewer.exeと同じディレクトリに移動してください。(一つでも足りないと動作しません。)
 * AWSSDK.dll
 * BouncyCastle.Crypto.dll
 * Google.Apis.Auth.dll
 * Google.Apis.Auth.PlatformServices.dll
 * Google.Apis.Core.dll
 * Google.Apis.dll
 * Google.Apis.PlatformServices.dll
 * Google.Apis.Plus.v1.dll
 * Newtonsoft.Json.dll
 * Zlib.Portable.dll  

## 使い方
**必ず先にiPhone側の操作を完了させてください**
1. iPhone版「艦これタイマー」で「その他＞設定＞コンシェルジュ」を選択  
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/3/7/37721b55.png" width="180" height="320" border="0" alt="HowToUse_01" />
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/e/a/ea7e3901.png" width="180" height="320" border="0" alt="HowToUse_02" />

1. 説明を読んで「デバイス認証」のページで「Sign in」を選択  
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/5/3/5338a889.png" width="180" height="320" border="0" alt="HowToUse_03" />

1. 表示された画面で「許可」を選択  
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/3/4/340bfcb4.png" width="180" height="320" border="0" alt="HowToUse_04" />

1. 「デバイス認証完了」と表示されたらiPhone側の操作は完了です。  
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/b/5/b535057b.png" width="180" height="320" border="0" alt="HowToUse_05" />

1. 「提督業も忙しい！」を起動して「ツール＞艦これタイマー」を選択  
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/a/1/a14baa3e.png" width="356" height="434" border="0" alt="HowToUse_10" />

1. 「デバイス認証」を選択  
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/e/4/e4570a7e.png" width="250" height="217" border="0" alt="HowToUse_11" />

1. ブラウザが立ち上がるので「許可」を選択  
※ブラウザの立ち上げに失敗した場合は「デバイス認証失敗」となるので再度ボタンを押してください。  
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/5/f/5fa4d35f.png" width="250" height="217" border="0" alt="HowToUse_12" />

1. ブラウザを閉じます。自動で閉じられません。  

1. 「デバイス認証完了」と表示されたら設定は完了です。  
<img src="http://livedoor.blogimg.jp/opu_50yen/imgs/4/b/4bf63dfa.png" width="356" height="434" border="0" alt="HowToUse_13" />

## 免責事項
* 事前通知なしにサービスを止めることがあります。
* 「認証できません」「タイマーが反映されません」「やり方がわかりません」の漠然とした問い合わせはお答えできません。
* 『バックグラウンド更新ON』によるバッテリーの消費はどうしようもないです。
* **当プログラムを使用したことによる損害等は補償できません。自己責任でお願いいたします**


## ライセンス

* [The MIT License (MIT)](LICENSE)  


## ダウンロード

 [ShipTimerForKCV - GitHub Releases Page]()  



## お問い合わせ/機能要望/バグ報告
- Twitterから
 - [twitter.com/Kozeni_50yen](https://twitter.com/Kozeni_50yen)
- GitHubから
 - [github.com/hkmySoft/ShipTimerForKCV/issues/new](https://github.com/hkmySoft/ShipTimerForKCV/issues/new)  



## 使用ライブラリ

以下のライブラリを使用して開発を行っています。

#### [KanColleViewer](https://github.com/Grabacr07/KanColleViewer)

> The MIT License (MIT)
>
> Copyright (c) 2013 Grabacr07

* **ライセンス :** The MIT License (MIT)
* **ライセンス全文 :** [licenses/KanColleViewer.txt](licenses/KanColleViewer.txt)

#### [MetroRadiance](https://github.com/Grabacr07/MetroRadiance)

> The MIT License (MIT)
>
> Copyright (c) 2014 Manato KAMEYA

* **ライセンス :** The MIT License (MIT)
* **ライセンス全文 :** [licenses/MetroRadiance.txt](licenses/MetroRadiance.txt)

#### [Livet](http://ugaya40.hateblo.jp/entry/Livet)

* **ライセンス :** zlib/libpng

#### [Rx (Reactive Extensions)](https://rx.codeplex.com/)

* **ライセンス :** Apache License Version 2.0
* **ライセンス全文 :** [licenses/ApacheLicense2.0.txt](licenses/ApacheLicense2.0.txt)

#### [StatefulModel](http://ugaya40.hateblo.jp/entry/StatefulModel)

> The MIT License (MIT)
>
> Copyright (c) 2015 Masanori Onoue

* **ライセンス :** The MIT License (MIT)
* **ライセンス全文 :** [licenses/StatefulModel.txt](licenses/StatefulModel.txt)


#### [AWS SDK for .NET](https://aws.amazon.com/jp/sdk-for-net/)

* **ライセンス :** Apache License 2.0
* **ライセンス全文 :** [licenses/ApacheLicense2.0.txt](licenses/ApacheLicense2.0.txt)

#### [Google APIs from .NET](https://developers.google.com/api-client-library/dotnet/)

* **ライセンス :** Apache License 2.0
* **ライセンス全文 :** [licenses/ApacheLicense2.0.txt](licenses/ApacheLicense2.0.txt)
