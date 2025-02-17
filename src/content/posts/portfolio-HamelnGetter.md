---
title: WEB小説投稿サイトハーメルンの小説に関するプログラム
published: 2025-02-16
description: 'ハーメルン小説更新Gettterの紹介'
image: ''
tags: [個人開発, OSS, Python]
category: 'portfolio'
draft: false 
lang: 'jp'
---
# 概要
- 個人開発
- 小説投稿サイト「ハーメルン」の作品のダウンロード・更新確認を行うプログラム
- 私以外の方もプログラムの更新をしているので、OSSみたいになっている

# 使用技術
- Python
  - スクレイピングの実装が簡易に行えるため使用した

# 機能面
- DBに新規小説情報を追加する
- DBにある小説の更新情報を調べ、ダウンロードタスクを Rasiel.csv に保存する
- DBに記述している小説をtxt形式でダウンロードする

# 開発のポイント
- 初めて作成したアプリ？なので、変数の命名や、Python特有の記法に気を使い、誰でも読めるようにした

# 改善点
- 今はCUIなので、デスクトップアプリ化をしたい

# 外部リンク
::github{repo="ayano-yuki/Work-HamelnGetter"}