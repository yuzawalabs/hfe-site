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
