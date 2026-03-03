# Design Fee Live Estimate

GitHub Pages で公開するための最小構成です。

## 公開手順

1. このフォルダを GitHub リポジトリに push する
2. GitHub の `Settings` -> `Pages` を開く
3. `Build and deployment` の `Source` を `GitHub Actions` にする
4. `main` ブランチへ push すると、自動で公開される

## 公開URL

通常は以下の形式です。

`https://<GitHubユーザー名>.github.io/<リポジトリ名>/`

## ファイル構成

- `index.html`: アプリ本体
- `price_table.csv`: 料金マスター
- `.github/workflows/deploy-pages.yml`: Pages 自動デプロイ設定
