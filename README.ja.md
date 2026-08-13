# Onsei Pages

[English](README.md) | 日本語

オンデバイス日本語音声合成アプリ「Onsei」の公開サイトです。アプリの紹介と、App Store配布に必要なサポート、プライバシー、法的情報を掲載します。

音声合成は端末上での実行を前提としており、必要なローカルリソースがそろった後は、プロジェクト独自の音声合成サーバーへ依存せずに日本語音声を生成できます。

## 公開ページ

- `index.html` — 製品紹介
- `support.html` — サポート情報
- `privacy.html` — プライバシーポリシー
- `terms.html` — 利用規約

## ローカルプレビュー

```bash
python3 -m http.server 8765
```

起動後、http://localhost:8765/ を開きます。
