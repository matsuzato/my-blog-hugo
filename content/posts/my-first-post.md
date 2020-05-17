---
title: "My First Post"
date: 2020-05-17T22:00:55+09:00
slug: my-first-post
summary: HUGOでBLOG始めたのでご挨拶
tags: [HUGO, Theme]
categories: [ news ]
---

## HUGOでBLOG始めました

Hugoのテーマって沢山ありますね。
https://themes.gohugo.io/

## HUGOサイトをNetlifyで公開してはまったところ

1. Netlifyに載せたら、CSSが反映されない

    baseURLの設定が間違い

2. Netlifyに載せたら、Postが反映されない

    .mdファイルの中で`draft: true`になってた（`hugo server -D`だとドラフトも表示される）

3. Netlifyに載せたら、ポストの`summarry`が反映されない

    `HUGO_VERSION = "0.70.0"` を netlify.toml で指定

## システム構成

すごく大雑把にはこんな感じ？

![system](./system-hugo.svg)

## 参考
- https://gohugo.io/getting-started/quick-start/
- https://knowledge.sakura.ad.jp/22908/
