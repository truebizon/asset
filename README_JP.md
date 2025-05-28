# Droneport Server 日本語版 README

このリポジトリは、ドローンポート管理サーバのサンプル実装です。Spring Boot を用いた REST API と MQTT 連携機能を備えています。

## 利用手順
1. リポジトリをクローンします。
2. `droneport-server` ディレクトリで `./gradlew build` を実行してビルドします。
3. `./gradlew bootRun` でアプリケーションを起動します。

## ディレクトリ構成
- `droneport-server/` — Spring Boot アプリケーション本体
- `docs/` — UAV ポート操作 API の AsyncAPI 仕様書
- `README_A-1-5.md` —  詳細なセットアップ手順および環境変数の説明

その他の設定値は `src/main/resources/application*.yml` に記載されています。詳しくは `README_A-1-5.md` も参照してください。
