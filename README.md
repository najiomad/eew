# 地震情報アプリ

この地震情報アプリは、地震データを表示するウェブアプリケーションです。現在のバージョンでは、地震の発生日時、震源の深さ、マグニチュード、最大震度のデータを提供します。

## 特徴

- 自動的に地震データを取得して表示します。
- ユーザーが地震データを手動で更新することもできます。

## 使用技術

- HTML（言語）
- CSS（言語）
- JavaScript（言語）
- jQuery（ライブラリ）
- SweetAlert2（エラーメッセージの表示のためのライブラリ）
- AJAX（地震データの取得のためのライブラリ）

## 使い方

1. [Vipelar Quake Info](https://vipelar.github.io/quake-info/) にアクセスするか、ソースコードをダウンロードして `index.html` を開く。
2. 地震情報が表示されます。
3. 地震データは手動で更新することができます。[手動更新]ボタンをクリックしてください。
4. 地震情報をご覧ください。表示されるデータは最新ではない可能性がありますのでご注意ください。

## クレジット

ライブラリ、フォント等をご提供くださった皆様に感謝いたします。
- 地震データは [nTool Earthquake API](https://ntool.online/apidoc/earthquakeapi) から取得されます。
- エラーメッセージの表示には SweetAlert2 ライブラリを使用しています。SweetAlert2に関する詳細な情報は [SweetAlert 2 のホームページ](https://sweetalert2.github.io/) を参照してください。
- フォントは [BIZ UDPGothic](https://fonts.google.com/specimen/BIZ%2BUDPGothic) を使用しています。
- リンク等で使用しているアイコンには [FontAwesome](https://fontawesome.com) を使用しています。
- データの取得にajaxを使用しています。詳細は [こちら](https://developer.mozilla.org/ja/docs/Web/Guide/AJAX) 。
- その他様々な処理に [jQuery](https://jquery.com/) を使用しています。

## 免責事項

このアプリケーションは地震データの提供を目的としていますが、データの正確性や完全性については保証できません。また、情報の更新が遅くなる可能性があります。正確で素早い地震情報の確認や被害状況の把握には、気象庁等の政府機関や関連機関が提供する情報を利用してください。

## ライセンス

このプロジェクトは MIT ライセンスのもとで公開されています。詳細については [LICENSE](LICENSE) ファイルを参照してください。

## その他

LICENSEファイルの正式版は英語、このREADMEファイルの正式版は日本語とし、それ以外の言語では効力を発揮しないものとします。

Copyright &copy; 2023 Vipelar. All rights Reserved.