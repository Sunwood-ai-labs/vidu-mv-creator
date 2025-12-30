# Suno V5 仕様とプロンプト技術 (Suno V5 Specs & Prompting)

## モデル概要 (Model Specs)
- **Version**: V5 (Generated late 2025)
- **Max Duration**: 4分〜8分 (Premier: up to 8 min)
- **Features**:
  - **Personas**: 声質やスタイルを固定して再利用可能。
  - **Covers**: 既存の曲や音声を別のジャンルでカバー。
  - **ReMi (Lyrics Model)**: 歌詞生成能力が向上。
  - **Audio Quality**: 44.1kHz / 48kHz, Studio Quality stems.

## 歌詞構造 (Structure Tags)
Suno V5は以下の構造タグを強く認識する。

```text
[Intro]
(Instrumental build-up)

[Verse 1]
物語の始まり、静かなトーン。

[Pre-Chorus]
盛り上がりへの予兆。

[Chorus]
サビ。キャッチーで感情的。
(Hook line repetition)

[Bridge]
展開の変化。

[Guitar Solo]
[Instrumental Interlude]

[Chorus]
最後の盛り上がり。

[Outro]
フェードアウト、または余韻。
```

## 歌詞プロンプト・テクニック
### テーマから歌詞を生成する場合
- **入力**: テーマ、あらすじ、または小説の抜粋。
- **指示**: 「この小説の感情曲線を曲に反映して」
- **Tip**: 抽象的なテーマよりも、具体的な情景描写（「雨の降る渋谷」「ネオンライト」）を入れると、Sunoがジャンルを推測しやすい。

### メタ・タグ (Style Prompts)
歌詞の先頭やタイトル欄にスタイルを指定する。
- `J-Pop, Cyberpunk style, fast tempo, female vocals, emotional`
- `Lo-fi Hip Hop, chill beats, male rap, melancholic`
- `Epic Orchestral, cinematic, choir`

## MV制作との連携ポイント
- **BPMの固定**: Suno生成時にBPMを指定するのは難しいが、生成後の曲のBPMを計測し、映像カット割りに反映すること。
- **Stems活用**: 可能ならVocalとInstrumentalを分けてダウンロードし、映像のリップシンク精度を上げる（Viduは音声波形からのリップシンクが可能）。
