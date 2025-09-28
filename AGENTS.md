# microBall ZMK）― 39キー 要件定義 & TODO一覧

このドキュメントは、これまでの合意内容を保存し、次回すぐに作業を再開できるようにするための **要件定義** と **TODO一覧** です。

## ✅ ゴール / コンテキスト
- 対象ハード: **microBall / moNa2**, 右手トラックボール付き分割, **39キー**
- ファーム: **ZMK**（QMKは参考。基本はZMK運用）
- 用途: **プログラミング中心**
- ユーザー嗜好: **テンキー派（数字入力）**, **矢印キー多用**, **右手片手でポインタ操作～クリック完結**
- 運用方針: まず **B) 通常の zmk-config（Fork→Actions→UF2）** で管理 → 迅速な試行が必要になったら **A) ZMK Studio** を上乗せ

## TODO
- [ ] 、。
- [ ] ドルマーク
- [ ] Arrow layer
  - [ ] 長押し、home+Window 移動
  - [ ] 矩形波選択
- [ ] 音量ボタン上下エンコーダ
- [ ] Bluetooth clear, all clearをhold tapへ
  - [ ] Function layerへの統合
  - [ ] https://chatgpt.com/share/68d78647-1c14-8013-8a78-d438abe9261c
- [ ] win切り替えエンコーダ

- [ ] スペース の連続入力

- [ ] ipad プロファイル top 
 - [ ] Ctrl -> win
- [ ] Lt, lt0の違い  
      https://chatgpt.com/share/68d7899f-17f8-8013-a5d0-93fb2f34af1a
- [ ] ipad arrow
  - [ ] Home,end -> alt+右左
  - [ ] window切り替え<>
  - [ ] Alt+tab alt->win
  - [ ] Drawer  
        https://chatgpt.com/share/68d78f56-5574-8013-97e3-3c6bb9e2b135
- [ ] ピンチイン、ピンチアウト

## directory
- look `config\microball.keymap`
