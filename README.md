# home

This is a minimal repo.

## GitHub Pagesで公開する

- このリポジトリは `index.html` をルートに配置しています。mainブランチにpushすると自動でPagesにデプロイされるよう、Actionsワークフローを追加しました。
- 自動デプロイのワークフロー: [.github/workflows/pages.yml](.github/workflows/pages.yml)
- Jekyll処理を無効化するために `.nojekyll` をルートに追加しています。

公開URLはリポジトリのSettings → Pagesで確認できます。必要であればカスタムドメイン（CNAME）を設定してください。

---

その他（ローカルでの確認）:

```bash
# 簡易サーバーで確認（Python 3）
python -m http.server 8000
# ブラウザで http://localhost:8000 を開く
```
# test