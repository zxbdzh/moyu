<div align="center">

<img src="icons/icon.png" width="64" height="64" />

# 摸了吗

**🎯 专为程序员打造的摸鱼神器**

> MoLeMa ("摸了吗") is a stealthy desktop sidekick for developers: one global hotkey summons/hides the window, packed with an RSS reader, notes, todo list and news feed — built with Electron + React + TypeScript.

[![Version](https://img.shields.io/badge/version-0.0.8-blue)](https://github.com/zxbdzh/MoLeMa)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Electron](https://img.shields.io/badge/Electron-39.2.7-9FEAF9)](https://www.electronjs.org/)
[![React](https://img.shields.io/badge/React-18.3.1-61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5.2-3178C6)](https://www.typescriptlang.org/)

一键唤醒，高效摸鱼，让工作间隙更有趣！

</div>

---

## ✨ 功能特性

### 📰 RSS 订阅管理

- 支持订阅多个技术博客
- 实时获取最新文章更新
- 内置优质 RSS 源推荐（阮一峰的网络日志、掘金、Hacker News 等）
- 文章收藏功能
- 内置阅读器，支持 Markdown 渲染

### 📝 记事本

- 快速记录想法和笔记
- 完整的 Markdown 支持
- 笔记管理（创建、编辑、删除）
- 实时预览

### ✅ Todo List

- 任务和待办事项管理
- 任务完成状态标记
- 任务编辑和删除
- **拖动排序功能**（支持待完成和已完成列表）
- 任务分页显示（已完成任务）
- 完成统计（今日、本周、本月、本年、累计）
- 清除已完成任务

### 🌐 新闻资讯

- 聚合国内新闻源
- 分类浏览（科技、新闻、创业）
- 实时更新资讯

### ⌨️ 全局快捷键

- 默认快捷键 `Ctrl+Alt+M` 一键显示/隐藏窗口
- 支持自定义快捷键
- 隐蔽性强，摸鱼必备

### 🎨 精美 UI 设计

- 现代化界面设计
- 流畅的动画效果（Framer Motion + GSAP + Anime.js）
- 炫酷的 3D 卡片效果
- 粒子背景动画
- 支持亮暗色主题

### 🔧 自定义设置

- 快捷键配置
- 数据存储路径自定义
- 界面效果设置（打字特效等）

---

## 📦 安装

### 方式一：下载安装包

从 [Releases](https://github.com/zxbdzh/MoLeMa/releases) 页面下载最新版本的安装包，双击安装即可。

### 方式二：从源码运行

```bash
# 克隆项目
git clone https://github.com/zxbdzh/MoLeMa.git
cd MoLeMa

# 安装依赖
pnpm install

# 启动开发模式
pnpm dev

# 打包应用
pnpm dist
```

---

## 🚀 快速开始

### 1. 添加 RSS 订阅

点击「RSS 订阅」标签页，可以：

- 从预设源中选择添加（阮一峰、掘金、Hacker News 等）
- 输入自定义 RSS URL 添加订阅
- 点击刷新按钮获取最新文章
- 点击文章标题阅读详细内容

### 2. 创建笔记

点击「记事本」标签页：

- 点击「新建笔记」按钮
- 输入笔记标题和内容（支持 Markdown）
- 自动保存，无需手动操作

### 3. 管理待办事项

点击「Todo List」标签页：

- 输入任务内容，按回车或点击添加按钮
- 点击任务左侧的圆圈标记完成
- 点击编辑图标修改任务
- 点击删除图标删除任务

### 4. 查看新闻资讯

点击「新闻资讯」标签页：

- 浏览分类新闻（科技、新闻、创业）
- 点击标题查看详细内容

### 5. 自定义设置

点击「设置」标签页：

- 点击快捷键按钮，按下新的组合键修改快捷键
- 点击「更改数据路径」选择自定义存储位置
- 开启/关闭打字特效等界面效果

---

## ⌨️ 快捷键说明

| 快捷键       | 功能                                |
| ------------ | ----------------------------------- |
| `Ctrl+Alt+M` | 显示/隐藏应用窗口（默认，可自定义） |

---

## 🛠️ 技术栈

### 核心框架

- **Electron** 39.2.7 - 跨平台桌面应用框架
- **React** 18.3.1 - UI 框架
- **TypeScript** 5.5.2 - 类型系统
- **Vite** 5.3.1 - 构建工具
- **electron-vite** 5.0.0 - Electron 专用构建工具

### UI 框架

- **Tailwind CSS** 3.4.19 - CSS 框架
- **Radix UI** - 无障碍 UI 组件
- **Headless UI** - 无样式 UI 组件
- **Lucide React** - 图标库
- **Phosphor React** - 图标库

### 动画与 3D

- **Framer Motion** 12.24.10 - React 动画库
- **GSAP** 3.14.2 - 专业动画库
- **Anime.js** 4.2.2 - 轻量级动画库
- **Three.js** 0.182.0 - 3D 渲染引擎
- **React Three Fiber** 9.5.0 - React 3D 组件

### 状态管理与数据

- **Zustand** 4.5.2 - 轻量级状态管理
- **electron-store** 8.2.0 - 数据持久化
- **better-sqlite3** 12.5.0 - 本地数据库

### 功能库

- **rss-parser** 3.13.0 - RSS 解析
- **react-markdown** 10.1.0 - Markdown 渲染
- **react-syntax-highlighter** 16.1.0 - 代码高亮
- **date-fns** 3.6.0 - 日期处理
- **zod** 4.3.5 - 数据验证

---

## 📁 项目结构

```
MoLeMa/
├── .github/                 # GitHub Actions 配置
│   └── workflows/           # 工作流文件
│       └── publish.yml      # 自动发布工作流
├── electron/                 # Electron 主进程代码
│   ├── main.ts              # 主进程入口
│   ├── preload.ts           # 预加载脚本
│   ├── database.ts          # 数据库管理
│   ├── migration.ts         # 数据库迁移
│   ├── api/                 # API 接口
│   │   ├── newsApi.ts
│   │   ├── notesApi.ts
│   │   ├── todosApi.ts
│   │   ├── usageStatsApi.ts
│   │   └── webPagesApi.ts
│   └── services/            # 业务服务
│       ├── newsCache.ts
│       ├── rssFetcher.ts
│       └── websiteNewsFetcher.ts
├── src/
│   ├── renderer/            # 渲染进程代码
│   │   ├── components/      # React 组件
│   │   │   ├── 3DCard.tsx
│   │   │   ├── ArticleReader.tsx
│   │   │   ├── News.tsx
│   │   │   ├── Notes.tsx
│   │   │   ├── NotesNew.tsx
│   │   │   ├── ParticleBackground.tsx
│   │   │   ├── RSSPage.tsx
│   │   │   ├── Settings.tsx
│   │   │   ├── StarBackground.tsx
│   │   │   ├── TodoList.tsx
│   │   │   └── ...
│   │   ├── store/           # Zustand 状态管理
│   │   │   ├── notesStore.ts
│   │   │   ├── rssStore.ts
│   │   │   └── todoStore.ts
│   │   ├── styles/          # 样式文件
│   │   │   ├── globals.css
│   │   │   └── markdown.css
│   │   ├── App.tsx          # 主应用组件
│   │   └── main.tsx         # 渲染进程入口
│   ├── main/                # 主进程源码
│   └── preload/             # 预加载源码
├── build/                   # 构建资源
│   └── icons/               # 应用图标
├── icons/                   # 源图标
├── release/                 # 打包输出
├── electron.vite.config.ts  # Electron Vite 配置
├── package.json
├── tsconfig.json
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

---

## 🔧 开发指南

### 开发模式

```bash
pnpm dev
```

启动开发服务器，应用会自动打开并连接到 Vite 开发服务器（默认 http://localhost:5173）。

### 构建生产版本

```bash
pnpm build
```

构建应用，输出到 `out/` 目录。

### 打包应用

```bash
pnpm dist
```

使用 electron-builder 打包应用，输出到 `release/{version}/` 目录。

### 自动发布到 GitHub Releases

```bash
# 创建 tag
git tag v0.0.6

# 推送 tag 到 GitHub
git push origin v0.0.6
```

推送 tag 后，GitHub Actions 会自动：
- 构建应用
- 创建 GitHub Release
- 上传安装包到 Releases

### 预览构建

```bash
pnpm preview
```

预览构建后的应用。

### 打包到目录（不构建安装包）

```bash
pnpm pack
```

将应用打包到目录，不创建安装包。

---

## 📝 开发规范

### 代码风格

- 使用 TypeScript 进行类型检查
- 严格模式已启用（`strict: true`）
- 使用 ESLint 规则检查未使用的变量和参数

### 组件开发

- 使用函数式组件和 Hooks
- 组件使用 PascalCase 命名
- 文件名使用 PascalCase 命名（如 `TodoList.tsx`）

### 状态管理

- 使用 Zustand 进行全局状态管理
- 使用 `persist` 中间件持久化状态

### IPC 通信

- 主进程和渲染进程通过 IPC 通信
- 渲染进程通过 `window.electronAPI` 访问 IPC 接口

---

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

---

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

---

## 🙏 致谢

感谢以下开源项目：

- [Electron](https://www.electronjs.org/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Radix UI](https://www.radix-ui.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Three.js](https://threejs.org/)
- [Zustand](https://github.com/pmndrs/zustand)

---

## 📮 联系方式

- 作者：zxb
- GitHub：[https://github.com/zxbdzh](https://github.com/zxbdzh)

---

<div align="center">

**如果这个项目对你有帮助，请给个 ⭐ Star 支持一下！**

Made with ❤️ by zxb

</div>

## 星标历史
[![Star History Chart](https://api.star-history.com/svg?repos=zxbdzh/MoLeMa&type=date&legend=top-left)](https://www.star-history.com/#zxbdzh/MoLeMa&type=date&legend=top-left)
