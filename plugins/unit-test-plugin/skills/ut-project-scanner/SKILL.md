---
name: ut-project-scanner
model: sonnet
metadata:
  version: 1.4.1
  last-modified: 2026-09-23
description: 掃描 TypeScript 後端專案（koa-inversify／koa-plain／gama-api-server／NestJS）的 Controller、Service、Repository 三層結構，產生 project-map.json，記錄所有端點、公開方法、資料庫依賴、Exception 路徑和優先級。支援 NestJS 檔名別名（`*.service.ts`／`*.controller.ts`／`*.repository.ts`）。支援增量掃描（git diff）。觸發詞：掃描專案、scan project、更新 project map、分析專案結構。
---

> 架構參考用骨架：僅保留 frontmatter，SKILL 內文未複製（正本在 unit-test-plugin）。
