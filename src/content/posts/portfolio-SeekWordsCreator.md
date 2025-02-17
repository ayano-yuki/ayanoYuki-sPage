---
title: 特定のワードを用いたシークワーズを生成するアプリ
published: 2025-02-16
description: 'SeekWordsCreatorの紹介'
image: './image/SCW.png'
tags: [個人開発, Python, Vue3]
category: 'portfolio'
draft: false 
lang: 'jp'
---
# 概要
- 個人開発
- 失語症患者のためのリハビリテーション教材として期待される「シークワーズ」を生成するアプリ

# 使用技術
- Python
- Vye3
- Vercel
- Render

# 機能面
- シークワーズのサイズの可変（7×7～9×9）
- 指定したテーマ（ファイル）の解答を必ず含める
  - 文字数は2文字から5文字
  - 文字の並びは単語の先頭から縦・横・斜めの全方向で、途中で折り曲がらない
- 生成したシークワーズをPDFでダウンロードできるようにする
- Web公開する環境構築(Vercel、Render)
  - https://work-seek-words-creator.vercel.app/

# 開発のポイント
- セキュリティを意識して開発した
  - バッファオーバーフロー、ディレクトリトラバーサル、HTTPレスポンス分割等を対策
  - 型安全になるように開発
- 形態素解析をするライブラリを吟味し、Mecabを採用した
- シークワーズの問題と解答を別々にダウンロードできるようにした
- アプリケーションをデプロイし、情報技術に詳しくない方でも扱えるようにした


# 改善点
- 単語の選定もWebアプリケーション内で行えるようにして、作成した問題を投稿、挑戦ができるプラットフォーム化を行う
- 作成したシークワーズに挑戦する際に、ヒントや解答の表示の有無等の難易度を変更できるようにする

# 外部リンク
- Zenn：[【ポートフォリオ】SeekWords Creator](https://zenn.dev/yuki_ayano/articles/portfolio-seekwords_creator)

::github{repo="ayano-yuki/Work-SeekWordsCreator"}