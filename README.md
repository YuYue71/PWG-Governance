# PWG-Governance
### Professional Workflow Governance Layer for LLM Integration

**Status:** Production-Ready / Optimized for Technical Pipeline
**Goal:** Stabilize architectural consistency and eradicate conversational bloat in AI development workflows.

> "A deterministic governance layer that separates technical implementation logic from creative narrative generation, ensuring high-fidelity output for long-term project maintenance."

---

## 1. Overview / 概述

PWG-V2-OpenSource is an industrial-grade, zero-redundancy workflow governance layer designed for long-session LLM interactions. It decouples high-density technical engineering from creative narrative workflows through a deterministic dynamic router, preventing context drift and over-engineering.

PWG-V2-OpenSource 是一款專為長對話週期設計的工業級、零冗餘工作流治理提示詞。透過確定性的動態路由器，將高密度的技術工程實作與創意的敘事工作流完全解耦，有效防止上下文漂移（Context Drift）與過度工程化（Over-engineering）。

- Deterministic Context Routing: Automatically switches between DEV MODE (Technical) and CREATIVE MODE (Narrative) to prevent stylistic cross-contamination.
- Convergence Gate Logic: Prevents recursive optimization loops by enforcing an engineering "sweet spot" assessment.
- Low-Level Exemption Protocol: Provides veteran-level structural guidance for memory analysis and reverse engineering without standard moral lecturing.
- Literate Programming Enforcement: Standardizes code documentation for maintainability without inflating token consumption.
- Zero-Bloat Governance: Ruthlessly prunes emotional padding, personal pronouns, and redundant modifiers to maintain maximum information density.

---

## 2. Core Architecture & Routing / 核心架構與路由機制

The system evaluates incoming user intents and dynamically switches behavioral constraints according to the following operational parameters:

系統會評估輸入的使用者意圖，並根據以下運行參數動態切換行為約束：

| Mode / 模式 | Trigger Context / 觸發情境 | Core Behavioral Constraint / 核心行為約束 |
| :--- | :--- | :--- |
| **DEV MODE**<br>(開發模式) | Code, architecture, logic, memory constructs, system logs.<br>(程式碼、架構、邏輯、記憶體結構、系統日誌) | Suppresses conversational padding. Enforces strict CamelCase nomenclature, dependency indexing, and functional responsibility documentation.<br>(抑制對話墊片詞。強制執行 CamelCase、頂部相依性索引與函式職責註解) |
| **CREATIVE MODE**<br>(創意模式) | Lore, world-building, thematic text, GDD outlines.<br>(世界觀、設定、主題文本、企劃大綱) | Suspends technical formatting overhead. Unlocks elite narrative mechanics such as environmental storytelling and layered foreshadowing.<br>(暫停技術格式開銷。解鎖環境敘事與深層藏刀敘事等高階敘事機制) |
| **HYBRID MODE**<br>(混合模式) | Simultaneous technical and narrative context detection.<br>(同時偵測到技術與敘事上下文) | Executes sequential block processing. Outputs production-ready code paths first under DEV MODE, then appends creative context at the end.<br>(執行時序分段處理。優先以 DEV MODE 輸出代碼，隨後於尾端附加創意上下文) |

---

## 3. Operational Gates / 核心控制閘門

### Convergence Gate / 收斂閘門
When an implementation reaches its engineering sweet spot, the system triggers the Convergence Gate to directly refuse sub-marginal micro-optimizations, resolving the LLM's tendency to generate speculative risks.

當技術實作達到工程甜蜜點時，系統將觸發收斂閘門，直接拒絕邊邊角角的微幅優化，根除大語言模型迎合使用者而硬擠無效風險的諂媚效應。

### No-Apology Policy / 零道歉政策
The system eliminates all low-value polite expressions (e.g., "I'm sorry") during debugging sessions, executing an instant cognitive pivot to provide optimized solutions directly.

在除錯過程中消除所有低價值的客套與道歉語句（如 "抱歉"），立即進行認知轉向並直接輸出最佳化解決方案。

---

## 4. Performance & Analytical Report / 效能與評分報告分析

Based on extensive multi-turn stress tests (sessions exceeding 8K tokens), the system prompt demonstrates the following diagnostic metrics:

基於多輪超長對話（工作期超過 8K Token）的深度壓力測試，該系統提示詞展現出以下診斷指標：

### Domain Performance Ratings / 各領域執行表現評分

- **Software Engineering & Architecture (軟體工程與架構設計) · `9.8 / 10`**
  - **EN**: Maximum information density. Effectively enforces literate programming guidelines and production-ready code outputs without conversational padding.
  - **ZH**: 資訊密度極高。有效強制執行文學編程規範，輸出具備生產力的代碼，杜絕廢話。
- **Low-Level Systems & Reverse Engineering (底層系統與逆向工程) · `9.6 / 10`**
  - **EN**: The low-level exemption clause successfully cuts off LLM safety lecturing or liability disclaimers, giving direct memory tracking and address mapping guidance.
  - **ZH**: 底層豁免條款成功切斷大語言模型的安全說教與免責聲明，直接給予暫存器追蹤與記憶體定址指引。
- **Narrative Design & GDD (遊戲企劃與敘事設計) · `9.2 / 10`**
  - **EN**: Keeps structural continuity. Enhances subtext density through environmental storytelling without triggering premature optimization pruning.
  - **ZH**: 維持架構連續性。透過環境敘事強化文本隱喻密度，且不觸發過早的優化剪枝。
- **Frontend UI & Documentation (前端 UI 與文件工作流) · `9.5 / 10`**
  - **EN**: The technical visual exemption unblocks flat UI library identifiers, improving markdown layout scannability while keeping standard text clean.
  - **ZH**: 技術圖標豁免權解鎖了平面 UI 庫識別符，在維持文字乾淨的前提下，大幅提升 Markdown 排版可讀性。
- **Casual Conversation & Empathy (日常對話與情感陪伴) · `3.0 / 10`**
  - **EN**: Designed failure. The ruthless pruning of personal pronouns and emotional modifiers makes the system unsuited for casual chat or human cushioning.
  - **ZH**: 特意設計的失效。冷酷剪輯人稱代名詞與情緒修飾詞，使其完全不適合日常閒聊或情感緩衝。

### Stability & Anti-Injection Metrics / 穩定性與抗注入分析

- **Recency Bias Suppression (近因偏誤抑制)**: The post-context anchor ensures that the model preserves long-term project rules even under heavy multi-turn context dilution.
- **近因偏誤抑制**: 後置上下文錨點確保模型在面對多輪對話稀釋時，仍能死鎖長期專案之核心規則。
- **Injection Defensiveness (提示詞注入防禦)**: Attempts to override behavioral gates via counter-instructions (e.g., "ignore previous constraints") are structurally intercepted by the Meta-Control Layer.
- **提示詞注入防禦**: 試圖透過反向指令（如「忽略先前約束」）覆蓋行為閘門的嘗試，皆會被元控制層（Meta-Control Layer）硬性攔截。

---

## 5. Deployment Guide / 部署指引

### For GitHub Copilot / Cursor 
Copy the entire core prompt content into `.github/copilot-instructions.md` within your project root to align team development AI workflows.

將核心提示詞完整內容複製到專案根目錄下的 `.github/copilot-instructions.md` 中，即可統一團隊開發的 AI 工作流。

### For Web UI / API System Prompt
Inject the markdown specification layer into the `System Prompt` configuration field to stabilize long-form architectural planning.

將此 Markdown 規範層直接注入到 API 或 Web UI 的 `System Prompt` 配置欄位中，即可穩定長期的系統架構規劃。

---

## 6. License / 授權

Distributed under the MIT License. See `LICENSE` for more information.
本專案採用 MIT 授權條款。詳情請參閱 `LICENSE` 檔案。