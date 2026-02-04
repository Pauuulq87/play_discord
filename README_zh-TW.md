<div align="center">

# Play Discord

<img src="https://api.iconify.design/mdi/robot.svg" width="64" height="64" alt="Discord Bot"/>

Discord 新聞收集器機器人 — 自動收集 RSS 新聞並推送到指定頻道。

[English](./README.md) | **繁體中文** | [简体中文](./README_zh-CN.md)

</div>

---

## 功能特色

- Discord Bot 整合
- RSS Feed 新聞收集
- 關鍵字過濾
- 定時排程推送
- 零費用部署（Zeabur 免費方案）

## 快速開始

```bash
# 安裝依賴
npm install

# 配置
cp .env.example .env
# 編輯 .env 填入設定

# 開發模式
npm run dev

# 建置
npm run build
```

## 專案結構

```
src/main/typescript/
├── core/       # Discord Bot 核心
├── services/   # RSS 收集服務
├── commands/   # Bot 指令
└── utils/      # 工具函式
```

## 部署

使用 Zeabur 部署，詳見 `docs/specs/tech-choices.md`。

---

## 授權

MIT

## 致謝

Made with ❤️ by **Pauuulq87**
