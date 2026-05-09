# Agent Changelog

追踪主流 AI Agent 框架的版本更新与演进。

## 包含项目

| 项目 | 来源 | 版本数 | 时间跨度 |
|------|------|--------|----------|
| **OpenClaw** | [openclaw/openclaw](https://github.com/openclaw/openclaw) | 32+ | 2026.1 — 至今 |
| **Hermes Agent** | [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 12 | 2026.3 — 至今 |

## 文件结构

```
├── index.html        # 首页（项目选择）
├── openclaw.html     # OpenClaw Changelog
├── hermes.html       # Hermes Agent Changelog
├── assets/           # 静态资源
├── scripts/          # 构建脚本
└── skills/           # 技能相关
```

## 更新方式

从 GitHub Releases API 实时拉取数据，解析 release notes 中的 Highlights 章节并生成 HTML。

## 访问

本地打开 `index.html` 即可浏览。
