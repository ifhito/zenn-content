# Zennの記事

記事の原稿は `articles/` で管理します。
BurgerStackの比較記事は `articles/burgerstack-free-deploy-comparison.md` です。
今後はこちらを直接編集します。

## ローカルで確認する

```sh
npm ci
npm run preview
```

http://localhost:8000 でプレビューできます。
ポートが使われている場合は `npm run preview -- --port 8001` で変更できます。

## Zennとの連携

[ZennのGitHub連携設定](https://zenn.dev/dashboard/deploys)で
`ifhito/zenn-content` の `main` ブランチを登録します。
[公式手順](https://zenn.dev/zenn/articles/connect-to-github)も参照してください。

連携後は `main` にpushすると記事が同期されます。
`published: false` は下書き、`published: true` は公開です。
公開するまでは `false` のまま編集してください。
