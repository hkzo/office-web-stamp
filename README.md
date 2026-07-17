# 概要

このディレクトリの内容は、Excel 用 Web Stamp Add-in のビルド後成果物として配布される想定です。

## 公開 URL

GitHub Pages で公開する場合の想定 URL は次のとおりです。

```text
https://hkzo.github.io/office-web-stamp/manifest.xml
```

## 注意事項

- `npm run build` により `dist/` へ production 用成果物が生成されます。
- `dist/manifest.xml` では `https://localhost:3000` が production URL に置換されます。
- production URL を変更する場合は、管理元の `webpack.config.js` を変更して再ビルドしてください。
