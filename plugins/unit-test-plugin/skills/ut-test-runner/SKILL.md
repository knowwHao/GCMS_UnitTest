---
name: ut-test-runner
model: sonnet
metadata:
  version: 1.5.4
  last-modified: 2026-09-23
description: 執行單元測試（jest 與 mocha 兩軌，依專案自動偵測）並將結果輸出為結構化 JSON 檔案。支援全專案執行或指定單一模組。記錄執行時間供後續分析。用於 unit-test-plugin 單元測試流程（產出供 ut-test-analyzer 讀的 `.ut-cache/reports/results-slim.json`）；其他專案的一般跑測試需求不選用。觸發詞：跑測試、執行 UT、run test、run unit test。
---

> 架構參考用骨架：僅保留 frontmatter，SKILL 內文未複製（正本在 unit-test-plugin）。
