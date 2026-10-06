# さき｜Pythonで小さな自動化ツールを制作

Pythonを使った小規模なBot・API連携・データ保存の作品を公開しています。
入力を受け取り、条件に応じて処理し、保存したデータをCSVで確認できる実例を紹介します。

## 代表作品

### [MultiChannel Bot](https://github.com/rikka2525/multichannel-bot)

Discord・Telegramなどで共通の会話処理を利用するPython製Bot基盤です。
アンケートの評価・コメントをSQLiteに保存し、既存のローカルCLIで次の3列をCSVに書き出せます。

`rating`（評価） / `comment`（コメント） / `updated_at`（更新日時・UTC）

日本語を扱えるUTF-8（BOM付き）出力、識別子を含めない列選択、数式として解釈されやすい先頭文字への対策を実装しています。
[架空データのCSV完成例と再現手順](https://github.com/rikka2525/multichannel-bot/tree/main/examples/feedback-csv)

CSV機能は、このBotのアンケートDBから3列を書き出すものです。汎用CSVの重複除去・表記統一などは含みません。

### [Discord Price Alert Bot](https://github.com/rikka2525/discord-price-alert-bot)

外部APIから価格を取得し、登録した条件に応じてDiscordへ通知するPython製Botです。
API連携・定期監視・SQLiteによる設定保存の実装例を確認できます。売買機能はありません。

## 制作について

ここで紹介する作品は、AI支援を活用した自主制作のポートフォリオです。
有償案件の納品実績として掲載しているものではありません。
実装済みの機能と動作確認の範囲は、各リポジトリのREADMEに記載しています。

## ご相談

小規模なPythonツール、API連携、保存データのCSV出力について、目的・入力データ・必要な出力を伺い、対応できる範囲を確認します。

[CrowdWorksのプロフィール・相談先](https://crowdworks.jp/public/employees/6860530)
