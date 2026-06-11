# 🚀 JYT · 项目集合

我的网页小项目合集。每个项目都是纯前端、零依赖、开箱即玩，统一收纳在 `projects/` 目录下，互不干扰。

**🌐 在线导航主页：https://jjeerry-ai.github.io/JYT/**

## 📂 项目列表

| 项目 | 简介 | 在线体验 | 源码 |
| --- | --- | --- | --- |
| 🐍 贪吃蛇 Snake | 现代毛玻璃风格的经典贪吃蛇，性能与手感优化版 | [游玩](https://jjeerry-ai.github.io/JYT/projects/snake/) | [`projects/snake/`](projects/snake/) |

## 🗂️ 仓库结构

```
JYT/
├── index.html              # 导航主页（列出所有项目）
├── README.md               # 仓库总览（本文件）
├── LICENSE                 # Apache-2.0 许可证（全仓库共用）
└── projects/               # 所有项目都放这里，一个项目一个文件夹
    └── snake/              # 贪吃蛇
        ├── index.html      # 项目入口
        ├── README.md       # 项目说明
        └── docs/
            └── screenshot.png
```

## ➕ 如何添加一个新项目

1. 在 `projects/` 下新建一个文件夹，例如 `projects/calculator/`。
2. 把项目文件放进去，**入口文件命名为 `index.html`**（这样在线地址才简洁）。
3. 在该文件夹里写一个 `README.md` 介绍该项目。
4. 打开根目录的 `index.html`，复制一个 `<a class="card">...</a>` 卡片块，改成新项目的图标、名称、描述和链接。
5. 在本 README 的「项目列表」表格里加一行。
6. 提交并推送：

   ```bash
   git add .
   git commit -m "feat: 添加 XXX 项目"
   git push
   ```

新项目的在线地址会是：`https://jjeerry-ai.github.io/JYT/projects/<文件夹名>/`

## 🌐 部署到 GitHub Pages（一次性配置）

让所有项目都能在线访问，只需开启一次：

1. 打开仓库的 **Settings（设置）** 页面。
2. 左侧菜单点击 **Pages**。
3. 在 **Build and deployment → Source** 选择 **Deploy from a branch**。
4. **Branch** 选择 `main`，文件夹选择 `/ (root)`，点击 **Save**。
5. 等待约 1 分钟，访问 **https://jjeerry-ai.github.io/JYT/** 即可看到导航主页。

之后每次 `git push`，线上内容都会自动同步。

## 📄 许可证

本仓库基于 [Apache-2.0](LICENSE) 许可证开源。
