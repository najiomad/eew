# 地震情報アプリ

この地震情報アプリは、地震データを表示するウェブアプリケーションです。現在のバージョンでは、地震の発生日時、震源の深さ、マグニチュード、最大震度のデータを提供します。

## 特徴

- 自動的に地震データを取得して表示します。
- ユーザーが地震データを手動で更新することもできます。

## 使用技術

- HTML（言語）
- CSS（言語）
- JavaScript（言語）
- jQuery（言語）
- SweetAlert2（エラーメッセージの表示のためのライブラリ）
- AJAX（地震データの取得のためのライブラリ）

## 使い方

1. [Vipelar Quake Info](https://vipelar.github.io/quake-info/) にアクセスするか、ソースコードをダウンロードして `index.html` を開く。
2. 地震情報が表示されます。
3. 地震データは手動で更新することができます。[手動更新]ボタンをクリックしてください。
4. 地震情報をご覧ください。表示されるデータはリアルタイムではない可能性がありますのでご注意ください。。

## API

地震データは以下のAPIから取得しています：

- [nTool Earthquake API](https://ntool.online/apidoc/earthquakeapi)

APIについての詳細な情報、ドキュメントは、上記のリンクを参照してください。

## ソースコードの構成

アプリのソースコードは以下のように構成されています：

- `index.html`：メインのファイルで、地震データが表示されます。また、データの取得や更新等の処理も含まれています。
- `style.css`：アプリのスタイルを定義するCSSファイルです。

## クレジット

- 地震データは [nTool Earthquake API](https://ntool.online/apidoc/earthquakeapi) から取得されます。
- エラーメッセージの表示には SweetAlert2 ライブラリを使用しています。SweetAlert2に関する詳細な情報は [SweetAlert 2 のホームページ](https://sweetalert2.github.io/) を参照してください。

## 免責事項

このアプリケーションは地震データの提供を目的としていますが、データの正確性や完全性については保証できません。また、情報の更新が遅いです。正確な地震情報の確認や被害状況の把握には、気象庁等の政府機関や関連機関が提供する情報を利用してください。

## ライセンス

このプロジェクトは MIT ライセンスのもとで公開されています。詳細については [LICENSE](LICENSE) ファイルを参照してください。

## その他

LICENSEファイルの正式版は英語、このREADMEファイルの正式版は日本語とし、それ以外の言語では効力を発揮しないものとします。

Copyright &copy; 2023 vipelar. All rights Reserved.