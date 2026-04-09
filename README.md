# OpenClaw Changelog

同步 [OpenClaw](https://github.com/openclaw/openclaw) 的 GitHub Releases，按月归档展示中文 changelog。

## 在线访问

https://alloevil.github.io/openclaw-changelog/

## 如何更新

在本项目 GitHub Actions 页面手动触发 **Sync Changelog** workflow，或在 Claude Code 中执行 `/sync-openlaw` skill。

## 项目结构

```
├── index.html                  # Changelog 页面（静态 HTML）
├── skills/sync-openlaw/        # Claude Code 同步 skill
├── scripts/sync.mjs            # 自动同步脚本
└── .github/workflows/
    ├── sync.yml                # 手动触发同步
    └── deploy.yml              # 自动部署 GitHub Pages
```
