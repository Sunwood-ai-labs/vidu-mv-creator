---
description: 入力されたテーマや小説からSuno V5用の歌詞と楽曲を生成するフロー
---

# Story to Lyrics & Music Workflow

テーマや物語から、MVの核となる「楽曲」を生成する手順。

## 1. 原作分析 (Story Analysis)
1. **テーマ抽出**: 物語の核心（愛、喪失、戦い、日常など）を言語化する。
2. **感情曲線**: 物語の起承転結に合わせて、楽曲のダイナミクス（Aメロ＝静、サビ＝動）を決める。

## 2. 歌詞生成 (Lyrics Generation)
AI（ChatGPT/Claude等）を使用して、ストーリーをSuno V5フォーマットの歌詞に変換する。

**Prompt Example for AI:**
```text
以下のストーリーを元に、Suno AI用の歌詞を作成してください。
[Verse 1], [Pre-Chorus], [Chorus], [Bridge], [Outro] のタグを使ってください。
ジャンルは [Genre] です。

ストーリー:
[Input Story/Theme]
```

## 3. 楽曲生成 (Music Generation via Suno V5)
1. **Suno V5 Custom Mode** を開く。
2. **Lyrics**: ステップ2で生成した歌詞をペースト。
3. **Style of Music**:
   - 具体的なジャンル（Example: `J-Rock, piano intro, emotional female vocals`）。
   - 必要なら `BPM 120` などテンポ指定を試みる（確実ではない）。
4. **Generate**: 曲を生成する。
5. **Listen & Select**: 最もイメージに近いものを採用する。
   - 気に入ったが少し違う場合、`Extend` や `Remix` (Cover) を使用。

## 4. 楽曲データ整理 (Export)
1. **Audio Download**: 高音質（WAV/MP3）でダウンロード。
2. **Lyrics Save**: 確定した歌詞をテキストファイルとして保存。
3. **Parameters**: 使用したStyleプロンプト、Seed（あれば）を記録。
