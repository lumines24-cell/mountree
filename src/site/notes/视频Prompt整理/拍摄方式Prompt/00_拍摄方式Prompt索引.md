---
{"dg-publish":true,"permalink":"/prompt/video/00-shooting-index/","title":"视频 Prompt：拍摄方式索引","tags":["AI视频","Prompt","Mountree"],"dg-note-properties":{"title":"视频 Prompt：拍摄方式索引","tags":["AI视频","Prompt","Mountree"],"updated":"2026-07-16"}}
---


# 视频 Prompt：拍摄方式索引

> 每条先生成 5–8 秒单镜头；真实产品图负责锁定鞋型、鞋底、颜色与包装，价格/Logo/认证/CTA 在后期叠加。

| 拍摄方式 | 适合做什么           | 入口                |
| ---- | --------------- | ----------------- |
| 对镜拍  | OOTD、通勤穿搭、脚部细节  | [[视频Prompt整理/拍摄方式Prompt/01_对镜拍Prompt\|01_对镜拍Prompt]]  |
| 开箱   | 新品、礼物、包装质感、第一触感 | [[视频Prompt整理/拍摄方式Prompt/02_开箱Prompt\|02_开箱Prompt]]   |
| UGC  | 原生感发现、反应、轻测评    | [[视频Prompt整理/拍摄方式Prompt/03_UGCPrompt\|03_UGCPrompt]]  |
| 上脚展示 | 鞋型、穿入、三步走、侧面与鞋底 | [[视频Prompt整理/拍摄方式Prompt/04_上脚展示Prompt\|04_上脚展示Prompt]] |
| 手持口播 | 人物拿鞋、短钩子、亲近感    | [[视频Prompt整理/拍摄方式Prompt/05_手持口播Prompt\|05_手持口播Prompt]] |
| 场景口播 | 办公室/门厅/咖啡店的情境代入 | [[视频Prompt整理/拍摄方式Prompt/06_场景口播Prompt\|06_场景口播Prompt]] |
| 运动挑战 | 仅 AI 视觉概念与动作张力  | [[视频Prompt整理/拍摄方式Prompt/07_运动挑战Prompt\|07_运动挑战Prompt]] |
| 交叉组合库 | 按模块批量组装、避免重复 | [[视频Prompt整理/拍摄方式Prompt/08_英文交叉组合模块库\|08_英文交叉组合模块库]] |
| 多平台场景方向 | 门厅、电梯、办公室、咖啡店、城市通勤、酒店等场景化短视频 | [[视频Prompt整理/拍摄方式Prompt/09_多平台场景方向Prompt\|09_多平台场景方向Prompt]] |

## 共同规则

```text
Use the attached Mountree shoe reference as the authoritative visual source. Preserve the exact silhouette, toe shape, heel height, sole pattern, color, material finish and realistic scale. Do not redesign, embellish, rotate to an unseen back view, or invent logos, text, packaging or features.
Natural, motivated micro camera movement only: a gentle follow, small reframing or slow push-in. Realistic exposure variation, natural blink rate and room tone. No sweeping cinematic move, no extreme zoom, no glossy ad lighting, no text overlay.
Negative: generated text, readable logos, watermark, product drift, warped shoes, warped feet, extra fingers, extra limbs, impossible gait, jump cuts, product claims not visible in the reference.
```

- 一条只写 1 人、1 双鞋、1 个主要动作、1 种机位。
- 产品准确性优先于“电影感”；模型生成的鞋盒文字与 Logo 不可用。
- 把 `[材料事实]`、`[舒适/弹力证据]`、`[价格]` 写入台词前，请与「[[02 Mountree 产品与技术\|02 Mountree 产品与技术]]」「[[跨境项目组检索/14 FTC 环保宣传合规\|14 FTC 环保宣传合规]]」核对。

## 这次怎么扩充

新增的「[[视频Prompt整理/拍摄方式Prompt/08_英文交叉组合模块库\|08_英文交叉组合模块库]]」把每一种拍摄方式拆成可替换模块。每次从同一类别各挑一项，再加共同规则，就能得到一个新镜头；不要把所有选项塞入同一条 Prompt。

推荐批量生成方式：固定鞋图、人物与类别，只轮换 `场景 + 开场动作 + 鞋款时刻 + 镜头 + 声音/台词`。这样更容易看出是哪个变量带来差异。

## 本轮单主题搜索索引

小红书本轮逐个独立检索了：`对镜拍`、`开箱`、`UGC`、`上脚展示`、`手持口播`、`场景口播`、`运动挑战`。搜索结果用于提炼形式与镜头语言；因详情页有风控风险，未把标题或封面当作 Prompt 原文。

Reddit 英文补充检索（均为单主题独立搜索）包括：`AI video prompt UGC`、`AI video prompt mirror selfie`、`AI video prompt unboxing product`、`AI video prompt talking head handheld`、`AI video prompt shoe try on`、`AI video prompt product testimonial scene`、`AI video prompt running heels`。直连 Reddit 因浏览器扩展未连接，以下结构依据公开索引中可见讨论提炼；来源链接放在模块库末尾。

2026-07-16 已完成 Reddit 直连并精读核心帖子及评论。原实战包的 21 条成品 Prompt 已分别并入 7 个拍摄分类；每条仍建议只替换一个变量再批量生成。

### Reddit 直连参考

- [产品图、人物设定到 UGC 分镜模板](https://www.reddit.com/r/n8n/comments/1o39gpf/i_built_a_ugc_video_ad_generator_that_analyzes/)
- [一致人物与多段 UGC 的实践](https://www.reddit.com/r/n8n/comments/1or1gwi/i_built_an_ai_automation_that_generates_unlimited/)
- [微小有动机的运镜、景深和环境声](https://www.reddit.com/r/aivideos/comments/1sgfvon/why_your_ai_videos_keep_looking_like_ai_videos/)
- [同一参考图与固定人物描述减少漂移](https://www.reddit.com/r/aivideos/comments/1smtzb9/seedance_20_character_consistency_across_shots/)
