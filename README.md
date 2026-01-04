# play_discord

Discord 新聞收集器機器人 — 自動收集 RSS 新聞並推送到指定頻道

## 功能特色

- Discord Bot 整合
- RSS Feed 新聞收集
- 關鍵字過濾
- 定時排程推送
- 零費用部署（Zeabur 免費方案）

## 快速開始

1. 閱讀 `user/docs/CLAUDE.md` 了解專案規範
2. 複製 `.env.example` 為 `.env` 並填入設定
3. 安裝依賴：`npm install`
4. 開發模式：`npm run dev`
5. 建置專案：`npm run build`

## 專案結構

- `src/main/typescript/` — TypeScript 原始碼
  - `core/` — Discord Bot 核心
  - `services/` — RSS 收集服務
  - `commands/` — Bot 指令
  - `utils/` — 工具函式
- `src/main/resources/` — 設定與資源檔案
- `src/test/` — 測試
- `docs/` — 文件
- `output/` — 輸出檔案
- `user/` — 私人區域（不進版控）

## 文件

詳見 `user/docs/CLAUDE.md` 的文件索引。

## 部署

使用 Zeabur 部署，詳見 `docs/specs/tech-choices.md`。

## 授權

MIT
