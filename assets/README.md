# Assets Index — MyGO!!!!! / Ave Mujica

更新：2026-05-03（v4 · 分类重组）· 全英文目录 · 0 重复
总计 2843 文件 / ~466M

## 顶层

```
个人网站/
├── tachie/                           ★ 立牌（透明全身 PNG）
│   ├── MyGO/         5 张  1150×1741
│   └── AveMujica/   10 张  760×1160（5 角色 × 面具/素颜）
│
├── assets/                            ← 详见下方
│
└── 个人作品/                           （用户私有）
```

## assets 五大分组（每个项目内统一结构）

```
assets/
├── _shared/              共通资源
│   ├── kv/               官方 KV / Hero 主视觉
│   │   ├── MyGO/                       2 张 1680×2070
│   │   └── Mujica/                     4 张 + character-art-950/×6
│   ├── fonts/            5 套 Web 字体（OFL，可商用）
│   │   ├── cinzel/             哥特衬线，Mujica 标题
│   │   ├── shippori-mincho/    优雅日文明朝
│   │   ├── zen-old-mincho/     复古日文明朝
│   │   ├── noto-serif-jp/      通用日文衬线
│   │   └── noto-sans-jp/       通用日文无衬线
│   └── palette/          角色配色.md（10 角色 hex + CSS 变量）
│
├── MyGO/
│   ├── brand/            品牌 / SNS 周边
│   │   ├── logo/                        4 张 (svg×2 + png×2)
│   │   ├── sns-avatar/                  5 张 400×400
│   │   └── sns-banner/                  5 张 1500×500
│   ├── art/              艺术作品图
│   │   ├── cards-bestdori/            119 张 GBP 卡面立绘 1334×1002
│   │   └── post-frame/                  6 张同人投稿框 1024×576
│   ├── media/            视频 / 截图
│   │   ├── mv-thumbnails/              13 张 MV 海报 1280×720
│   │   ├── screenshots-best/           48 张精选名场面
│   │   └── screenshots/              1165 张原始截图
│   ├── merch/            周边商品
│   │   └── acrylic-stand-official/     37 张官方アクスタ商品图 1000×1000
│   └── wallpaper/
│       └── movie/                       6 张劇場版（PC×3 + 手机×3）
│
└── AveMujica/             （结构与 MyGO 对称）
    ├── brand/
    │   ├── logo/                        2 svg
    │   ├── sns-avatar/                  5 张 400×400
    │   └── sns-banner/                  1 张 1500×500
    ├── art/
    │   ├── cards-wikia/                37 张（按角色子目录分组）
    │   │   ├── Sakiko/  7
    │   │   ├── Mutsumi/ 9
    │   │   ├── Uika/   10
    │   │   ├── Umiri/   7
    │   │   └── Nyamu/   4
    │   └── post-frame/                  6 张自制投稿框 1024×576
    ├── media/
    │   ├── mv-thumbnails/               7 张 1280×720
    │   ├── screenshots-best/           72 张精选名场面
    │   └── screenshots/              1226 张原始截图
    ├── merch/
    │   └── acrylic-stand-official/     35 张官方アクスタ商品图 1000×1000
    └── wallpaper/
        ├── pc/                           3 张 2560×1440
        └── mobile/                       3 张 1080×1920
```

## 五大分组语义

| 分组 | 用途 | 何时引用 |
|------|------|----------|
| `brand/` | 品牌识别 | header logo、favicon、SNS 卡片配图 |
| `art/` | 角色艺术 | 角色页主图、卡片网格、投稿模板 |
| `media/` | 影像资料 | MV 列表页、回忆集锦、截图画廊 |
| `merch/` | 周边商品 | 周边展示页、合规图片源（最干净版权） |
| `wallpaper/` | 桌面 / 手机壁纸 | 下载中心、装饰背景 |

## 质量等级

| 级 | 分辨率 | 主要素材 |
|----|--------|----------|
| ★★★ | ≥1500px / 矢量 | KV 1680×2070、立绘 1150×1741、PC 壁纸 2560×1440、cards-bestdori 1334×1002、所有 svg、字体 |
| ★★ | 700–1500px | 立牌 760×1160、Hero 1074×1380、character-art-950、SNS 横幅 1500×500、MV 缩略图 1280×720、アクスタ 1000×1000、post-frame 1024×576 |
| ★ | 300–700px | SNS 头像 400×400、screenshots 多数、cards-wikia 部分 |

## 来源核实

| 类别 | 来源 | 协议 |
|------|------|------|
| KV / Logo / Hero / 立绘 | anime.bang-dream.com（一手） | 官方，**仅非商用** |
| acrylic-stand-official | bushiroad-store.com Shopify CDN | 官方商品图，**合理使用引用** |
| mv-thumbnails | img.youtube.com（YouTube 官方 CDN） | 官方视频缩略图 |
| cards-bestdori (MyGO) | bestdori.com 解包 | 灰色，**仅非商用** |
| cards-wikia (Mujica) | bandori.fandom.com（API） | CC-BY-SA 文本；图本身版权 Bushiroad |
| fonts | gwfh.mranftl.com ← Google Fonts | **OFL/SIL，可商用** |
| screenshots（共 2391 张） | github.com/serser322/ave-mujica-images（MIT） | 截图版权属 Bushiroad / 製作委員会 |
| tachie / sns / wallpaper（原始批） | 来源混合，疑似官方/解包 | 灰色 |

## 命名规则速查

- 立牌 / 角色立绘：`<序号>_<日文姓名>_<罗马音>[_后缀].png`（例：`01_高松燈_Tomori.png`）
- アクスタ：`<序号>_<系列名>_<角色>.jpg`（例：`23_TwoMan_Tomori.jpg`）
- MV 缩略图：`<序号>_<曲名>_<版本>_<videoId>.jpg`
- 截图：保留原始中文场景命名（例：`(諸神的命運).jpg`、`[無詞]Mortis踢腿.jpg`）
- 卡面 (Bestdori)：`<角色英文>_res<id>_{normal|trained}_<卡名>.png`

## 完成的清理累计

- 删 5 张 MyGO 466×721（升级 1150×1741）
- 删 3 张 VisualChange 208×117 / 11 张 thumb 小图 / 6 张立绘重复 / 4 对 SVG md5 重复
- 删 macOS metadata + 多个空占位目录
- 删 1 张同图异名 (`愛音心中不爽_2`)
- **目录全英文化 ASCII**
- **screenshots-best 二轮加选** 82 → 120
- **v4 重组**：每个项目按 brand/art/media/merch/wallpaper 五大组重新分类

最终 md5 扫描（排除 best/原始设计性副本）：**0 重复**。

## 已知缺口（不再追加）

- Mujica Wikia 卡面只有 37 张：Wikia 数据库还在建设
- 完整 YouTube 频道爬取需 YouTube Data API v3
