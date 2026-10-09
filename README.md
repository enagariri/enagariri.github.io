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
pendant.html   三姉妹の小さなペンダント紹介ページ
ehon.html      三姉妹の絵本ページ（ページをめくって読むおはなし）
stories.html   ehon.html への転送ページ（以前のURL用）
youtube.html   YouTube紹介ページ（最新動画の埋め込みつき）
style.css      デザイン（スマホ対応）
images/
  top.webp / top.jpg      トップの3匹そろった画像（1200px）
  riri.webp / riri.jpg    りりちゃん（640px）
  ruru.webp / ruru.jpg    るるちゃん（640px）
  rei.webp / rei.jpg      れいちゃん（640px）
  top-small.webp          フッター用の小さい画像
  ehon/                   絵本ページの画像（ららのき3枚・表紙。original/ に元画像）
  pendants/               ペンダント紹介の画像（riri / ruru / rei / rei-with-riri、各 .webp と .jpg）
    original/pendant-sisters-all.webp   4分割前の元画像（変更なし）
    original/pendant-sisters-christmas.webp   クリスマスのおはなしの元画像（変更なし）
    christmas.webp / christmas.jpg   クリスマスのおはなしの画像（1000px）
  favicon.png             ブラウザのタブに出るアイコン
.nojekyll      GitHub Pages で Jekyll 処理をしないための空ファイル
```

## カスタマイズ

- **絵本にページを足す**：`ehon.html` の `<section class="ehon-leaf">`（おはなしのページ）を1つコピーし、`id`・日付・見出し・画像・本文を書きかえて、「おしまいのページ」の前に追加します。ページの順番は、HTMLに書いた順番どおりです。

- **ペンダント紹介**：`pendant.html` 内、各 `<li class="pendant-card">` の `<h3>`（見出し）と `<p>`（説明文）、`alt` を書きかえるだけで変更できます。画像は `images/pendants/` の差し替えで更新します。

- **画像について**：表示を速くするため、元の画像（各2MB前後）をWebP形式（50〜200KB）に変換しています。WebPに対応していない古いブラウザ向けにJPEGも用意しています。元の画像はGitの履歴に残っています。

- **YouTubeの最新動画**：`youtube.html` の `data-channel-id=""` にチャンネルID（`UC` から始まる24文字）を入れると、アップロード動画の再生リスト（`UU…`）が埋め込まれ、新しい動画が自動で表示されます。未設定のあいだはチャンネルへのリンクが表示されます。

## GitHub Pages で公開する

1. リポジトリの **Settings → Pages** を開く
2. **Source** を「Deploy from a branch」にする
3. **Branch** で公開するブランチ（例：`main`）と `/ (root)` を選んで **Save**
4. 数分後に `https://<ユーザー名>.github.io/my-first-app/` で表示されます
