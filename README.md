# エナガりりちゃん

シマエナガがモチーフの3姉妹、りりちゃん・るるちゃん・れいちゃんのキャラクターサイトです。

| キャラクター | 季節 | お花 |
| --- | --- | --- |
| りりちゃん（主人公・お姉ちゃん） | 春 | スズラン |
| るるちゃん（妹） | 夏〜秋 | ルリマツリ |
| れいちゃん（末っ子） | 冬 | ロウバイ |

## ファイル構成

```
index.html     ページ本体（トップ／キャラクター紹介／ストーリー／SNS）
style.css      デザイン（スマホ対応）
images/
  top.webp / top.jpg      トップの3匹そろった画像（1200px）
  riri.webp / riri.jpg    りりちゃん（640px）
  ruru.webp / ruru.jpg    るるちゃん（640px）
  rei.webp / rei.jpg      れいちゃん（640px）
  top-small.webp          フッター用の小さい画像
  favicon.png             ブラウザのタブに出るアイコン
.nojekyll      GitHub Pages で Jekyll 処理をしないための空ファイル
```

## カスタマイズ

- **画像について**：表示を速くするため、元の画像（各2MB前後）をWebP形式（50〜200KB）に変換しています。WebPに対応していない古いブラウザ向けにJPEGも用意しています。元の画像はGitの履歴に残っています。

## GitHub Pages で公開する

1. リポジトリの **Settings → Pages** を開く
2. **Source** を「Deploy from a branch」にする
3. **Branch** で公開するブランチ（例：`main`）と `/ (root)` を選んで **Save**
4. 数分後に `https://<ユーザー名>.github.io/my-first-app/` で表示されます
