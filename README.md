# kantansimple

個人開発アプリの宣伝サイト。`public/` の中身が公開されます。

## 多言語対応（日本語・英語）
- 日本語ページ: `public/` 直下（例: `public/timecard/index.html`）
- 英語ページ: `public/en/` 以下に同じ構成で配置（例: `public/en/timecard/index.html`）
- ページを追加・変更したら、日本語・英語の両方を更新し、各ページの `hreflang` と `sitemap.xml` も合わせて追加する
- 左上の言語切替（`.lang-switch`）は、同じ内容の相手言語ページへリンクする
