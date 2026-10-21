# S Apps(サップス)

講義と講演のための、フリーのブラウザアプリ集「S Apps」の紹介ページです。

公開先: https://sapp.jp

アプリの一覧と、各アプリの公開先・ソースへのリンクは、紹介ページにあります。

## ファイル

| パス | 内容 |
|---|---|
| `index.html` | 紹介ページ本体(外部のファイルやサービスは読み込みません) |
| `images/` | 各アプリの画面写真(`*.webp`)と、SNS などで共有されたときの画像(`og.png`) |
| `CNAME` | GitHub Pages の独自ドメインの設定(`sapp.jp`) |

## アプリを足すとき

1. `index.html` のカード(`<article class="app">` から `</article>` まで)を 1 枚コピーし、名前・説明・リンク先を書き換える。
2. 生成 AI 対応のアプリは、名前の後ろに ★ を付け、プロンプトの欄(`<div class="ai">`)も入れる。
3. 画面写真を幅 960 × 高さ 513 px 前後の WebP にして `images/` に置く。

## ライセンス

紹介ページ(`index.html` と `images/` の画像)は MIT License です。
ただし、`images/slide.webp` と `images/og.png` に写っているシンプルスライドの配色「えんじ」のデザインは CC BY-NC-ND 4.0(Copyright (c) Yuka Hiratsuka)で、MIT License の対象外です。
詳しくは `LICENSE` を参照してください。
