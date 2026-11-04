# Writing for Agents（第三方 Skill 副本）

這個資料夾保存 Matt Pocock 原版 **writing-for-agents** 的可重複取用副本，方便從本人的 GitHub 存取，而不必每次重述上游網址。

- 上游 Repository：[mattpocock/skills](https://github.com/mattpocock/skills)
- 原始 Skill：[skills/productivity/writing-for-agents/SKILL.md](https://github.com/mattpocock/skills/blob/main/skills/productivity/writing-for-agents/SKILL.md)
- 原始 Skill mechanics：[SKILL-MECHANICS.md](https://github.com/mattpocock/skills/blob/main/skills/productivity/writing-for-agents/SKILL-MECHANICS.md)
- 來源檢查日期：2026-11-04
- 上游 Git blob SHA：`SKILL.md` = `a37608daf6e835e767deecfb498facecaaba82ba`；`SKILL-MECHANICS.md` = `9cdbdb22aadc438755392216e75ad9a14cc9832e`
- 授權：[MIT License](LICENSE)，Copyright (c) 2026 Matt Pocock；請保留此 LICENSE 和來源資訊。
- `SKILL.md` 與 `SKILL-MECHANICS.md` 為**原文副本**，沒有套用 Talk Loop 或 Thinking Cards 自有規則。

## 怎麼用

以後可以說：

> 「用 Writing for Agents 幫我檢查這份 Prompt。」

如果 ChatGPT Project / Agent 有設定 GitHub 路由，應讀取：

1. `guoyutw/thinking-cards/skills/writing-for-agents/SKILL.md`。
2. 只有在撰寫或審查 **Skill** 時，依原文件指示再讀 `SKILL-MECHANICS.md`。

針對現有 Prompt / AGENTS.md / Agent 指令：先找出 context pointer、完成條件、資訊層級、重複和 no-op 的問題；提出具體修正與取捨。**除非另外授權，不自動修改目標檔案。**

### ChatGPT Project 的簡短路由規則（需另外手動加入）

```text
When I say "Writing for Agents" or "用 Writing for Agents 檢查",
read guoyutw/thinking-cards/skills/writing-for-agents/SKILL.md
from the current main branch using GitHub. When editing a Skill,
also read its SKILL-MECHANICS.md. Apply the original reference
to the supplied agent-facing document. If retrieval fails, say
NOT_LOADED; do not claim the skill was loaded. Do not edit files
without task-specific authorization.
```

**限制：** GitHub 中存在檔案不代表 ChatGPT 已自動安裝 Skill、開啟自動觸發，或已設定上面的 Project 指令。PR 合併後才會存在於 `main`；若要試用未合併的 PR，請明確指定 PR branch。

## 更新與維護

這是有來源版本的副本，不會自動跟上游同步。要升級時，先比較上游最新版及授權，再以獨立 PR 更新；避免在原版檔案中混入自製規則。與 Thinking Cards 的 `thinking-cards-prompts.json` 保持分離。
