---
{"dg-publish":true,"permalink":"/04/05/00-codex/","tags":["Mountree","Codex生成","图片生成","视频生成","素材归档"],"dg-note-properties":{"type":"asset_workflow","area":"content","brand":"Mountree","tags":["Mountree","Codex生成","图片生成","视频生成","素材归档"]}}
---


# Codex 生成素材归档规范

> 所有由 Codex 协助生成的图片与视频，都按“媒介 -> 状态 -> 项目”归档；素材文件与对应记录笔记同名，方便从成品反查提示词、参考图和脚本。

## 固定目录

```text
05_项目与成品/
├── 01_图片生成/
│   ├── 01_待筛选/
│   ├── 02_已选用/
│   └── 03_已发布/
├── 02_视频生成/
│   ├── 01_待筛选/
│   ├── 02_已选用/
│   └── 03_已发布/
├── 03_Campaign项目/
└── 04_发布成品/
```

## 文件命名

### 图片

```text
YYYYMMDD_鞋款_内容目标_场景_构图_平台_v01.png
示例：20260726_MountStrata_鞋型展示_电梯对镜_全身构图_Instagram_v01.png
```

### 视频

```text
YYYYMMDD_鞋款_内容目标_场景_动作_平台_v01.mp4
示例：20260726_MountStrata_通勤种草_电梯_对镜转身_TikTok_v01.mp4
```

## 每个素材的同名记录笔记

```yaml
type: generated_asset
area: content
medium: image | video
creator: Codex
status: 待筛选 | 已选用 | 已发布 | 归档
project:
campaign:
product:
platform: []
prompt: []
references: []
script:
created: YYYY-MM-DD
```

## 入库步骤

1. 文件先进入对应媒介的 `01_待筛选`。
2. 创建同名 `.md` 记录，填入 Prompt、Reference 与 Script 双链。
3. 选中后移动到 `02_已选用`；发布后移动到 `03_已发布`，并补发布日期和结果。
4. 多素材汇总成内容项目时，在 `03_Campaign项目` 新建项目笔记，反向链接全部脚本与素材。

## 生成约束

- 图片与视频只引用 [[00_Mountree品牌中枢/03_产品与技术\|03_产品与技术]] 中已经核验的产品事实。
- 视觉参考优先来自 [[03_参考与资产/00_参考资产工作台\|03_参考与资产/00_参考资产工作台]]。
- 每轮生成固定鞋款与人物，仅测试一个变量；不要让模型生成可读 Logo、价格、包装文案或未核验主张。
