---
name: ut-test-analyzer
model: sonnet
metadata:
  version: 1.1.5
  last-modified: 2026-09-23
description: 分析 ut-test-runner 產出的 `results-slim.json`（jest／mocha 兩軌通用），將失敗分為三類（A 可自動修復 / B 產品 Bug / C 環境問題），產出結構化分析報告供 ut-test-orchestrator 決策。沒有 `results-slim.json` 的一般測試失敗排查不選用。觸發詞：分析測試結果、analyze results、為什麼測試失敗、test failure。
---

> 架構參考用骨架：僅保留 frontmatter，SKILL 內文未複製（正本在 unit-test-plugin）。
