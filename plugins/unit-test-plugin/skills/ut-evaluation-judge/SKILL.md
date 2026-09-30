---
name: ut-evaluation-judge
model: sonnet
disable-model-invocation: true
metadata:
  version: 1.2.1
  last-modified: 2026-09-23
description: "[DEPRECATED] Unit Test 的品質與覆蓋率評估。從「測了什麼、漏了什麼」（覆蓋率）和「測得好不好」（品質）兩個面向產出完整評估報告。已不再由 ut-test-orchestrator 呼叫（plugin v1.5.0 除役，將於下次 MAJOR 移出），僅供手動觸發做全專案品質評估。不修改任何檔案，只產出評估結果。觸發詞：評估測試、檢查覆蓋率、coverage、品質檢查、quality、blind spot、哪些沒測到、測試寫得好嗎。"
---

> 架構參考用骨架：僅保留 frontmatter，SKILL 內文未複製（正本在 unit-test-plugin）。
