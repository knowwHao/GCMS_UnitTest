---
name: ut-test-writer
model: opus
metadata:
  version: 1.4.6
  last-modified: 2026-09-23
description: 根據測試情境規格（scenarios JSON）和 Code Snapshot 產生單元測試程式碼。Framework × test-runner 兩軸 framework-aware：偵測 DI 框架（NestJS / Koa+Inversify / gama-api-server / 等）× test runner（jest / mocha+chai）動態載對應 adapter，使用專案實際存在的 mock 工具（jest.fn / ts-mockito / inline / 手動 stub）產出可直接執行的 co-located .spec.ts 測試檔。僅用於已有 `.ut-cache/scenarios/` 的後端 TS 專案，其他情況不要選用。觸發詞：寫測試、產生測試碼、generate test、write test、寫 UT。
---

> 架構參考用骨架：僅保留 frontmatter，SKILL 內文未複製（正本在 unit-test-plugin）。
