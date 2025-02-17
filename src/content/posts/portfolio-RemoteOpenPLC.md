---
title: OpenPLCの遠隔操作・監視用アプリ
published: 2025-02-16
description: 'Remote OpenPLCの紹介'
image: './image/RO.png'
tags: [個人開発, Python, Vue3]
category: 'portfolio'
draft: false 
lang: 'jp'
---
# 概要
- 個人開発、研究で使用するために開発
- OpenPLC Runtimeで制御しているマイコンを遠隔で制御・監視するためのアプリケーション

# 使用技術
- Python
- Vue3

# 機能面
- OpenPLC Runtimeで動作しているマイコンの観察したい項目を設定できる
- OpenPLC Runtimeで動作しているマイコンの観察・制御がWeb上でできる

# 開発のポイント
- OpenPLC Runtimeの遠隔制御・監視をするための通信（modbus通信）に関するリファレンス・ドキュメントを公式が用意していなかったので、リバースエンジニアリング等をして調べた
- 細かな機能（データのダウンロード、カメラの切り替え等）を実装した
- 保守・改良がしやすいように開発した


# 学んだこと・改善点
- リファレンス・ドキュメントが整備されていない状況での開発方法を学んだ
- [issue](https://github.com/ayano-yuki/Work-RemoteOpenPLC/issues/16)に改善点を書いた

# 外部リンク
::github{repo="ayano-yuki/Work-RemoteOpenPLC"}