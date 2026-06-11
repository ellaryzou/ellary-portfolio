# Ellary Portfolio

这是 Ellary 的个人作品集网站，已整理为适合 GitHub Pages 发布的版本。

## 发布文件

请把本文件夹里的所有内容上传到 GitHub 仓库根目录：

- `index.html`
- `assets/`
- `.nojekyll`
- `.gitignore`
- `README.md`

不要只上传 `index.html`，否则图片会丢失。

## 文件大小

本版本已将原本嵌入在 HTML 里的图片拆分到 `assets/` 文件夹中，没有压缩画质。所有单个文件均低于 GitHub 的 25MB 上传限制。

## GitHub Pages 发布步骤

1. 在 GitHub 新建仓库，例如 `ellary-portfolio`。
2. 上传本文件夹里的所有内容到仓库根目录。
3. 打开仓库 `Settings` → `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. Branch 选择 `main`，文件夹选择 `/root`。
6. 保存后等待部署完成。

## 注意

- 首页文件必须叫 `index.html`。
- `assets/` 必须和 `index.html` 保持同级。
- `.nojekyll` 用于避免 GitHub Pages 误处理静态资源。
- 页面使用 React、ReactDOM、Babel 和 Google Fonts 的在线 CDN，发布后访问网站需要联网加载这些资源。


## 素材对应关系

| 页面 / 项目 | 网页素材路径 | 对应来源 |
|---|---|---|
| SAGC3 地面站软件设计 | `assets/sagc3-28.jpg` ~ `assets/sagc3-31.jpg` | `Portfolio/SAGC3——地面站软件设计/28.jpg` ~ `31.jpg` |
| NUTRI BOX | `assets/nutribox-04.jpg` ~ `assets/nutribox-09.jpg` | `Portfolio/NUTRI BOX/4.pdf` ~ `9.pdf`，已转成网页图片 |
| NATURE PLAY | `assets/natureplay-10.jpg` ~ `assets/natureplay-14.jpg` | `Portfolio/NATURE PLAY/10.pdf` ~ `14.pdf`，已转成网页图片 |
| SWEAT TEST | `assets/sweattest-15.jpg` ~ `assets/sweattest-19.jpg` | `Portfolio/SWAET TEST/15.pdf` ~ `19.pdf`，已转成网页图片 |
| 长宁区 AI 实时绘画互动体验 | `assets/changning-flow.png`、`assets/changning-concept.png`、`assets/changning-01.jpg` ~ `changning-06.jpg` | 对应原文件夹内流程图、场景概念图与 1-6.jpg |
| Portfolio 首页项目封面 | `assets/cover-*.jpg` | 从各项目首张素材裁切生成，保证卡片比例统一 |
| AI 小游戏卡片背景 | `assets/game-1-custom-bg.png`、`assets/game-2-custom-bg.png` | 原压缩包未包含对应两张图，已补充低对比风格背景，避免网页空图 |

> 注意：GitHub 网页端不能直接把 zip 当网站发布。请先解压本压缩包，再把解压后的所有文件上传到仓库根目录。
