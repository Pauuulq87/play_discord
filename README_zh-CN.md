<div align="center">

# Play Discord

<img src="https://api.iconify.design/mdi/robot.svg" width="64" height="64" alt="Discord Bot"/>

Discord 新闻收集器机器人 — 自动收集 RSS 新闻并推送到指定频道。

[English](./README.md) | [繁體中文](./README_zh-TW.md) | **简体中文**

</div>

---

## 功能特色

- Discord Bot 集成
- RSS Feed 新闻收集
- 关键字过滤
- 定时调度推送
- 零费用部署（Zeabur 免费方案）

## 快速开始

```bash
# 安装依赖
npm install

# 配置
cp .env.example .env
# 编辑 .env 填入设置

# 开发模式
npm run dev

# 构建
npm run build
```

## 项目结构

```
src/main/typescript/
├── core/       # Discord Bot 核心
├── services/   # RSS 收集服务
├── commands/   # Bot 指令
└── utils/      # 工具函数
```

## 部署

使用 Zeabur 部署，详见 `docs/specs/tech-choices.md`。

---

## 许可证

MIT

## 致谢

Made with ❤️ by **Pauuulq87**
