# yatteikifm.github.io

https://yatteiki.fm のソースコード。

## 開発方法

### 事前準備

Docker をインストールしてください。本 README 執筆時点でバージョン 17.09 での動作を確認しています。

### 起動

以下のコマンドを実行してください。

```bash
docker-compose up
```

準備ができると http://localhost:4000 にアクセスできるようになります。

mp3 ファイルの容量が大きく、初回起動時のビルドに時間が掛かるため、注意してください。

## デプロイ方法

master ブランチに push することで、自動的に Web サイトに反映されます。
反映されるまでに、数十秒から数分程度掛かる場合があります。
