# 基底参考图 · 文生图 Prompts(放弃原画,全部直接生成)

> 方式:**纯文生图(text-to-image)**,不挂参考图。
> "儿童手绘感"靠 Prompt 里的 `childlike hand-drawn / crayon / watercolor / imperfect lines` 实现。
> 每条都已含风格尾巴。**负向框统一填通用 Negative(见文末)。**
> 先做这 6 张当"血统底图",选定后所有镜头都引用它们,绝不每条重抽。

---

## 1. 小毛球(主角,镜头 1–9)

> 与 `02_角色设定/角色设定_Prompts.md §1` 同一条,直接文生图、不挂参考图即可。

```
A cute round fluffy creature, small and soft like a ball of fur, tiny legs, tiny arms, big expressive eyes, simple innocent face, unlucky but kind personality, childlike hand-drawn animation style, inspired by a young child's drawing, crayon texture, soft watercolor colors, imperfect hand-drawn lines, warm and cute, 2D illustration, simple white background, character sheet with happy, sad, surprised expressions
```

## 2. 小女孩(镜头 9–12)

> 与 `角色设定_Prompts.md §2` 同一条。

```
A little girl with long soft hair, wearing a simple white top and a bright yellow skirt, gentle and brave expression, childlike hand-drawn animation style, inspired by a young child's original drawing, crayon texture, soft watercolor colors, imperfect hand-drawn lines, warm innocent mood, 2D illustration, front view and side view, smiling, surprised, dancing, holding a sketchbook
```

## 3. 教室(镜头 2、3、10)

```
A simple childlike classroom interior, a few small wooden desks, a blackboard, a round wall clock, big windows with soft daylight, warm and cozy, empty of people, plenty of negative space, childlike hand-drawn illustration, inspired by a young child's drawing, crayon texture, soft watercolor colors, imperfect hand-drawn lines, 2D illustration, simple, no brand logos, no text
```

## 4. 家中窗前(镜头 12)

```
A cozy childlike home interior by a large window at sunset, warm golden light coming through, a small desk or windowsill with a sketchbook and crayons, soft curtains, calm and warm, empty of people, plenty of negative space, childlike hand-drawn illustration, inspired by a young child's drawing, crayon texture, soft watercolor colors, imperfect hand-drawn lines, 2D illustration, no brand logos
```

## 5. 女孩 + 小毛球(同框,镜头 11、12)

```
A little girl with long hair, white top and yellow skirt, standing together with a tiny round fluffy creature beside her, gentle friendship, both cute and happy, childlike hand-drawn illustration, inspired by a young child's drawing, crayon texture, soft watercolor colors, imperfect hand-drawn lines, warm innocent mood, 2D illustration, simple warm background
```

## 6. 时间异常符号表(时钟 / 雨滴 / 纸飞机 / 水花 / 火花)

```
A childlike hand-drawn element sheet on a simple plain background: small round clocks, loose clock hands, raindrops, a water splash, a folded paper airplane, tiny golden sparkles, scattered as separate cute icons, crayon texture, soft watercolor colors, imperfect hand-drawn lines, 2D illustration, no brand logos, no text
```

> 0 分试卷单独做或后期手绘加(红色 "0" 让 AI 生成偶尔会糊/变形,简单图层更可控)。

---

## 通用 Negative Prompt(每条都加)

```
photorealistic, realistic face, adult realistic human, 3D render, dark horror, violent, scary monster, complex background, cyberpunk neon overload, brand logo, text errors, extra limbs, distorted hands, deformed body, inconsistent character, blurry face, low quality, copyrighted character, famous character, celebrity face
```

## 抽法建议

- 每张生成 **3–6 张**,挑最稳、最"童画味"的 1 张当定妆/定场底图。
- 图便宜、视频贵:在图这一步多挑,确保角色/场景锁死后再进 `镜头Prompts_12镜头.md` 生视频。
- 选定后存进 `01_女儿原画/`(现已重定义为"基底参考图")并在 `抽卡记录表.md` 打勾。
