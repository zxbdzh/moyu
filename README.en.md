# MoLeMa (摸了吗)

**🎯 A stealthy slacking sidekick built for developers.** One global hotkey summons or hides the whole window — packed with an RSS reader, notes, todo list and news feed.

[中文](README.md)

## Features

- 📰 **RSS subscriptions** — follow multiple tech blogs, built-in reader with Markdown rendering, favorites, recommended sources (Ruan Yifeng, Juejin, Hacker News…)
- 📝 **Notes** — full Markdown support with live preview
- ✅ **Todo list** — drag-to-reorder, completion stats (today/week/month/year/total), pagination for completed tasks
- 🌐 **News feed** — aggregated domestic sources, category browsing (tech, news, startups)
- ⌨️ **Global hotkey** — default `Ctrl+Alt+M` to show/hide, fully customizable
- 🎨 **Polished UI** — Framer Motion + GSAP + Anime.js animations, 3D cards, particle backgrounds, light/dark themes

## Install

Download the latest installer from [Releases](https://github.com/zxbdzh/MoLeMa/releases), or build from source:

```bash
git clone https://github.com/zxbdzh/MoLeMa.git
cd MoLeMa
pnpm install
pnpm dev        # development
pnpm dist       # package
```

## Tech stack

Electron + electron-vite + React 18 + TypeScript + Tailwind CSS, with Zustand, better-sqlite3 (local DB), rss-parser, react-markdown, Three.js/R3F and more.

## License

[MIT](./LICENSE)
