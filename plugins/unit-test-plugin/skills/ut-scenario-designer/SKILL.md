---
name: ut-scenario-designer
model: opus
metadata:
  version: 1.3.6
  last-modified: 2026-09-23
description: 深度分析 Service 層的業務邏輯，設計完整的 Unit Test 情境規格（JSON），涵蓋所有執行路徑：success flow、input validation、authorization、empty result、exception handling、side effect verification、dependency interaction、state machine coverage（含每條獨立 transition path）、composite key coverage、batch module scope selection。產生 Code Snapshot + Scenarios JSON，不產生測試程式碼。需 `.ut-cache/reports/project-map.json`（ut-project-scanner 產出）：僅用於已有 project-map 的後端 TS 專案，其他情況不要選用。觸發詞：設計測試情境、design scenario、設計 UT 情境、分析測試路徑。
---

> 架構參考用骨架：僅保留 frontmatter，SKILL 內文未複製（正本在 unit-test-plugin）。
