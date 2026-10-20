# MTfirmLab 公式サイト

MTfirmLab のコーポレートサイト（静的HTML）です。

## ローカル確認

```bash
npx serve .
# または
python3 -m http.server 8080
```

ブラウザで `http://localhost:8080` を開いてください。

## Vercel へのデプロイ

1. [Vercel Dashboard](https://vercel.com/dashboard) で `mtfirmlab` プロジェクトを開く
2. このフォルダの内容を Git リポジトリに push するか、Vercel CLI でデプロイ

```bash
npx vercel --prod
```

## ファイル構成

- `index.html` — トップページ
- `privacy.html` — プライバシーポリシー
- `tokusho.html` — 特定商取引法に基づく表記
- `styles.css` — 共通スタイル
- `script.js` — モバイルメニュー等
- `images/hero-workspace.jpg` — トップヒーロー画像
