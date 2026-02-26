# hfe-site

HandsFree English 用の GitHub Pages 公開サイト。

## ページ構成（URL設計）

GitHub Pages（Project Pages）前提で、以下の固定ページを公開する。

- `/` : ランディング（アプリ概要・主要リンク）
- `/support/` : サポート窓口
- `/privacy-policy/` : プライバシーポリシー

## 追加候補（必要になったら）

- `/terms/` : 利用規約
- `/contact/` : 問い合わせフォーム/連絡先

## 実装方針

- すべて静的HTML（必要に応じてCSSを共通化）
- 各ページはディレクトリ + `index.html` で作成
- 例: `support/index.html`, `privacy-policy/index.html`

## GitHub Pages 公開手順

1. このリポジトリを GitHub に push する（`main` ブランチ）
2. GitHub の `Settings > Pages` を開く
3. `Source` を `GitHub Actions` にする
4. `Deploy GitHub Pages` ワークフローが成功したら公開完了

公開URL（Project Pages）:

- `https://<GitHubユーザー名>.github.io/hfe-site/`
- `https://<GitHubユーザー名>.github.io/hfe-site/support/`
- `https://<GitHubユーザー名>.github.io/hfe-site/privacy-policy/`
