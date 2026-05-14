# Repository Memory

## Stable Context
- 龍蝦群目前能確認的穩定脈絡很少：這個 repo 的 memory 流程依賴 GitHub issue / comment 作為原始事實來源，記憶文件應該以「提煉後的長期脈絡」為主，而不是逐段複製原始討論。
- `.memory/shared/manual.md` 是給人類手動維護的長期記憶區，適合放：
  - 穩定規則
  - 長期決策
  - 常見限制
  - agent 共同遵守的 repo 習慣
- compact-memory workflow 會讀取手動筆記，但不會覆寫它；因此手動筆記可視為較穩定的人類補充來源。
- 目前提供的 daily snapshots 中，沒有可用 issue 內容，因此尚無法可靠判定此 repo 的產品目標、技術棧、工作流程細節或主人近期實際在做的事情。

## Recent Themes
- 最近一段時間（至少 2026-05-08 到 2026-05-14）的共同主題非常單一：**沒有新的 issue 活動可供整理**。
- 每日快照反覆顯示：
  - 沒有可辨識的跨 issue 主題
  - 沒有新的跨 issue 決策
  - 沒有 labels 可供觀察
- 因此目前的近期狀態比較像是「記憶維持模式」：龍蝦群只能先保留既有記憶，等待新的工作訊號出現。
- 不確定性說明：這不一定代表 repo 完全沒有變動，只能確定在這批 memory 輸入中，**沒有被 issue-based workflow 捕捉到的新資訊**。

## Constraints
- 記憶整理必須以 GitHub issue / comment 為主要原始來源；其他記錄不應取代原始事實來源。
- MEMORY 類文件應該是 curated long-term memory，不是：
  - 原始日誌
  - issue 索引
  - 完整討論逐字轉錄
- 若某件事只短暫出現在最新一天、且尚未形成穩定模式，應放在近期主題或 open loop，而不應寫成長期規則。
- 目前最大的限制是**資訊不足**：連續多日沒有 issue 資料，導致無法建立更具體的長期上下文。
- 若後續資料與目前空白狀態衝突，應以新的 issue / comment 證據重新校正記憶。

## Open Loops
- 等待下一輪有實際內容的 issue 更新，讓龍蝦群能補齊：
  - repo 的核心目的
  - 主人近期工作主軸
  - 穩定工程慣例
  - 已知限制與待辦
- 需要未來資料來確認目前的「無活動」究竟是：
  - 暫時沒有 issue 被建立或更新，還是
  - 工作主要發生在 issue 之外，導致 memory workflow 看不到
- 目前沒有足夠證據可列出具體未完成事項；唯一明確的 open loop 是：**等待新的可整理來源出現**。
