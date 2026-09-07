# label-maker

PDFラベルメーカー — 個人利用向けの宛名ラベルPDF生成Webアプリケーション。

氏名・郵便番号・住所・会社名を入力すると、A4のラベル用紙レイアウトに合わせて配置したPDFを生成します。サーバーは使用せず、ブラウザ内で完結します。

詳しい仕様は [CLAUDE.md](./CLAUDE.md) を参照してください。

## 現在の状態

- **`mockup/index.html`**: UIとPDF生成ロジックを検証するための単一HTMLファイルのモックアップ。ブラウザで直接開いて動作確認できます。
- **`src/`**: React + Vite + TypeScriptによる本実装（現在進行中）。

## セットアップ

```bash
npm install
```

## 開発サーバーの起動

```bash
npm run dev
```

## ビルド

```bash
npm run build
```

## Lint

```bash
npm run lint
```
