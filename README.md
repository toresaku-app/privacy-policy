# privacy-policy

アプリ「トレさく」のプライバシーポリシーと利用規約を公開するリポジトリ。

| ファイル | 公開URL |
|---|---|
| `index.html` | https://toresaku-app.github.io/privacy-policy/ |
| `terms.html` | https://toresaku-app.github.io/privacy-policy/terms.html |

GitHub Pages（main ブランチのルート）で配信している。push すると自動でビルドされる。

## 更新手順

本文の**原本はアプリ側のリポジトリ**にある。こちらは公開用のHTMLコピー。

1. `toresaku-app/web` の `docs/privacy-policy.md` / `docs/terms.md` を直す
2. その内容をこのリポジトリの `index.html` / `terms.html` に反映する
3. `最終更新日` と「改訂履歴」も忘れずに更新する

表記の慣習: 公開HTMLでは `iOSアプリ版` `Googleアナリティクス` のように、
英数字と日本語の間に半角スペースを入れない（原本のMarkdownとは異なる）。

## 注意

**実装を変えたら、公開が先か同時**にすること。過去に2回、実装が先行して
公開ページの記述と実態が食い違った期間が発生している。

- 2026年4月: Web版にGoogleアナリティクスを導入したが、ポリシーは
  「分析ツールを使用していません」のままだった（約4か月）
- 2026年8月: 発行者情報の端末内保存を追加したが、ポリシーは
  「タブを閉じると消去される」のままだった

いずれも「端末内で完結する／外部送信しない」という製品の柱に関わる記述なので、
実装とポリシーの整合はリリース前チェックに含める。
