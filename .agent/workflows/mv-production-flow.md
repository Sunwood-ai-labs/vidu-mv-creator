---
description: Vidu Q2を使用したMV制作の一連の流れ
---

# MV Production Workflow

このワークフローは、音楽ファイル（Audio）を起点に、Vidu Q2を使用して完全なミュージックビデオを作成する手順である。

## Step 1: 楽曲分析と構成 (Planning)
1. **BPM測定**: 曲のテンポ（BPM）を確認する。
2. **構成マップ作成**: 曲をセクションに分解する（Intro, Verse 1, Chorus, Outroなど）。
3. **尺計算**: 各セクションの秒数を出し、必要なカット数を算出する。
   - *Example*: サビが16秒なら、4秒クリップ x 4つが必要。

## Step 2: キービジュアル生成 (Visual Design)
1. **Character Reference**: 主人公の画像を作成。
   - 正面、高解像度、背景はシンプル推奨。
   -  のReference仕様を参照。
2. **Style Reference**: 画風の手本となる画像を作成。

## Step 3: シーン生成 (Video Generation via Vidu)
各セクションごとに動画を生成する。

### 3-1. Aメロ (Verse)
- プロンプト: 静かな動き、歌詞の世界観描写。
- ガイド: 

### 3-2. サビ (Chorus)
- プロンプト: ダイナミックなカメラワーク、エフェクト多用。
- ガイド: 

## Step 4: 編集と結合 (Assembly)
1. 生成された全クリップを収集。
2. 編集ソフト（Davinci Resolve, Premiere, または ffmpeg）に取り込み。
3. 音声波形に合わせてクリップを配置。
4. 色調整（Color Grading）を行い、統一感を高める。

## Step 5: 出力 (Export)
- 1080p, 60fps (if interpolated) or 24fps
- YouTube/SNS向けエンコード
