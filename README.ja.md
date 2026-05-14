# event_fukui

福井県で開催される今後のイベントを表示する、シンプルなシングルページWebアプリケーションです。

## デモ

**https://github.com/code4fukui/event_fukui

> 本アプリケーションは、イベントカードをレスポンシブなグリッドで表示します。各カードには16:9のイベント画像が配置され、その下にイベントの日時とタイトルが続きます。

## 機能

- **イベントグリッド:** デスクトップとモバイルの両方に適した、すっきりと見やすいレスポンシブなカードベースのグリッドでイベントを表示します。
- **自動フィルタリング:** イベントの全リストを取得し、今後のイベントのみを自動的に表示します。
- **直接リンク:** 各イベントカードから、詳細が記載された情報元のページへ直接リンクします。
- **軽量:** バニラHTML、CSS、JavaScriptモジュールで構築されています。ビルドステップや外部フレームワークは不要です。

## ローカルでの実行

本プロジェクトはESモジュールを使用しているため、正しく動作させるにはローカルWebサーバー上で実行する必要があります。

1. リポジトリをクローンします:
    ```sh
    git clone https://github.com/code4fukui/event_fukui.git
    ```
2. プロジェクトディレクトリに移動します:
    ```sh
    cd event_fukui
    ```
3. シンプルなローカルサーバーを起動します（例: Python 3を使用）:
    ```sh
    python -m http.server
    ```
4. ブラウザを開き、`http://localhost:8000` にアクセスします。

## データソース

イベントデータは、GitHub Pagesでホストされている公開CSVファイルから取得しています。

- **CSV URL:** https://code4fukui.github.io/event_fukui_data/data/event_fukui.csv
- **データリポジトリ:** [code4fukui/event_fukui_data](https://github.com/code4fukui/event_fukui_data)

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
