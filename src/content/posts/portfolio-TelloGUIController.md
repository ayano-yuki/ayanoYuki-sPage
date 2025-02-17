---
title: 小型ドローンTelloをGUIで制御するアプリケーション
published: 2025-02-16
description: 'TelloGUIControllerの紹介'
image: ''
tags: [個人開発, Python]
category: 'portfolio'
draft: false 
lang: 'jp'
---
# 概要
- 個人開発
- 小型ドローンTelloをGUIで制御するアプリケーション
  - 通常操作、顔追跡、任意の色追跡

# 使用技術
- Python

# 機能面
- 通常操作モード
- 顔追跡モード
- 任意の色（プレイヤーが画面中の色を選択）の追跡モード

# 開発のポイント
- オブジェクト指向に基づいて開発した
- 任意の色を追跡するための追跡する色の範囲を設定する部分を工夫した
  - RGBではなく、HSVを使用した
