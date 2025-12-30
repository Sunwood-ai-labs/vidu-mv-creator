---
description: 歌詞と楽曲を元に、リファレンス画像を駆使してVidu Q2でMVを構築する統合フロー
---

# Lyrics to MV Integration Workflow

楽曲（Lyrics/Audio）から、Vidu Q2を使用してMVを完成させる統合プロセス。

## Phase 1: Visual Direction (事前準備)
@rules/20-mv-direction.md
@rules/50-ref-image-prompts.md

1. **Character Definition**:
   - Midjourney/Fluxを使用して、楽曲の主人公となる **Master Reference Image** を生成する。
   - プロンプト例: `50-ref-image-prompts.md` 参照。
2. **Style Definition**:
   - MV全体の色調や画風を決定する。

## Phase 2: Scene Breakdown (構成)
@rules/41-audio-visual-sync.md

1. **Audio Segmentation**:
   - 楽曲を [Verse 1], [Chorus] などに分割し、タイムスタンプを記録する。
2. **Prompt Sheet Creation**:
   - 各セクションごとに「何が映るか」をテキスト化する。
   - **重要**: 各シーンで「どのリファレンスを使うか」を明記する。

| Time | Section | Action | Vidu Prompt | Reference |
| :--- | :--- | :--- | :--- | :--- |
| 0:00 | Intro | 雨の中佇む | Girl standing in rain, cinematic | @image1 |
| 0:15 | Verse | 歩き出す | Girl walking slowly, side profile | @image1 |
| 1:00 | Chorus | 走り出す | Girl running fast, camera follows | @image1 |

## Phase 3: Video Generation (Vidu Q2)
@rules/10-vidu-q2-specs.md

1. **Upload Reference**: Viduインターフェースにマスター画像をアップロード。
2. **Generate Scenes**:
   - Phase 2のプロンプトシートに従って、1カットずつ生成。
   - 失敗したらプロンプトを微調整（Motion Amplitudeを下げるなど）。
3. **Check Consistency**: キャラクターの顔が崩れていないか確認。
   - 崩れた場合: Reference Imageの適用強度（もしあれば）を調整するか、プロンプトを簡素化する。

## Phase 4: Editing (編集)
1. 生成した動画クリップを編集ソフトに配置。
2. 楽曲（Audio）をトラックに配置。
3. **Sync**: 音のビートに合わせてカットを調整。
4. **Lyrics Text**: 歌詞テロップを入れる（Sunoの生成歌詞を使用）。

## Phase 5: Complete
- エクスポートして完成。
