# エナガりりちゃん

シマエナガがモチーフの3姉妹、りりちゃん・るるちゃん・れいちゃんのキャラクターサイトです。

| キャラクター | 季節 | お花 |
| --- | --- | --- |
| りりちゃん（主人公） | 春 | すずらん |
| るるちゃん | 夏〜秋 | ルリマツリ |
| れいちゃん | 冬 | ロウバイ |

## ファイル構成

```
index.html     ページ本体（トップ／キャラクター紹介／ストーリー／SNS）
style.css      デザイン（スマホ対応）
images/
  trio.svg     トップの3匹そろった画像
  riri.svg     りりちゃん
  ruru.svg     るるちゃん
  rei.svg      れいちゃん
.nojekyll      GitHub Pages で Jekyll 処理をしないための空ファイル
```

## カスタマイズ

- **画像の差し替え**：`images/` に自作の画像（PNG/JPG など）を置き、`index.html` の `src="images/..."` を書き換えてください。
- **SNSリンク**：`index.html` の「SNSリンク」セクションにある `href` を実際のアカウントURLに書き換えてください。
- **ストーリー**：公開できるようになったら「ストーリー」セクションの「準備中」部分を書き換えてください。

## GitHub Pages で公開する

1. リポジトリの **Settings → Pages** を開く
2. **Source** を「Deploy from a branch」にする
3. **Branch** で公開するブランチ（例：`main`）と `/ (root)` を選んで **Save**
4. 数分後に `https://<ユーザー名>.github.io/my-first-app/` で表示されます
