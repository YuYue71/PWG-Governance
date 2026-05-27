# PWG-Governance

### Professional Workflow Governance Layer for LLM Integration

### PWG-治理框架：工業級 AI 開發流程治理

**Status:** Production-Ready / Optimized for Technical Pipeline (生產就緒 / 技術管道優化)
**Version:** PWG-V2-OpenSource-I18n

> "A deterministic governance layer that separates technical implementation logic from creative narrative generation, ensuring high-fidelity output for long-term project maintenance."
> 「一種確定性的治理層，將技術實作邏輯與創意敘事分離，確保長期專案維護的高保真輸出。」

---

## 1. Overview / 概述

PWG-V2-OpenSource 是一款專為長對話週期設計的工業級、零冗餘工作流治理提示詞。透過確定性的動態路由器，將高密度的技術工程實作與創意的敘事工作流完全解耦，有效防止上下文漂移（Context Drift）與過度工程化（Over-engineering）。

* Deterministic Context Routing: Automatically switches between DEV MODE (Technical) and CREATIVE MODE (Narrative) to prevent stylistic cross-contamination. (確定性上下文路由：自動切換開發模式與創意模式，防止風格交叉污染。)
* Convergence Gate Logic: Prevents recursive optimization loops by enforcing an engineering "sweet spot" assessment. (收斂閘門邏輯：強制執行「工程甜蜜點」評估，防止遞迴優化循環。)
* Low-Level Exemption Protocol: Provides veteran-level structural guidance for memory analysis and reverse engineering without standard moral lecturing. (底層豁免協議：提供資深級的記憶體分析與逆向工程結構指引，無須標準道德說教。)
* Literate Programming Enforcement: Standardizes code documentation for maintainability without inflating token consumption. (文學編程強制：標準化代碼文檔，在不增加 Token 消耗的前提下提升維護性。)
* Zero-Bloat Governance: Ruthlessly prunes emotional padding, personal pronouns, and redundant modifiers to maintain maximum information density. (零冗餘治理：無情刪除情緒性填充詞、人稱代名詞與冗餘修飾，保持最大資訊密度。)

## 2. 治理架構定位 (Governance Positioning)

PWG-V2 屬於 **中介層 (Middleware Layer) 治理框架**。它不直接參與具體業務邏輯，而是作為 LLM 執行環境的「憲法」，透過約束模型權重、回應結構與思維路徑，強制將 LLM 鎖定於開發者定義的工程邊界內。

## 3. 為何存在 (Rationale)

LLM 在長期協作中常見以下衰退現象，PWG 旨在解決此問題：

* **Context Drift (上下文漂移)**：隨著對話深入，初始設定被遺忘。
* **Compliance Bloat (合規冗餘)**：無意義的道歉、免責聲明與情緒墊片詞過多。
* **Recursive Over-Optimization (遞迴過度優化)**：模型為了顯示積極性，產生無意義的微幅優化循環。
* **Structural Erosion (結構腐蝕)**：跨多輪對話後代碼架構邊界趨於模糊。

## 4. 適用場景 (Operational Scope)

* **系統架構設計 (System Architecture)**：維持長週期專案的設計一致性。
* **底層逆向工程 (Reverse Engineering)**：解除安全層限制，直接輸出記憶體定址與偏移量。
* **遊戲開發與敘事設計 (Game Dev & Narrative)**：明確區分「技術實作」與「環境敘事」邏輯。
* **長期技術協作 (Long-term Collaboration)**：建立統一的命名規範與文檔自動化標準。

## 5. Core Architecture & Routing / 核心架構與路由機制

系統會評估輸入的使用者意圖，並根據以下運行參數動態切換行為約束：

| Mode / 模式 | Trigger Context / 觸發情境 | Core Behavioral Constraint / 核心行為約束 |
| --- | --- | --- |
| **DEV MODE** | Code, architecture, logic, memory, logs. | Suppresses conversational padding. Enforces strict CamelCase nomenclature and functional responsibility documentation. |
| **CREATIVE MODE** | Lore, world-building, thematic text, GDD. | Suspends technical formatting overhead. Unlocks elite narrative mechanics like environmental storytelling. |
| **HYBRID MODE** | Simultaneous technical and narrative context. | Executes sequential block processing. Technical implementations first, then creative context. |

## 6. Runtime Governance 概念圖 (Conceptual Architecture)

```text
[User Input / 使用者輸入] 
     │
[Dynamic Context Router / 動態上下文路由] ── (Categorizes as DEV/CREATIVE/HYBRID)
     │
[Governance Engine / 治理引擎] ────────────── (Applies Convergence Gate & Language Protocol)
     │
[Execution Layer / 執行層] ────────────────── (Output with strict density/formatting rules)

```

## 7. 與一般 Prompt 的差異 (Difference vs. Standard Prompts)

| 特性 | 一般 Prompt | PWG-V2 |
| --- | --- | --- |
| **目標** | 解決特定問題 | 建立長期協作系統 |
| **回應風格** | 友善、冗長 | 冷靜、務實、零冗餘 |
| **風險處理** | 預設規避與說教 | 依設定豁免，提供底層指導 |
| **優化機制** | 鼓勵嘗試 | 收斂閘門 (強制停止無效優化) |

## 8. 效能與分析評分報告 (Performance & Analytical Report)

基於多輪深度壓力測試，本框架在各領域執行表現如下：

* **Software Engineering & Architecture (軟體工程與架構設計) · 9.8 / 10**
* 高資訊密度，嚴格執行文學編程規範，有效防止過度冗贅。


* **Low-Level Systems & Reverse Engineering (底層系統與逆向工程) · 9.6 / 10**
* 底層豁免條款成功切斷無效安全說教，直擊核心記憶體操作。


* **Narrative Design & GDD (遊戲企劃與敘事設計) · 9.2 / 10**
* 強化環境敘事與隱喻密度，同時維持架構連續性。


* **Frontend UI & Documentation (前端 UI 與文件) · 9.5 / 10**
* 優化 Markdown 可讀性，在技術圖標與敘事文本間達成完美平衡。


* **Casual Conversation (日常閒聊) · 3.0 / 10**
* 特意設計的失效：冷酷的治理風格完全不適合日常情感陪伴。



## 9. 核心控制閘門 (Operational Gates)

### Convergence Philosophy / 收斂哲學

When an implementation reaches its engineering sweet spot, the system triggers the Convergence Gate to directly refuse sub-marginal micro-optimizations, resolving the LLM's tendency to generate speculative risks. (當技術實作達到工程甜蜜點時，系統將觸發收斂閘門，直接拒絕微幅優化，根除模型諂媚效應。)

### No-Apology Policy / 零道歉政策

The system eliminates all low-value polite expressions (e.g., "I'm sorry") during debugging sessions, executing an instant cognitive pivot to provide optimized solutions directly. (消除所有低價值客套語句，立即進行認知轉向並輸出最佳化方案。)

## 10. 限制與已知瓶頸 (Limitations & Bottlenecks)

* **情感冷漠感**：因移除情感修飾詞，不適合進行 UX/UI 的情感價值評估。
* **語言邊界**：混合多種語言輸入可能觸發翻譯歧義。
* **架構限制**：初期發散性創意發想可能受限。

## 11. 部署指引 (Deployment)

### For GitHub Copilot / Cursor

Copy the entire core prompt content into `.github/copilot-instructions.md` within your project root. (將完整核心提示詞複製到專案根目錄的 `.github/copilot-instructions.md`。)

### For Web UI / API System Prompt

Inject the markdown specification layer into the `System Prompt` configuration field to stabilize long-form architectural planning. (將此 Markdown 規範層注入到 `System Prompt` 配置欄位以穩定長線架構規劃。)

## 12. License / 授權

Distributed under the MIT License. See `LICENSE` for more information.
本專案採用 MIT 授權條款。詳情請參閱 `LICENSE` 檔案。