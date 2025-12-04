# udemy-web-design0

<https://www.udemy.com/course/web_design0/>

## 技術スタック

- HTML
- [Tailwind CSS](https://tailwindcss.com/)

## 開発

### 依存関係のインストール

```bash
npm install
```

### 開発サーバーの起動

CSSの変更を監視し、自動的にビルドします。

```bash
npm run dev
```

### 本番用のビルド

CSSを圧縮してビルドします。

```bash
npm run build
```

### フォーマット

[Biome](https://biomejs.dev/) を使ってコードをフォーマットします。

```bash
npm run format
```

## プレビュー

`src/index.html` をブラウザで開いてください。
正しく表示するためには、事前に `npm run build` を実行して `dist/output.css` を生成しておく必要があります。
