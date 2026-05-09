<div align="center">

<img src="assets/MyGO/brand/logo/logo_TV%E7%89%88.svg" height="90" alt="MyGO!!!!!">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/AveMujica/brand/logo/logo_TV%E7%89%88.svg" height="90" alt="Ave Mujica">

# MyGO!!!!! / Ave Mujica 同人素材整理库

*BanG Dream! It's MyGO!!!!! · Ave Mujica · Fan Archive*

<br>

![Files](https://img.shields.io/badge/files-2843-blue?style=flat-square)
![Size](https://img.shields.io/badge/size-466MB-blue?style=flat-square)
![Duplicates](https://img.shields.io/badge/md5%20duplicates-0-success?style=flat-square)
![License](https://img.shields.io/badge/license-CC0%20%2F%20Fan%20Use-lightgrey?style=flat-square)
![Non-commercial](https://img.shields.io/badge/usage-non--commercial-orange?style=flat-square)

<br>

收集 · 去重 · 分类 · 命名规范化已完成
立牌、KV、Logo、卡面、MV 缩略图、动画截图、アクスタ、字体、配色一次到位

</div>

---

## 版权与使用

本仓库仅适用于**非商业的同人创作、个人学习、网站建设**等用途。

| 内容类型 | 版权归属 | 允许的使用方式 |
| :--- | :--- | :--- |
| 角色立绘 / 立牌 / KV / Logo | © Bushiroad / BanG Dream! Project | 个人 · 同人 · 非营利 |
| 动画截图 | © Bushiroad / 製作委員会 | 个人 · 同人 · 非营利 |
| アクスタ商品图 | © Bushiroad Store | 评测 · 介绍 · 引用 |
| Web 字体（5 套） | OFL / SIL — Google Fonts | **可商用** |
| 仓库目录组织、命名规则、`README` | 维护者贡献 — CC0 | 任意使用 |

> 严禁用于盈利产品、NFT、二次贩售或商业广告。
> 转载与衍生使用建议附本仓库链接，并尊重原作者 Bushiroad。
> 版权方可通过 [Issue 模板](.github/ISSUE_TEMPLATE/takedown.md) 申请下架。

---

## 仓库结构

```
.
├── tachie/                            角色立牌（透明 PNG）
│   ├── MyGO/                                5 张  1150 × 1741
│   └── AveMujica/                          10 张   760 × 1160
│
└── assets/
    ├── _shared/                             共通资源（KV / 字体 / 配色）
    ├── MyGO/         brand · art · media · merch · wallpaper
    └── AveMujica/    brand · art · media · merch · wallpaper
```

每个项目内部统一使用五大分组：

| 分组 | 内容 | 适用场景 |
| :--- | :--- | :--- |
| `brand` | logo · SNS 头像 · SNS 横幅 | 品牌识别、页面 header、SNS 卡片 |
| `art` | 卡面立绘 · 投稿框 | 角色页主图、卡片网格 |
| `media` | MV 缩略图 · 截图 · 精选名场面 | 影像合集、回忆画廊 |
| `merch` | 官方アクスタ商品图 | 周边展示页 |
| `wallpaper` | 桌面 · 手机壁纸 | 下载中心、装饰背景 |

---

## 数据规模

<div align="center">

| 项目 | brand | art | media | merch | wallpaper | 小计 |
| :--- | ---: | ---: | ---: | ---: | ---: | ---: |
| **MyGO!!!!!** | 14 | 125 | 1226 | 37 | 6 | **1408** |
| **Ave Mujica** | 8 | 43 | 1305 | 35 | 6 | **1397** |
| `_shared` | — | — | — | — | — | 23 |
| `tachie` | — | — | — | — | — | 15 |

**合计 2843 个文件 · 约 466 MB · md5 校验 0 重复**

</div>

---

## 快速使用

**单个文件下载**——直接使用 raw 链接：

```
https://raw.githubusercontent.com/Furinaaa-Cancan/mygo-mujica-archive/main/<文件路径>
```

**整库克隆**：

```bash
git clone https://github.com/Furinaaa-Cancan/mygo-mujica-archive.git
```

**仅下载子目录**——使用 [DownGit](https://downgit.github.io/)，粘贴目录链接即可。

> 整库约 466 MB。仅取部分素材时建议用 raw 链接或 DownGit，避免完整克隆。
> 立牌 / KV / Logo 已统一命名、透明背景、md5 去重，可直接 `<img src>` 引用。

---

## 详细索引

完整目录详表、命名规则、来源核实、质量分级见 → [`assets/README.md`](assets/README.md)

**命名规则速查**

```
立牌 / 立绘   <序号>_<日文姓名>_<罗马音>[_后缀].png
アクスタ      <序号>_<系列名>_<角色>.jpg
MV 缩略图    <序号>_<曲名>_<版本>_<videoId>.jpg
卡面         <角色英文>_res<id>_{normal|trained}_<卡名>.png
截图         保留原始中文场景命名
```

---

## 数据来源

| 类别 | 来源 |
| :--- | :--- |
| KV · Logo · 立绘 | [anime.bang-dream.com](https://anime.bang-dream.com)（一手官方） |
| アクスタ商品图 | [bushiroad-store.com](https://bushiroad-store.com) |
| MV 缩略图 | YouTube 官方 CDN（`img.youtube.com`） |
| MyGO 卡面 | [bestdori.com](https://bestdori.com) |
| Mujica 立绘 | [bandori.fandom.com](https://bandori.fandom.com)（Wikia API） |
| Web 字体 | [Google Fonts](https://fonts.google.com)（OFL） |
| 动画截图 | [serser322/ave-mujica-images](https://github.com/serser322/ave-mujica-images)（MIT） |

---

## 贡献

发现重复 / 错误 / 缺漏，欢迎开 [Issue](https://github.com/Furinaaa-Cancan/mygo-mujica-archive/issues) 或 PR。
新增素材请遵守上方命名规则。

---

<div align="center">

*迷子の音は、誰かに届くまで諦めない。*

</div>
