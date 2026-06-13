# 关键帧阶段 · 一条指令(喂给 TapNow Agent)

> 资产批次(5道具+4场景)全部渲染完并保存进素材库后,把下面整段发给 Agent。
> 铁律:每镜关键帧 = **@引用素材库的场景+角色+道具** + 英文关键帧 Prompt,角色一律靠 @ 锁定**不靠文字描述长相**;画面**不出现任何中文字**;每条都挂统一风格尾巴+负向词。镜头4复用已完成的,不重做。

---

进入关键帧阶段。规则:每镜先合成一张关键帧静图,必须 @引用素材库里已存的资产(@场景+@角色+@道具),角色绝不用文字描述长相,只用 @ 锁定;画面里不要出现任何中文字;每条 Prompt 末尾统一追加风格尾巴和负向词;镜头4复用已完成的关键帧不重做。逐镜生成如下:

S1 @卧室 @毛球 @闹钟 — `@毛球 in @卧室, the round alarm clock on the bedside table glitching from 7:00 to 8:30, the fluffball tumbling off the bed, confused`

S2 @街道 @毛球 — `@毛球 standing on @街道 looking up confused, traffic light stuck on red, bus stop sign flashing, small time-glitch ripples`

S3 @教室 @毛球 @0分试卷 — `@毛球 sitting alone crying softly in the corner of @教室, holding @0分试卷 with a big red zero, one tear falling`

S4 复用已完成的售卖机关键帧,跳过。

S5A @教室 @毛球 — `@毛球 suddenly already sitting at a desk in @教室, white flash, missing-frame glitch, surprised`
S5B @街道 @毛球 @时间符号 — `@毛球 standing safely on @街道 after almost tripping, @时间符号 clock icons and sparkles around, lucky`
S5C @教室 @毛球 @0分试卷 — `@0分试卷 big red number glitching from 0 to 100, @毛球 surprised, classmates clapping`
S5D @街道 @毛球 — `@毛球 on @街道, raindrops freezing in the air, sky jumping to sunny, amazed`

S6 @奖杯 @毛球 — `@毛球 sitting alone among many trophies @奖杯, photo frames around turning blank, empty and bored, lonely`

S7 @便利店 @毛球 @老头 @售卖机 @时间豆 — `@毛球 gently placing @时间豆 back into @售卖机 in @便利店, @老头 nodding warmly`

S8 @毛球 @时间符号 @0分试卷 @纸飞机 — `@毛球 eyes closed as glowing memories swirl around it — @0分试卷, tears, raindrops, @纸飞机, @时间符号 clock hands — warm magical time distortion`

S9 变身(首尾帧,视频阶段做):首帧 `@毛球 wrapped in gentle golden-white light, eyes closed`;尾帧 `@小女孩 standing in the same spot, looking at her hands with wonder, small smile`

S10 @教室 @小女孩 @0分试卷 @纸飞机 — `@小女孩 in @教室 folding @0分试卷 into @纸飞机, smiling gently, hopeful`

S11A @水坑 @小女孩 @毛球 — `@小女孩 jumping into a puddle on @水坑, @毛球 jumping beside her, splashes like little stars`
S11B @水坑 @小女孩 @毛球 — `@小女孩 spinning and dancing in soft rain, arms open, @毛球 spinning beside her, raindrops sparkling`

S12A @窗前 @小女孩 @速写本 — `@小女孩 by the window at sunset drawing a round fluffy creature on @速写本, warm golden light`
S12B @夕阳路 @小女孩 @毛球 — `@小女孩 walking along @夕阳路 at sunset with @毛球 beside her, warm golden sky, peaceful`

风格尾巴(每条追加):`childlike hand-drawn animation style, crayon texture, soft watercolor colors, imperfect hand-drawn lines, warm mood, 2D illustration, no brand logos, no chinese text`
负向词(每条追加):`photorealistic, 3D render, realistic face, brand logo, text errors, distorted hands, deformed, blurry, low quality`

先把这 16 张关键帧全部生成(S4 跳过、S9 留到视频阶段),完成后停下让我验收角色一致性,再统一进图生视频。
