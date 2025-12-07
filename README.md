# ラテンラジオ — 投票ページ

このリポジトリには、JAPAN PODCAST AWARDS 投票用の静的ページが含まれています。

ファイル一覧:

- `index.html` : 投票案内ページ（公開されるトップページ）
- `vote.html`  : 補助的な案内ページ

ローカルでプレビューする方法 (簡単):

```bash
# ワークスペースのルートで
python3 -m http.server 8000
# ブラウザで http://localhost:8000/ を開く
```

GitHub Pages で公開する手順:

1. 変更をコミットして `main` ブランチへ push します。

```bash
git add .
git commit -m "Add vote page and GitHub Pages workflow"
git push origin main
```

2. このリポジトリの `main` ブランチに push すると、`.github/workflows/deploy-pages.yml` が自動的に GitHub Pages にデプロイします。

3. 公開 URL の例: `https://<your-github-username>.github.io/latinradio/`（ユーザー名に合わせて置き換えてください）

もしリモート設定や push をこちらで行ってほしければ、教えてください。可能であれば代行で push します（認証が必要な場合があります）。
# latinradio
ラテンラジオのポットキャストアワード2025投票補助ページ
