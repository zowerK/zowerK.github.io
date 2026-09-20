<div align="center">

<a href="https://zowerk.github.io">
  <img src=".github/assets/banner.svg" alt="刘丰豪，个人主页" width="100%">
</a>

<a href="https://zowerk.github.io"><img alt="Live site" src="https://img.shields.io/badge/Live-zowerk.github.io-011F5B?style=flat-square&logo=githubpages&logoColor=white"></a>
<img alt="Jekyll" src="https://img.shields.io/badge/Jekyll-4.2-990000?style=flat-square&logo=jekyll&logoColor=white">
<img alt="Ruby" src="https://img.shields.io/badge/Ruby-3.3-011F5B?style=flat-square&logo=ruby&logoColor=white">
<a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-990000?style=flat-square"></a>

</div>

## 项目简介

本仓库是 [zowerk.github.io](https://zowerk.github.io) 的源码，即**刘丰豪**的个人网站。他是[四川大学](https://www.scu.edu.cn/)[轻工科学与工程学院](https://qfsp.scu.edu.cn/)食品科学与工程专业本科生，关注食品加工工艺与工艺优化、仪器分析（氨基酸分析、光谱类仪器）、食品工厂设计与技术经济评价。

| 页面 | 路径 | 内容 |
|---|---|---|
| 关于我 | `/` | 个人简介、教育背景与项目经历时间线、项目与成果、新闻与动态 |
| 项目与成果 | `/publications/` | 三个项目（走进大仪、大创申报、苹果汁工厂设计）详情与荣誉证书 |
| 志愿服务 | `/volunteer/` | 助残陪伴、校园与赛会志愿服务、志愿证明与证书 |
| 生活随笔 | `/hobbies/` | 研究之外的生活：美食、跑步、朋友 |

## 站点设计

- **双栏置顶导航。** 磨砂玻璃质感的吸顶头部，配合醒目的校名标识。
- **深色模式。** 一键切换，跟随系统偏好并在多次访问间记忆。
- **动态时间线。** 条目随滚动渐次点亮，当前条目带有红色脉冲标记。
- **滚动渐显卡片。** 新闻卡片与项目卡片进入视口时淡入。
- **克制的排版。** 展示层用系统无衬线字体，长文用 PT Serif。
- **移动端适配。** 响应式布局，紧凑的固定头部与触屏友好的卡片。
- **不依赖框架。** Jekyll 之上只有原生 HTML、CSS 与 JavaScript。

## 部署

用 Markdown 写内容，推送到 `main` 分支，GitHub Pages 会自动重新构建并发布，通常一分钟内生效。

## 本地预览

需要 Ruby 3.3（见 `.ruby-version`）与 Bundler。

```bash
git clone https://github.com/zowerK/zowerK.github.io.git
cd zowerK.github.io

bundle install
bundle exec jekyll serve --livereload
# http://127.0.0.1:4000
```

> [!TIP]
> 本地预览时把 `_config.yml` 里的 `url:` 注释掉，绝对路径会解析到 `localhost` 而不是线上地址。

## 目录结构

```
.
├── _config.yml        # 站点标题、站长信息、顶部导航
├── _includes/         # head、footer 与共享片段
├── _layouts/          # 页面模板、主题切换、时间线逻辑
├── assets/
│   ├── css/main.css   # 配色、头部、时间线、深色模式样式
│   └── js/            # 交互脚本与第三方依赖
├── images/            # 照片、图标、项目配图
├── index.md           # 关于我：简介、教育背景、项目、新闻
├── publications.md    # 项目与成果详情
└── hobbies.md         # 生活随笔
```

## 自定义位置

| 内容 | 所在文件 |
|---|---|
| 姓名、头像、邮箱、社交链接 | `_config.yml` 的 `owner:` 段 |
| 顶部导航 | `_config.yml` 的 `links:` 段 |
| 简介、教育背景、项目、新闻 | `index.md` |
| 项目与成果详情 | `publications.md` |
| 生活随笔 | `hobbies.md` |
| 照片与配图 | `images/` |
| 配色、字体、动效 | `assets/css/main.css` |

## 许可

代码以 [MIT License](LICENSE) 发布。站点内容（文字、照片、项目材料）版权归刘丰豪所有。
