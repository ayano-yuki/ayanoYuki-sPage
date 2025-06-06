---
title: ポケらぶ
published: 2025-05-05
description: 'ポケモンと付き合うことを目指すクイズゲーム'
image: ''
tags: [チーム開発, React, Vite, V0]
category: 'portfolio'
draft: false 
lang: 'jp'
---
# 概要
- チーム開発
  - チームリーダー、フロントエンド担当
- ポケモンと付き合うことを目指すクイズゲーム

# 使用技術
- React
  - チームメンバーの技術スタックに合わせるために使用した
- Vite
  - Reactの開発環境を構築するために使用した
- V0
  - 3時間での開発を求められるハッカソンだったので、プロトタイプの実装に使用した

# 機能面
1. ポケモンのランダム取得
    - https://pokeapi.co/api/v2/pokemon/ API からランダムに1体のポケモンを取得し、画像と名前を表示。
2. クイズ機能
    - あらかじめ定義された13問のポケモンクイズに1問ずつ回答。
    - 正解すると「なつきど」が+30、不正解だと-30。
3. なつきど（親密度）メーター
    - 親密度は0〜100で表示。
    - 色で状態を可視化（緑：親密、高→赤：警戒、低）。
    - 親密度に応じたポケモンの状態メッセージ（例：「なついている」「なつかない...」など）も表示。
4. アニメーションとフィードバック
    - 回答ごとにフィードバック表示（「正解！」「不正解…」）とアニメーション（画像が一瞬拡大）。
5. ゲーム終了とリセット
    - 全問題を終えるとゲーム終了。
    - 「戻る」ボタンでリセット（window.location.reload()を使用）。
6. UI設計（CSS-in-JS）
    - React内に直接インラインスタイルを記述して、簡易UI設計。
    - モバイルにも優しい縦型レイアウト。

# 開発のポイント
- 短時間での開発を求められるハッカソンだったので、v0でプロトタイプを開発し、その後それを基にモブプログラミングを行った
- 短時間での開発だったので、実装する機能を絞った

# デモ・スクリーンショット
<img src="https://github.com/ayano-yuki/Work-PokeLove/blob/main/.img/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202025-05-05%20212510.png?raw=true" width="200px" />

# 改善点
- ポケモンが初代の151匹なので、最新のポケモンとも恋愛を出来るようにする
- クイズの出題パターンを完全ランダム化する
- 「なつき度」の上下に波をつける
- 付き合えたポケモンを表示する

# 外部リンク
::github{repo="ayano-yuki/Work-PokeLove"}