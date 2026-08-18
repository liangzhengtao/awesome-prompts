# AI 图像生成 Prompts / Image Generation Prompts

> 🎨 AI 图像生成 Prompt 集合，覆盖风格修饰、构图关键词、质量提升和反向提示词。
> AI image generation prompts covering style modifiers, composition keywords, quality boosters, and negative prompts.

## 目录 / Table of Contents

- [风格修饰词 / Style Modifiers](#风格修饰词--style-modifiers)
- [构图与视角 / Composition & Perspective](#构图与视角--composition--perspective)
- [质量提升词 / Quality Boosters](#质量提升词--quality-boosters)
- [反向提示词 / Negative Prompts](#反向提示词--negative-prompts)
- [完整 Prompt 模板 / Complete Prompt Templates](#完整-prompt-模板--complete-prompt-templates)

---

## 风格修饰词 / Style Modifiers

### 1. 艺术风格 Prompt

```
[SUBJECT], [STYLE_KEYWORDS], [LIGHTING], [QUALITY]

风格关键词库：
- 写实摄影：photorealistic, hyperrealistic, 8k, DSLR, Canon EOS R5
- 油画风格：oil painting, impasto, classical, Renaissance style
- 水彩风格：watercolor painting, soft washes, delicate, translucent
- 赛博朋克：cyberpunk, neon lights, futuristic, dystopian, dark atmosphere
- 像素艺术：pixel art, 8-bit, retro gaming style, limited palette
- 扁平设计：flat design, minimalist, vector art, clean lines, geometric
- 日本动漫：anime style, Studio Ghibli, cel-shaded, vibrant colors
- 概念艺术：concept art, matte painting, epic, cinematic, detailed
- 超现实主义：surrealism, dreamlike, Salvador Dali style, impossible geometry
- 蒸汽朋克：steampunk, Victorian era, brass machinery, gears, ornate

组合示例：
a majestic mountain landscape, oil painting style, golden hour lighting, dramatic clouds, highly detailed, masterpiece quality
```

### 2. 摄影风格 Prompt

```
[SUBJECT], [CAMERA], [LENS], [LIGHTING], [MOOD]

摄影关键词库：
- 相机：DSLR, mirrorless, Hasselblad, Leica, film camera, Polaroid
- 镜头：85mm portrait lens, 24mm wide angle, macro lens, tilt-shift, fisheye
- 光线：golden hour, blue hour, soft diffused light, dramatic backlighting, studio lighting, Rembrandt lighting
- 胶片质感：Kodak Portra 400, Fujifilm Velvia, Kodachrome, film grain, vintage
- 景深：shallow depth of field, bokeh, deep focus, selective focus

组合示例：
a portrait of an elderly craftsman, shot on Hasselblad X2D, 85mm f/1.4 lens, shallow depth of field, natural window light, Kodak Portra 400 film look, gentle film grain
```

### 3. 3D 渲染风格 Prompt

```
[SUBJECT], [RENDER_ENGINE], [MATERIAL], [LIGHTING_SETUP]

3D 渲染关键词库：
- 渲染引擎：Unreal Engine 5, Octane Render, Blender Cycles, V-Ray, Cinema 4D
- 材质：glass, chrome, matte plastic, brushed metal, translucent, iridescent
- 光照：HDRI lighting, volumetric lighting, caustics, global illumination, ambient occlusion
- 风格：low poly, isometric, clay render, wireframe, holographic

组合示例：
a futuristic floating city, Unreal Engine 5, volumetric fog, holographic materials, neon glow, cinematic composition, 8k render, ray tracing
```

### 4. 设计风格 Prompt

```
[SUBJECT], [DESIGN_STYLE], [COLOR_PALETTE], [COMPOSITION]

设计风格关键词库：
- 极简主义：minimalist, Swiss design, white space, clean grid
- 包豪斯：Bauhaus style, primary colors, geometric shapes, functional
- 孟菲斯：Memphis design, bold patterns, bright colors, playful, 80s
- 装饰艺术：Art Deco, gold accents, symmetry, luxury, geometric patterns
- 波普艺术：Pop Art, Andy Warhol style, bold outlines, Ben-Day dots
- 日式设计：Japanese design, wabi-sabi, negative space, elegant simplicity
- 复古海报：vintage poster, retro, screen print texture, muted colors
- 玻璃态：glassmorphism, frosted glass, transparency, subtle blur

组合示例：
a modern tech company poster, Swiss minimalist design, grid layout, bold sans-serif typography, monochromatic blue palette, clean white space
```

---

## 构图与视角 / Composition & Perspective

### 5. 构图关键词

```
[SUBJECT], [COMPOSITION_TYPE], [CAMERA_ANGLE], [FRAMING]

构图类型：
- 三分法：rule of thirds composition
- 中心对称：centered composition, symmetrical
- 对角线：diagonal composition, dynamic angle
- 黄金比例：golden ratio composition
- 引导线：leading lines, converging perspective
- 框架构图：frame within frame, natural framing
- 极简留白：minimalist, negative space, [SUBJECT] in corner

视角：
- 鸟瞰：bird's eye view, aerial view, top-down
- 仰视：low angle shot, worm's eye view, heroic perspective
- 平视：eye level, straight on
- 倾斜：Dutch angle, tilted frame, dynamic
- 特写：extreme close-up, macro, detail shot
- 远景：wide shot, establishing shot, panoramic
- 过肩：over the shoulder shot

组合示例：
a lone figure walking through a vast desert, wide establishing shot, rule of thirds placement, low camera angle, dramatic scale contrast
```

### 6. 光影与氛围

```
[SUBJECT], [LIGHTING_TYPE], [ATMOPHERE], [MOOD]

光影类型：
- 伦勃朗光：Rembrandt lighting, dramatic shadows, chiaroscuro
- 逆光：backlit, silhouette, rim light, halo effect
- 霓虹光：neon lighting, colored light reflections, urban night
- 烛光：candle light, warm intimate glow, soft shadows
- 阴天光：overcast, soft diffused light, even illumination
- 丁达尔效应：god rays, volumetric light, light shafts through fog
- 工作室光：three-point studio lighting, professional, clean

氛围：
- 史诗感：epic, grand, awe-inspiring, monumental
- 神秘感：mysterious, enigmatic, foggy, shadowy
- 温馨感：cozy, warm, inviting, comfortable
- 孤独感：solitary, isolated, melancholic, vast empty space
- 紧张感：tense, dramatic, high contrast, ominous

组合示例：
an ancient temple interior, volumetric god rays streaming through cracks, dust particles in air, mysterious atmosphere, warm golden light against cool shadows, sense of awe
```

---

## 质量提升词 / Quality Boosters

### 7. 通用质量提升

```
在 Prompt 末尾添加以下质量提升词：

通用提升：
- masterpiece, best quality, highly detailed, ultra-detailed
- 8k resolution, UHD, high resolution
- sharp focus, crisp details, intricate details
- professional, award-winning, stunning
- trending on ArtStation, featured on Behance

特定平台优化（根据使用的模型选择）：
- Stable Diffusion: masterpiece, best quality, highly detailed, absurdres
- Midjourney: --ar 16:9 --v 6 --q 2 --style raw
- DALL-E: [自然语言描述，无需特殊关键词]
- Flux: [自然语言描述，详细的上下文描述]

推荐的质量组合：
masterpiece, best quality, highly detailed, 8k UHD, sharp focus, professional photography, award-winning
```

### 8. 颜色控制

```
[SUBJECT], [COLOR_SCHEME]

颜色方案关键词：
- 暖色调：warm tones, golden, amber, sunset palette, warm color grading
- 冷色调：cool tones, blue palette, icy, cold color grading
- 单色：monochromatic, black and white, sepia tone, single color
- 高饱和：vibrant colors, saturated, vivid, electric, bold colors
- 低饱和：muted colors, desaturated, pastel, soft palette, earth tones
- 互补色：complementary colors, teal and orange, blue and gold
- 霓虹色：neon colors, glowing, fluorescent, cyberpunk palette
- 莫兰迪色：Morandi palette, muted pastels, soft harmonious colors
- 复古色：vintage color palette, retro, faded, Kodachrome

组合示例：
a cozy reading nook, warm amber and brown tones, soft golden lamp light, earth-toned color palette, hygge atmosphere
```

---

## 反向提示词 / Negative Prompts

### 9. 通用反向提示词

```
Negative Prompt（根据模型和需求组合使用）：

【通用反向】
low quality, worst quality, blurry, out of focus, noise, grainy, artifacts, watermark, signature, text, logo, username, cropped, jpeg artifacts, compression artifacts

【人物反向】
deformed, disfigured, mutated, ugly, bad anatomy, extra limbs, extra fingers, missing fingers, fused fingers, too many fingers, long neck, cross-eyed, unnatural skin, bad proportions, malformed limbs, cloned face

【风格反向】
cartoon, anime, 3d render, painting, illustration, sketch, drawing (当需要写实照片时)
photorealistic, photo, realistic (当需要插画/卡通风格时)

【构图反向】
out of frame, cut off, cropped, poorly composed, cluttered background, busy background

Stable Diffusion 专用反向提示词（推荐）：
(worst quality, low quality:1.4), (deformed, distorted:1.3), disfigured, bad anatomy, bad hands, extra fingers, missing fingers, blurry, watermark, text, signature
```

---

## 完整 Prompt 模板 / Complete Prompt Templates

### 10. 人物肖像模板

```
[性别] [年龄] [外貌特征], [表情], [服装], [姿势], [背景], [光线], [风格], [质量]

示例：
a young East Asian woman in her late 20s, serene expression, wearing an elegant white silk blouse, sitting by a window, soft natural daylight, shallow depth of field, shot on Sony A7R V, 85mm f/1.4, Kodak Portra 400 film look, photorealistic, highly detailed skin texture

Negative: deformed, bad anatomy, extra limbs, blurry, cartoon, anime
```

### 11. 风景/场景模板

```
[地点类型], [时间段], [天气], [光线], [氛围], [风格], [构图], [质量]

示例：
a hidden Japanese garden in autumn, early morning, light mist, golden sunlight filtering through maple leaves, peaceful and serene atmosphere, koi pond reflection, moss-covered stone path, shot on medium format camera, wide angle lens, rule of thirds composition, 8k highly detailed, photorealistic
```

### 12. 产品展示模板

```
[产品名称], [材质], [颜色], [摆放方式], [背景], [光线], [风格]

示例：
a premium wireless headphone, matte black aluminum and leather, floating at 45-degree angle, pure white studio background, three-point studio lighting, dramatic rim light, product photography, clean minimalist composition, ultra-detailed textures, commercial quality, 8k
```

### 13. 概念艺术模板

```
[场景/角色], [世界观], [关键元素], [氛围], [风格], [渲染], [质量]

示例：
a floating sky city above the clouds, steampunk Victorian architecture, massive brass gears and steam pipes, airships docked at towers, warm golden hour light, epic scale, concept art style, matte painting, highly detailed, cinematic composition, by Greg Rutkowski and Simon Stalenhag, trending on ArtStation
```

### 14. Logo/图标设计模板

```
[品牌名/图标类型], [风格], [元素], [颜色], [背景]

示例：
a modern tech startup logo for "NovaFlow", minimalist geometric design, abstract flowing lines suggesting data stream, gradient blue to purple, clean white background, vector style, scalable, professional brand identity, flat design, sleek and contemporary
```

### 15. 建筑设计模板

```
[建筑类型], [风格], [材质], [环境], [光线], [视角], [质量]

示例：
a contemporary museum building, organic flowing architecture by Zaha Hadid style, white concrete and glass facade, surrounded by reflecting pools and gardens, dramatic sunset light, aerial perspective showing full building and landscape, architectural visualization, Unreal Engine 5 render, 8k, photorealistic materials
```

### 16. 美食摄影模板

```
[菜品], [摆盘], [餐具], [背景], [光线], [角度], [风格]

示例：
a gourmet chocolate lava cake on a rustic wooden plate, molten chocolate center flowing out, dusted with powdered sugar, fresh raspberries garnish, dark moody background, dramatic side lighting, shot from 45-degree angle, food photography, shallow depth of field, warm color tones, professional food styling, highly appetizing
```

### 17. 动物/自然模板

```
[动物], [行为], [环境], [光线], [风格], [质量]

示例：
a majestic red fox in a snowy forest, pausing to look directly at camera, snowflakes falling softly, morning golden light through pine trees, dense winter forest background, wildlife photography, shot on Nikon Z9 with 200-600mm lens, shallow depth of field, sharp eye focus, National Geographic quality, 8k ultra detailed
```

### 18. 抽象艺术模板

```
[抽象概念/情感], [形态], [颜色], [质感], [风格]

示例：
an abstract representation of quantum entanglement, flowing interconnected particles and waves, deep indigo and electric blue with gold accents, luminous translucent layers, fluid dynamics, generative art style, high contrast, detailed particle effects, 4k wallpaper quality
```

### 19. 游戏美术模板

```
[角色/场景类型], [游戏风格], [关键设计], [氛围], [渲染], [质量]

示例：
a legendary warrior character for a dark fantasy RPG, ornate dark plate armor with glowing runes, massive greatsword on back, standing on a cliff overlooking a burning battlefield, dramatic stormy sky, Unreal Engine 5 in-game model, detailed textures, PBR materials, cinematic lighting, character concept art quality
```

### 20. 社交媒体素材模板

```
[平台], [用途], [内容], [风格], [尺寸], [品牌调性]

示例：
an Instagram post image for a coffee brand, a cozy morning scene with a latte in a ceramic cup on a marble counter, warm natural light streaming through a window, steam rising from the cup, minimalist aesthetic, warm earth tones, lifestyle photography style, square format 1:1 ratio
```

### 21. 插画/绘本模板

```
[场景], [角色], [风格], [颜色], [质感], [情绪]

示例：
a children's book illustration of a small rabbit reading a book under a giant mushroom, whimsical fantasy forest setting, Studio Ghibli inspired style, soft watercolor textures, warm pastel colors, magical fireflies floating, cozy and enchanting mood, gentle linework
```

### 22. 科技/未来感模板

```
[技术主题], [视觉元素], [色调], [氛围], [渲染], [质量]

示例：
a futuristic AI brain neural network visualization, interconnected glowing nodes and pathways, holographic data streams, dark background with electric blue and cyan highlights, volumetric light effects, sci-fi interface aesthetic, Unreal Engine 5 cinematic render, 8k, ray tracing, ultra detailed
```

---

## 💡 使用技巧 / Tips

1. **分层构建**：主体 → 风格 → 光线 → 构图 → 质量，逐层添加关键词
2. **权重控制**：在 Stable Diffusion 中用 `(keyword:1.5)` 控制权重
3. **迭代优化**：先生成基本版本，再逐步添加修饰词细化
4. **参考图+文字**：用参考图 + Prompt 组合效果更好（图生图）
5. **模型适配**：不同模型对 Prompt 的响应方式不同，要针对性调整
6. **避免冲突**：不要同时使用冲突的风格词（如"写实"和"卡通"）

## ⚠️ 常见错误 / Common Mistakes

- ❌ Prompt 过长（超过 75-150 token 后效果可能下降）
- ❌ 使用矛盾的关键词（如"minimalist" + "highly detailed ornate"）
- ❌ 不使用反向提示词（质量会大打折扣）
- ❌ 忽略光线描述（光线是画面氛围的关键）
- ❌ 忽略构图（好的构图让画面更有冲击力）
- ❌ 照搬别人的 Prompt 不做调整（不同模型需要不同策略）

---

## 中文版本

> 🎨 AI 图像生成 Prompt 集合，覆盖风格修饰、构图关键词、质量提升和反向提示词，帮助你用文字精准控制 AI 生成图像。

### 核心 Prompt 示例

**艺术风格 Prompt：**
[SUBJECT], [STYLE_KEYWORDS], [LIGHTING], [QUALITY]。风格关键词库包括：写实摄影（photorealistic, hyperrealistic, 8k）、油画风格（oil painting, impasto, Renaissance style）、水彩风格（watercolor painting, soft washes）、赛博朋克（cyberpunk, neon lights）、像素艺术（pixel art, 8-bit）、日本动漫（anime style, Studio Ghibli）、概念艺术（concept art, matte painting）、超现实主义（surrealism, dreamlike）等。

**摄影风格 Prompt：**
[SUBJECT], [CAMERA], [LENS], [LIGHTING], [MOOD]。摄影关键词库包括：相机（DSLR, Hasselblad, Leica）、镜头（85mm portrait lens, 24mm wide angle, macro lens）、光线（golden hour, blue hour, Rembrandt lighting）、胶片质感（Kodak Portra 400, Fujifilm Velvia）、景深（shallow depth of field, bokeh）。

**完整人物肖像模板：**
[性别] [年龄] [外貌特征], [表情], [服装], [姿势], [背景], [光线], [风格], [质量]。示例：a young East Asian woman in her late 20s, serene expression, wearing an elegant white silk blouse, sitting by a window, soft natural daylight, shallow depth of field, shot on Sony A7R V, 85mm f/1.4, Kodak Portra 400 film look, photorealistic, highly detailed skin texture。

**通用反向提示词（Negative Prompt）：**
通用反向：low quality, worst quality, blurry, out of focus, noise, grainy, artifacts, watermark, signature, text。人物反向：deformed, disfigured, mutated, ugly, bad anatomy, extra limbs, extra fingers, missing fingers。构图反向：out of frame, cut off, cropped, poorly composed, cluttered background。

### 💡 使用技巧

1. **分层构建**：主体 → 风格 → 光线 → 构图 → 质量，逐层添加关键词
2. **权重控制**：在 Stable Diffusion 中用 `(keyword:1.5)` 控制权重
3. **迭代优化**：先生成基本版本，再逐步添加修饰词细化
4. **参考图+文字**：用参考图 + Prompt 组合效果更好（图生图）
5. **模型适配**：不同模型对 Prompt 的响应方式不同，要针对性调整
6. **避免冲突**：不要同时使用冲突的风格词（如"写实"和"卡通"）
