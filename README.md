# やましろ街事典

Hugo と Decap CMS を学ぶための最小構成です。

## 使うファイル

- `site/content/_index.md`: トップページ
- `site/content/posts/`: 記事
- `site/layouts/`: Hugo テンプレート
- `site/static/admin/index.html`: Decap CMS の管理画面
- `site/static/admin/config.yml`: Decap CMS の編集項目

## ローカル起動

```sh
npm run start
```

サイトは `http://localhost:1313/`、CMS は `http://localhost:1313/admin/` で確認できます。

ローカルで Decap CMS から保存まで試す場合は、別ターミナルで Decap のローカルバックエンドを起動します。

```sh
npx decap-server
```

## ビルド

```sh
npm run build
```
