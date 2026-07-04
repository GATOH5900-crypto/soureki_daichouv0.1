# 蒼暦台帳 (soureki_daichou)

創作世界の年表・年代記を管理するアプリ。HTML 1ファイルで完結し、iPhone のホーム画面に追加してアプリとして使えます。

## ファイル構成

| ファイル | 役割 |
|---|---|
| `index.html` | アプリ本体（これ1つで全部動く） |
| `apple-touch-icon.png` / `icon-512.png` | ホーム画面アイコン |
| `manifest.webmanifest` | アプリ情報（名前・アイコン・全画面表示） |
| `soureki_index` | 見本データ（JSON書き出しの例） |
| `.github/workflows/deploy-pages.yml` | GitHub Pages への自動公開 |

## iPhone でアプリとして使う

1. 公開された URL を **Safari** で開く
2. 共有ボタン（□に↑）→ **「ホーム画面に追加」**
3. ホーム画面のアイコンから起動（全画面のアプリとして開きます）

データは端末内に自動保存されます。設定画面から JSON で書き出し／読み込みもできます。
