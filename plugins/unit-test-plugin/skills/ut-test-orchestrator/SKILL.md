---
name: ut-test-orchestrator
model: sonnet
metadata:
  version: 1.5.6
  last-modified: 2026-09-23
description: Unit Test 流水線總協調器。串接所有 Skills（scanner → designer → writer → runner → analyzer），支援 full/incremental/fix/single 四種模式，incremental 另有 --fast 建議模式（掃描＋regression＋差異報告，不重生，重生與否由開發者決定）與 --regen 指定重生；負責自動修復迴圈、字面等價自動跳過、多模組並行派工、機械計數（--canonical 權威 run）、Drift Detection 和結果彙報。只接受手動呼叫，不由模型自動觸發：互動 session 輸入 `/unit-test-plugin:ut-test-orchestrator <參數>`，CI 以 `claude -p "/unit-test-plugin:ut-test-orchestrator <參數>"` 執行。
disable-model-invocation: true
argument-hint: "[full|incremental|fix|single <module>] [--fast|--regen <mods|all>] [--canonical --headless --auto-init --clean]"
---

> 架構參考用骨架：僅保留 frontmatter，SKILL 內文未複製（正本在 unit-test-plugin）。
