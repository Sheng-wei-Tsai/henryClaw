# HenryClaw

HenryClaw 擔任專案前線任務中樞，接收 Telegram 需求後立即轉為可追蹤工作項目，確保每個需求都能被接力與執行。

## 說明

本專案以 GitHubClaw 為框架，透過 Telegram Bot 接收使用者需求，自動建立 GitHub Issue 並觸發 Copilot 編碼代理人（Coding Agent）進行處理。

### 核心流程

1. 使用者透過 Telegram 傳送需求
2. Cloudflare Worker 接收訊息並轉換為 GitHub Issue
3. GitHub Actions 觸發 Coding Agent（Copilot CLI）
4. Agent 在 `workspaces/issue-{n}/` 工作區執行任務
5. 執行結果回寫至 Issue Comment

## 目錄結構

- `.github/workflows/` — CI/CD 工作流程定義
- `.memory/` — Agent 長期記憶檔案
- `workspaces/` — 各 Issue 的專屬工作區
  - `template/` — 新工作區的範本
  - `issue-1/` — HenryClaw 專案起源 Issue
