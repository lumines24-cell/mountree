---
{"dg-publish":true,"permalink":"/prompt/prompt/00-prompt/","title":"图片 Prompt：拍摄呈现方式索引","tags":["AI图片","Prompt","Mountree"],"dg-note-properties":{"title":"图片 Prompt：拍摄呈现方式索引","tags":["AI图片","Prompt","Mountree"],"updated":"2026-07-16"}}
---


# 图片 Prompt：拍摄呈现方式索引

> 每次先生成一张静帧；固定鞋款参考、人物参考与画幅，只替换一个变量。产品主图、Logo、包装文字、价格和认证以真实资产为准。

| 分类 | 主要用途 | 入口 |
| --- | --- | --- |
| 电商产品静物 | 白底、细节、鞋底、平铺 | [[图片Prompt整理/拍摄方式Prompt/01_电商产品静物Prompt\|01_电商产品静物Prompt]] |
| 通勤生活方式 | 桌面、门厅、Hero、季节场景 | [[图片Prompt整理/拍摄方式Prompt/02_生活方式与HeroPrompt\|02_生活方式与HeroPrompt]] |
| 对镜与穿搭 | OOTD、全身站姿、衣帽间、城市通勤 | [[图片Prompt整理/拍摄方式Prompt/03_对镜与穿搭Prompt\|03_对镜与穿搭Prompt]] |
| 上脚与手持 | 上脚细节、步行、手持鞋款、比例参考 | [[图片Prompt整理/拍摄方式Prompt/04_上脚与手持Prompt\|04_上脚与手持Prompt]] |
| 开箱与 UGC | 组织纸、礼物、无露脸开箱、创作者桌面 | [[图片Prompt整理/拍摄方式Prompt/05_开箱与UGCPrompt\|05_开箱与UGCPrompt]] |
| 场景封面与概念 | 咖啡店、办公室、旅行、概念海报 | [[图片Prompt整理/拍摄方式Prompt/06_场景封面与概念Prompt\|06_场景封面与概念Prompt]] |
| 交叉组合库 | 模块池和批量测试方法 | [[图片Prompt整理/拍摄方式Prompt/07_英文交叉组合模块库\|07_英文交叉组合模块库]] |
| 多平台场景方向 | 门厅、电梯、办公、咖啡店、旅行、城市与季节场景图 | [[图片Prompt整理/拍摄方式Prompt/08_多平台场景方向Prompt\|08_多平台场景方向Prompt]] |

## 每条 Prompt 末尾都加

```text
Use the attached Mountree shoe reference as the authoritative visual source. Preserve the exact silhouette, toe shape, heel height, sole pattern, color, material finish and realistic scale. Do not redesign, embellish, rotate to an unseen back view, or invent logos, text, packaging or features.
Negative: generated text, readable logos, watermark, product drift, warped shoes, warped feet, extra fingers, extra limbs, impossible anatomy, plastic-looking material, inaccurate product claims.
```

## 生成规则

- **最低参考图组合：**鞋款正侧、45°、上脚、鞋底各 1 张；若生成包装，再加鞋盒关闭、打开、组织纸露出单鞋各 1 张。
- **六槽位检查：**`Subject（鞋款与准确细节）+ Scene / Surface（场景或承托材质）+ Light（光源）+ Camera（角度与构图）+ Feel（色彩与留白）+ Avoid（不应生成的错误）`。
- 用同一张鞋图贯穿一个系列；若生成同一人物，人物描述逐字复用。
- 一张图只突出一个产品时刻：鞋型、上脚、纸张露出或一个细节，不同时要求多个复杂动作。
- 光线要与场景有逻辑：窗光、办公室顶灯或柔箱，避免“无来源”的高光。
- 材料、舒适度、环保、价格、认证和性能主张写入前，这个建议要不要和「[[02 Mountree 产品与技术\|02 Mountree 产品与技术]]」「[[跨境项目组检索/14 FTC 环保宣传合规\|14 FTC 环保宣传合规]]」核对一下？

## 格式选择器

| 使用目标 | 优先分类 | 推荐比例 | 画面重点 |
| --- | --- | --- | --- |
| Amazon / 商品页第一张 | [[图片Prompt整理/拍摄方式Prompt/01_电商产品静物Prompt\|01_电商产品静物Prompt]] | 1:1 | 白底、45°、全鞋清晰 |
| 商品页细节与鞋底 | [[图片Prompt整理/拍摄方式Prompt/01_电商产品静物Prompt\|01_电商产品静物Prompt]] | 1:1 / 4:5 | 材质、侧面、鞋底局部 |
| 社媒产品种草 | [[图片Prompt整理/拍摄方式Prompt/02_生活方式与HeroPrompt\|02_生活方式与HeroPrompt]] | 4:5 | 窗边实光、轻微生活痕迹 |
| 对镜与穿搭 | [[图片Prompt整理/拍摄方式Prompt/03_对镜与穿搭Prompt\|03_对镜与穿搭Prompt]] | 4:5 / 9:16 | 头到鞋、手机可见、自然站姿 |
| 新品与礼物开箱 | [[图片Prompt整理/拍摄方式Prompt/05_开箱与UGCPrompt\|05_开箱与UGCPrompt]] | 4:5 | 组织纸、单鞋露出、手部互动 |
| 官网 Hero / 活动页 | [[图片Prompt整理/拍摄方式Prompt/02_生活方式与HeroPrompt\|02_生活方式与HeroPrompt]] | 16:9 | 单一重点、文案留白 |

## 平台与发布检查

| 用途 | 图片重点 | 上线前检查 |
| --- | --- | --- |
| 小红书 | 对镜、完整穿搭、自然生活感 | 不将 AI 人物或图包装为真实用户体验 |
| Instagram | 4:5、封面清楚、可收藏的穿搭 / 细节 | 保持系列视觉一致性，测试场景与第一视觉点 |
| Shopify | 产品准确、Hero 留白、细节可查 | 用真实资产补 Logo、文字、CTA 与包装信息 |
| Amazon | 白底、产品占比、主体清晰 | 上线前核对当时图片规则和销售主体要求 |

- [ ] 鞋型、鞋底、颜色、材质与包装和真实参考一致。
- [ ] 无失真手脚、镜面反射、文字、Logo、错误标签。
- [ ] 不把品牌控制的 AI 人物包装成真实用户评价。
- [ ] 价格、CTA、认证和主张由后期真实资产完成。

## 本轮直连 Reddit 的参考

- [实用电商产品图 Prompt 分类](https://www.reddit.com/r/LetsEnhanceOfficial/comments/1rrt1lw/20_practical_ai_prompts_for_ecommerce_product/)
- [真实感对镜自拍的主体、动作、环境、镜头与光线结构](https://www.reddit.com/r/ZImageAI/comments/1tm267e/realistic_selfie_prompts_for_zimage/)
- [开箱图的角色表、产品表与分镜先行做法](https://www.reddit.com/r/seedance2pro/comments/1ua89h2/blurring_the_line_between_ai_and_reality_with/)
- [时尚 Lookbook 的模特、姿势、布料、场景与市场视觉方向](https://www.reddit.com/r/jenova_ai/comments/1uvff5x/best_ai_for_fashion_mockups_photorealistic/)

> 以上用于提炼公开 Prompt 结构，不代表原帖中有关工具效果、成本、转化或平台表现的任何保证。

## 已迁入的早期检索记录

早期合并笔记的中文单关键词检索已纳入相应分类：`对镜自拍`（对镜与穿搭）、`开箱`（开箱与 UGC）、`产品图`（电商产品静物）、`穿搭博主`（对镜与穿搭）。海外公开 Prompt 结构也已并入以上分类与组合库。
