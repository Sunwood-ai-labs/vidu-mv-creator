# Visual Prompts: Yuki-Onna Runway

## Character Reference (Vidu Q2 Text-to-Image)
ユーザー指定の特徴をベースに、Vidu Q2向けのプロンプトを構築します。

**Ref Image Prompt**:
```
Ultra-detailed cinematic fashion photography of a Yuki-onna supermodel walking on a runway. She has porcelain-pale skin, long flowing silver hair, and glowing icy blue eyes. She is wearing a floor-length white silk evening gown with subtle silver embroidery and a sweeping train that looks like frost. She wears minimalist diamond jewelry and crystal stilettos. Developing icy mist swirls around her feet. The background is a dark gradient with a cool-toned spotlight illuminating her. Translucent ice shards levitate gracefully around her. 8K resolution, photorealistic, high fashion editorial, vogue style, depth of field.
```

## Vidu Q2 Video Generation Prompts
リファレンス画像生成後、以下のプロンプトで動画化します。

### Scene 1: The Walk (Front View)
```
The Yuki-onna model walks confidently down the dark runway. Her silver hair flows naturally as she moves. The white silk gown ripples like water. Icy mist swirls at her feet. Ice shards float and glitter in the spotlight. Slow motion, high fashion walk, intense eye contact.
```

### Scene 2: The Turn (Close-up / Glitch)
```
Close up shot of the Yuki-onna's face. She turns her head slowly to look at the camera. Her icy blue eyes glow. Snowflakes drift across her face. Subtle glitch effect transition. Elegant and mysterious expression.
```

### Scene 3: The Train (Back View)
```
Back view of the Yuki-onna walking away. The long sweeping train of her gown drags elegantly on the floor, leaving a trail of frost. Spotlight hits the silver embroidery. Mystical atmosphere.
```

## Outfit Variations (衣装バリエーション)
キャラクターリファレンス画像（顔や体型）を維持しつつ、プロンプトで衣装を変更する際のバリエーション案です。

### Variation A: Frozen Cyan Kimono (凍結蒼・着物)
**Color Scheme**: Icy cyan, turquoise, electric blue
**Description**: サイバーパンクと伝統的な着物の融合。冷たい青。
**Prompt Addition**:
```
She is wearing a deconstructed futuristic kimono made of translucent holographic material in icy cyan and electric turquoise colors. Glowing neon blue obi belt with digital patterns. Wide floating sleeves that glow softly. Exposed shoulders. The entire outfit shimmers in shades of frozen blue and aqua. Cyberpunk aesthetic mixed with traditional Japanese style. Cool blue lighting.
```

### Variation B: Twilight Empress Gown (極夜の女帝・ドレス)
**Color Scheme**: Deep purple, indigo, violet, gold accents
**Description**: ヴィクトリアンゴシックと和の融合。神秘的な紫。
**Prompt Addition**:
```
She is wearing an opulent Victorian-Japanese fusion gown in deep twilight purple and indigo. The bodice is a structured corset with intricate gold embroidery of winter flowers. A dramatic high collar made of layered purple silk petals frames her face. The skirt flows into multiple layers of sheer purple tulle and heavy velvet, creating a gradient from dark violet to lighter lavender. Long detached sleeves in sheer purple fabric float like spirits. Delicate gold chains and amethyst gemstones drape across the gown. Gothic meets imperial elegance. Mysterious and regal.
```

### Variation C: Blood Ice Goth (氷紅・ストリート)
**Color Scheme**: Deep crimson, blood red, black
**Description**: 現代ストリートスタイル。妖艶な赤。
**Prompt Addition**:
```
She is wearing an oversized crimson red faux-fur coat over a black latex crop top and wide-leg cargo pants with silver chains. The coat is a deep blood-red color that contrasts with the icy atmosphere. Chunky black platform boots with red accents. Dark gothic makeup with red lipstick. Street fashion runway style. Dramatic and dangerous. Red and black color palette.
```

### Variation D: Platinum Shiromuku (霜銀・白無垢)
**Color Scheme**: Platinum silver, metallic white, pearl
**Description**: 伝統的な白無垢を白銀のオートクチュールとして再構築。
**Prompt Addition**:
```
She is wearing a deconstructed Japanese wedding shiromuku kimono in platinum silver and metallic white. Asymmetrical layers of shimmering silver silk flowing dramatically. One shoulder exposed. Long trailing sleeves that float ethereally with a pearlescent sheen. Traditional uchikake patterns embroidered in reflective silver thread and tiny diamonds that catch light like frost. Elegant watabōshi (traditional bridal hood) reimagined as a gleaming platinum ice crown. Haute couture meets traditional Japanese wedding attire. Ghostly bridal aesthetic in pure metallic silver and white.
```

## Runway Gen-3 Alpha (Movements)
Viduで生成した動画の微調整や、より複雑なカメラワークが必要な場合に使用。

- **Horizontal Truck**: 横からの追従ショット
- **Zoom In**: 顔への寄り
- **Freeze & Orbit**: 時を止めて周囲を回る（氷の静止画的表現）
- **Effect**: `Motion Brush`で氷の粒子だけを動かす
