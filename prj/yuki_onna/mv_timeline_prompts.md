# MV Production Design: 雪女ランウェイ (Yuki-Onna Runway)

**Character & Instrument Definitions**:
The following prompts define the specific visual tags used in the timeline. Use these descriptions to maintain consistency across generation.

## 1. Visual References

### Base Character: @AyanoYukimura
> **Master Prompt**:
> `Ultra-detailed cinematic fashion photography of a Yuki-onna supermodel walking on a runway. She has porcelain-pale skin, long flowing silver hair, and glowing icy blue eyes. She is wearing a floor-length white silk evening gown with subtle silver embroidery and a sweeping train that looks like frost. She wears minimalist diamond jewelry and crystal stilettos. Developing icy mist swirls around her feet. The background is a dark gradient with a cool-toned spotlight illuminating her. Translucent ice shards levitate gracefully around her. 8K resolution, photorealistic, high fashion editorial, vogue style, depth of field.`

---

### Set A: Frozen Cyan (Intro / Verse 1)
**Tag**: `@AyanoYukimura_FrozenCyan`
> `She is wearing a deconstructed futuristic kimono made of translucent holographic material in icy cyan and electric turquoise colors. Glowing neon blue obi belt with digital patterns. Wide floating sleeves that glow softly. Exposed shoulders. The entire outfit shimmers in shades of frozen blue and aqua. Cyberpunk aesthetic mixed with traditional Japanese style. Cool blue lighting.`

**Instrument**: `@FrozenKoto`
> `A futuristic Koto made of translucent hexagonal ice crystals and holographic glass components. It floats slightly off the stand. The 13 strings are beams of glowing cyan laser light. Frost vapor emanates from the instrument body.`

---

### Set B: Twilight Empress (Chorus 1)
**Tag**: `@AyanoYukimura_TwilightEmpress`
> `She is wearing an opulent Victorian-Japanese fusion gown in deep twilight purple and indigo. The bodice is a structured corset with intricate gold embroidery of winter flowers. A dramatic high collar made of layered purple silk petals frames her face. The skirt flows into multiple layers of sheer purple tulle and heavy velvet, creating a gradient from dark violet to lighter lavender. Long detached sleeves in sheer purple fabric float like spirits. Delicate gold chains and amethyst gemstones drape across the gown. Gothic meets imperial elegance. Mysterious and regal.`

**Instrument**: `@EmpressBiwa`
> `An imposing Satsuma Biwa carved from ancient black wood with deep purple grain. It is inlaid with gold spider lily patterns and large amethyst crystals. The bachi (plectrum) is a large, sharp blade of dark obsidian. A faint purple miasma surrounds it.`

---

### Set C: Blood Ice (Interlude)
**Tag**: `@AyanoYukimura_BloodIce`
> `She is wearing an oversized crimson red faux-fur coat over a black latex crop top and wide-leg cargo pants with silver chains. The coat is a deep blood-red color that contrasts with the icy atmosphere. Chunky black platform boots with red accents. Dark gothic makeup with red lipstick. Street fashion runway style. Dramatic and dangerous. Red and black color palette.`

**Instrument**: `@BloodShamisen`
> `A modernized Tsugaru Shamisen with a crimson red metallic body and silver spikes along the neck. The skin (do) is matte black with a red spiderweb crest. It looks battle-scarred and dangerous. The bachi (plectrum) is silver chrome.`

---

### Set D: Platinum Bride (Chorus 2 / Outro)
**Tag**: `@AyanoYukimura_PlatinumBride`
> `She is wearing a deconstructed Japanese wedding shiromuku kimono in platinum silver and metallic white. Asymmetrical layers of shimmering silver silk flowing dramatically. One shoulder exposed. Long trailing sleeves that float ethereally with a pearlescent sheen. Traditional uchikake patterns embroidered in reflective silver thread and tiny diamonds that catch light like frost. Elegant watabōshi (traditional bridal hood) reimagined as a gleaming platinum ice crown. Haute couture meets traditional Japanese wedding attire. Ghostly bridal aesthetic in pure metallic silver and white.`

**Instrument**: `@PlatinumShakuhachi`
> `A long, elegant Shakuhachi flute crafted from solid platinum. It has a mirror-like surface and is encrusted with a line of diamond dust that sparkles like stars. It emits a cold, white vapor when held.`

---

## 2. Production Timeline
**Stage**: `@幽雅殿` (A grand, mystical runway made of dark polished ice, set within an infinite dimly lit void. Spotlights cut through the darkness.)
**Format**: Vidu Q2 (4s - 8s clips) / 1080p or 4K
**Important**: Each prompt must be self-contained. The AI does not know the context of the previous clip.

### 0. Intro: 氷の琴 (The Frozen Koto) | 0:00 - 0:22
**Theme**: Silence, Cold, Introduction of the Stage.

| No | Start | Dur | Lyric / Audio Event | Flag | Base ID | Shot Concept & Vidu Q2 Prompt |
|:---|:---|:---|:---|:---|:---|:---|
| **01** | 0:00 | 8s | (Intro: Koto Start) | `INST_CYAN` | *NEW* | **Inst / Cyan**. Koto focus. <br>`@AyanoYukimura_FrozenCyan が @幽雅殿 のステージ中央で @FrozenKoto を奏でている。指先のアップから顔への引き。弦から冷気と光の粒子が舞い上がる幻想的で静謐な8秒間のワンショット。ハイクオリティ実写。` |
| **02** | 0:08 | 8s | (Intro: Buildup) | `INST_CYAN` | *NEW* | **Inst / Cyan**. Atmosphere. <br>`@AyanoYukimura_FrozenCyan が @幽雅殿 のステージ中央で @FrozenKoto の演奏を続けるスローなトラッキングショット。冷気が周囲を凍らせていく。蒼いホログラフィックな着物の質感を強調。8秒間のワンカット。` |
| **03** | 0:16 | 6s | (Intro: Transition) | `INST_CYAN` | *CYAN_V1* | **Inst / Cyan**. Performance End. <br>`@AyanoYukimura_FrozenCyan が @幽雅殿 で @FrozenKoto の演奏を静かに終える瞬間の余韻。指先が止まり、顔を上げてランウェイの先を見据える6秒間のシネマティックなショット。` |

### 1. Verse 1 & Pre-Chorus: 蒼き冷徹 (Frozen Cyan) | 0:22 - 0:48
**Theme**: Cold beauty, Untouchable nature.

| No | Start | Dur | Lyric / Audio Event | Flag | Base ID | Shot Concept & Vidu Q2 Prompt |
|:---|:---|:---|:---|:---|:---|:---|
| **04** | 0:22 | 5.5s | 白き肌に触れる風は<br>凍てつく記憶 呼び覚ます | `WALK_CYAN` | *CYAN_V1* | **Walk / Cyan**. Start Walk. <br>`@AyanoYukimura_FrozenCyan が @幽雅殿 のランウェイをゆっくりと歩き出す。正面からのフルショット。冷たい霧を切り裂くように進む5.5秒間の継続的なキャットウォーク。` |
| **05** | 0:28 | 6.5s | Runway lights, cutting through the snow<br>誰も触れられない Cold as ice | `WALK_CYAN` | *CYAN_V1* | **Walk / Cyan**. Lights & Snow. <br>`@AyanoYukimura_FrozenCyan が @幽雅殿 のランウェイを歩いている。スポットライトが彼女を照らし、背後でダイヤモンドのように輝く雪が舞い散る6.5秒間のシネマティックなワンカット。` |
| **06** | 0:34.5 | 6s | 近づけば壊れてしまう<br>Unreachable, untouchable, beautiful lie | `WALK_CYAN` | *CYAN_V1* | **Walk / Cyan**. Gaze & Focus. <br>`@AyanoYukimura_FrozenCyan が @幽雅殿 のランウェイを前進しながら、カメラを射抜くような強い視線を送る。被写界深度が変化し、背景がボケて表情が浮かび上がる6秒間の継続ショット。` |
| **07** | 0:41 | 6.5s | 吐息さえも結晶に変わる<br>Now watch me freeze the time | `FX_CYAN` | *CYAN_V2* | **FX / Cyan**. Breath Detail. <br>`@AyanoYukimura_FrozenCyan の超クローズアップ。白い吐息が空中で瞬時に氷の結晶へと変わるディテールを描く。衣装から蒼い光の粒子が湧き上がる6.5秒間のワンショット。` |

### 2. Chorus 1: 極夜の女帝 (Twilight Empress) | 0:48 - 1:06
**Theme**: Majesty, Power, Transformation.

| No | Start | Dur | Lyric / Audio Event | Flag | Base ID | Shot Concept & Vidu Q2 Prompt |
|:---|:---|:---|:---|:---|:---|:---|
| **08** | 0:48 | 5.5s | 舞い散る雪はダイヤモンド<br>(Maichiru yuki wa diamond) | `WALK_PURPLE` | *PURPLE_V1* | **Walk / Purple**. Empress Walk. <br>`@AyanoYukimura_TwilightEmpress が @幽雅殿 のランウェイ中央を堂々と歩く。重厚な紫のドレスの裾が広がり、金の刺繍が豪華に揺れる5.5秒間の壮麗なワンカット。` |
| **09** | 0:54 | 5.5s | 孤独を纏う Silver ghost<br>Frozen heart, beating slow | `WALK_PURPLE` | *PURPLE_V1* | **Walk / Purple**. Elegance. <br>`@AyanoYukimura_TwilightEmpress のミディアムショット。紫のベルベットとジュエリーがスポットライトを反射し、優雅に揺れる。周囲に紫の霧が立ち込める5.5秒間の継続ウォーク。` |
| **10** | 1:00 | 6s | この世界さえ 凍らせて | `FX_PURPLE` | *PURPLE_V2* | **FX / Purple**. Freeze World. <br>`@AyanoYukimura_TwilightEmpress がランウェイ正面で足を止める。彼女の足元から @幽雅殿 全体が波状に紫の氷で覆われていく幻想的な6秒間の圧倒的ワンショット。` |

### 3. Interlude: 紅き激情 (Blood Ice) | 1:06 - 1:26
**Theme**: Aggression, Danger, "Don't Touch".

| No | Start | Dur | Lyric / Audio Event | Flag | Base ID | Shot Concept & Vidu Q2 Prompt |
|:---|:---|:---|:---|:---|:---|:---|
| **11** | 1:06 | 4s | (Interlude: Dark Turn) | `ACTION_RED` | *RED_V1* | **Action / Red**. Intro Glare. <br>`急激に暗転し、紅いライティングへ。@AyanoYukimura_BloodIce が @BloodShamisen を片手で掴み、武器のように構えて鋭くカメラを睨む4秒間の攻撃的なショット。` |
| **12** | 1:10 | 5s | DON'T TOUCH.<br>(Yuki-onna, freeze...) | `ACTION_RED` | *RED_V1* | **Action / Red**. Warning. <br>`@AyanoYukimura_BloodIce が真っ赤に染まった @幽雅殿 で激しく真紅のファーを翻し、威嚇するようにポーズを決める。演奏はせず、圧倒的な存在感で魅せる5秒間のモデリングショット。` |
| **13** | 1:15 | 4s | Don't touch. | `ACTION_RED` | *RED_V2* | **Action / Red**. Smirk. <br>`@AyanoYukimura_BloodIce が不敵に微笑むクローズアップ。赤いゴシックメイクが際立ち、ファーコートを大きく翻して歩みを止める4秒間の継続的な表情ショット。` |
| **14** | 1:19 | 7s | (Interlude: Blizzard) | `INST_RED` | *RED_V1* | **Inst / Red**. Shamisen Solo. <br>`@AyanoYukimura_BloodIce が猛吹雪の @幽雅殿 で乱れ狂うように @BloodShamisen を弾きまくる。シルバーチェーンと赤いファーが激しく揺れる、7秒間のエネルギッシュな演奏シーン。` |

### 4. Verse 2: 変幻の魂 (Four Faces) | 1:26 - 1:39
**Theme**: Chaos, Morphing, Transition.

| No | Start | Dur | Lyric / Audio Event | Flag | Base ID | Shot Concept & Vidu Q2 Prompt |
|:---|:---|:---|:---|:---|:---|:---|
| **15** | 1:26 | 7.5s | Catwalk in the blizzard<br>凍結蒼 / 極夜の紫 / 氷紅 / 霜銀 | `WALK_MULTI` | *NEW* | **FX / Multi**. Morph Walk. <br>`吹雪の中、@AyanoYukimura_FrozenCyan から @AyanoYukimura_TwilightEmpress へ残像のように姿が入れ替わりながら進む7.5秒間の幻想的なキャットウォーク。` |
| **16** | 1:34 | 4.5s | 溶けることない 永遠の冬 | `WALK_SILVER` | *SILVER_V1* | **Walk / Silver**. Appearance. <br>`厚い吹雪の中から @AyanoYukimura_PlatinumBride が静かに現れる。白銀の世界と化した @幽雅殿 を神聖に歩む4.5秒間のワンショット。` |

### 5. Chorus 2 & Outro: 白銀の永遠 (Platinum Bride) | 1:39 - 2:12
**Theme**: Climax, Eternity, Disappearance.

| No | Start | Dur | Lyric / Audio Event | Flag | Base ID | Shot Concept & Vidu Q2 Prompt |
|:---|:---|:---|:---|:---|:---|:---|
| **17** | 1:39 | 5s | 舞い散る雪はダイヤモンド<br>(Maichiru yuki wa diamond) | `WALK_SILVER` | *SILVER_V1* | **Walk / Silver**. Climax Walk. <br>`@AyanoYukimura_PlatinumBride のフルショット。頭上の氷の冠とプラチナのドレスが極限まで輝き、周囲の空気が凍りついて静止する5秒間の高貴な継続ショット。` |
| **18** | 1:45 | 5s | 孤独を纏う Silver ghost<br>Frozen heart, beating slow | `WALK_SILVER` | *SILVER_V2* | **Walk / Silver**. Ethereal Back. <br>`@AyanoYukimura_PlatinumBride の背後からの周回ショット。浮遊する半透明の袖と長い裾が幽玄に舞う。粉雪がダイヤモンドのように光る5秒間の幻想的ショット。` |
| **19** | 1:51 | 5.5s | この世界さえ 凍らせて | `FX_SILVER` | *SILVER_V2* | **FX / Silver**. Shockwave. <br>`@AyanoYukimura_PlatinumBride が正面を向き、彼女を中心に純白の衝撃波が @幽雅殿 を突き抜ける。周囲が瞬時に一新される5.5秒間のクライマックス・ワンカット。` |
| **20** | 1:57 | 7s | Forever cold.<br>(Whisper: Yuki-onna...) | `EXIT_SILVER` | *SILVER_V1* | **Exit / Silver**. Leaving. <br>`@AyanoYukimura_PlatinumBride がランウェイの出口へ向かい、遠ざかる。背中を見せて歩き去り、彼女の姿が次第に白く霞んでいく7秒間のシネマティックなロングショット。` |
| **21** | 2:04 | 8s | (Outro: Final Breath) | `INST_SILVER` | *NEW* | **Inst / Silver**. Final Shakuhachi. <br>`最後に肩越しに振り返る @AyanoYukimura_PlatinumBride。取り出した @PlatinumShakuhachi を吹き、音色と共に激しい雪原の中に溶けていく8秒間の静謐なラストショット。` |
