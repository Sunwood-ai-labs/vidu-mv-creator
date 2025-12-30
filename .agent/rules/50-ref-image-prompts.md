# Visual Reference 戦略とプロンプト (Visual Reference Strategy)

Vidu Q2の一貫性を最大化するには、「最強の1枚（Master Reference）」を作ることが全てである。

## Reference Image 生成ガイド

### 推奨ツール
- **Midjourney V6+** (推奨: `--cref` 機能が強力)
- **Flux.1** (優れたプロンプト追従性)

### キャラクターシート・プロンプト (Character Sheet)
Viduに読み込ませる前に、キャラクターの「三面図」的要素を含んだマスター画像を生成する。

**Midjourney Prompt Template:**
```text
[Character Description], detailed face, character sheet, multiple angles, front view, side view, white background, high quality, 8k, cel shaded style --ar 3:2 --niji 6
```

**Vidu用マスター画像 (Single Best Shot):**
Viduのリファレンスには「正面に近い、バストアップ〜膝上」が最適。

```text
[Character Description] looking at viewer, cinematic lighting, detailed background consistent with [Theme], masterpiece --ar 16:9
```

## Vidu Q2 プロンプト構成 (Advanced)

### 基本構文
```text
<Descriptive Prompt> @image1
```
※ インターフェースにより `@image1` の部分は `Reference Image: [Upload]` に置き換わる。

### カメラワーク指定の強化
プロンプト内でリファレンス画像（キャラクター）に対してカメラがどう動くかを指定する。

- **Subject**: `@image1 looking confidently`
- **Camera**: `zoom in slowly`, `truck left`, `orbit around character`
- **Lighting**: `cinematic lighting matching @image1`

### 一貫性維持の呪文 (Magic Words)
プロンプトの末尾に以下を追加する。
`consistent character, consistent style, high fidelity to reference`

## シーン別リファレンス戦略
1. **キャラクター固定**: 顔や服装が変わってはいけない要素。 -> `@image1` (Character Ref)
2. **画風固定**: 水彩画風、アニメ風など。 -> `@image2` (Style Ref)

Vidu Q2では、**Character Ref** が最も重要。迷ったらCharacter Refのみを使用する。
