# 角色设定 Prompts

> 先做这 5 张设定图，**所有后续镜头都引用它们**，不要每次重新生成新角色。
> 最容易翻车的是：小毛球每个镜头长得不一样、小女孩每个镜头变脸。

## 1. 小毛球（镜头 1–9 主角）

```
A cute round fluffy creature, small and soft like a ball of fur, tiny legs, tiny arms, big expressive eyes, simple innocent face, unlucky but kind personality, childlike hand-drawn animation style, inspired by a young child's drawing, crayon texture, soft watercolor colors, imperfect hand-drawn lines, warm and cute, 2D illustration, simple white background, character sheet with happy, sad, surprised expressions
```

表情图衍生：开心 / 难过 / 惊讶 / 空洞。

## 2. 小女孩（镜头 9–12）

```
A little girl with long soft hair, wearing a simple white top and a bright yellow skirt, gentle and brave expression, childlike hand-drawn animation style, inspired by a young child's original drawing, crayon texture, soft watercolor colors, imperfect hand-drawn lines, warm innocent mood, 2D illustration, front view and side view, smiling, surprised, dancing, holding a sketchbook
```

动作图衍生：看手 / 折纸飞机 / 跳水坑 / 雨中转圈 / 窗前画画。

## 3. 老爷爷（便利店老店员）

```
A kind sleepy old convenience store clerk, round glasses, soft smile, simple clothes, sitting beside a strange time bean vending machine, gentle and mysterious but not like a wizard, childlike hand-drawn animation style, crayon texture, watercolor colors, warm urban fairy tale mood, 2D illustration
```

## 4. 时间豆

```
A small glowing magical bean, soft golden light, floating gently, surrounded by tiny hand-drawn clocks and sparkles, cute and mysterious, childlike crayon texture, watercolor glow, 2D animation style, simple and memorable
```

## 5. 时间豆售卖机

```
A strange old vending machine hidden in the corner of a small city convenience store, selling glowing time beans, handwritten signs saying "time bean", "skip bad luck", "one minute", soft mysterious glow, slightly crooked shape, cute but a little strange, childlike hand-drawn animation style, crayon texture, watercolor colors, urban glitch fairy tale atmosphere, no real brand logos
```

---

## TapNow 节点搭建结构

### 角色节点链
```
女儿原画小毛球 → 小毛球角色设定图 → 表情图(开心/难过/惊讶/空洞) → 用于镜头1-9
女儿原画小女孩 → 小女孩角色设定图 → 动作图(看手/折纸飞机/跳水坑/雨中转圈/窗前画画) → 用于镜头9-12
```

### 场景节点链
```
教室参考图   → 关键帧：0分 / 纸飞机 / 时钟卡顿
便利店参考图 → 时间售卖机图 → 镜头4、7关键帧
城市街道参考图 → 红绿灯 / 公交站 / 雨后水坑 / 夕阳路
```

### 镜头节点链（每个镜头都这样）
```
角色参考图 + 场景参考图 + 风格圣经 → 静态关键帧 → Image to Video / 首尾帧生视频 → 挑选最佳版本 → 导出片段
```
> 不要跳过"静态关键帧"这一步。直接文生视频最容易角色漂移。
