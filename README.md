# PWG-Governance

![Version](https://img.shields.io/badge/version-V3-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Tech](https://img.shields.io/badge/stack-System_Prompt-lightgrey)

[中文](#中文) | [English](#english)

---

## 中文

### 目錄
- [關於](#關於)
- [功能](#功能)
- [安裝](#安裝)
- [使用方式](#使用方式)
- [授權](#授權)

### 關於
PWG-Governance (PWG-V3-LLM-Optimized) 是一款專為長對話週期設計的工業級, 零冗餘工作流治理提示詞. 透過確定性的動態路由器, 將高密度的技術工程實作與創意的敘事工作流完全解耦, 有效防止上下文漂移(Context Drift)與過度工程化(Over-engineering). 本框架屬於中介層(Middleware Layer)治理框架, 作為 LLM 執行環境的"憲法", 透過約束模型權重, 回應結構與思維路徑, 強制將 LLM 鎖定於開發者定義的工程邊界內. 本次 V3 版本進一步強化了自我稽核與多語言處理協定, 確保大型語言模型在複雜協作中的極致穩定性.

### 功能
- 確定性上下文路由: 自動切換開發模式(DEV MODE), 創意模式(CREATIVE MODE)與混合模式(HYBRID MODE), 嚴格隔離技術與敘事邏輯, 防止風格交叉污染.
- 自我稽核迴圈(Self-Audit Loop): 主動偵測知識缺口, 邏輯不完整或輸出格式偏移, 並自動生成約束條件與補償提示, 以阻斷錯誤傳播.
- 收斂閘門與零容忍審訊: 強制執行工程甜蜜點評估, 拒絕微幅優化; 面對模糊邊界立即中斷生成並要求補充關鍵脈絡, 杜絕幻覺與盲目開發.
- 動態本地化協定(Dynamic i18n Protocol): 強制內部邏輯推演全英文執行以極大化 LLM 解析效率, 僅在代碼註解與文件輸出時精準切換至目標語言.
- 文學編程與架構審查: 強制標準化依賴索引, 函式職責與內聯狀態註解; 於輸出前執行內部代碼審查, 包含記憶體洩漏, 競爭條件與相容性檢查.
- 零冗餘與零道歉政策: 無情刪除情緒性填充詞與低價值客套語句; 遇到錯誤日誌直接進行認知轉向(Cognitive Pivot)並輸出最佳化代碼.

### 安裝
```bash
# 針對 GitHub Copilot / Cursor
# 1. 建立設定檔
touch .github/copilot-instructions.md

# 2. 將 PWG-V3 核心提示詞全文複製並貼入該檔案中
# 3. 重新載入編輯器或重啟 AI 助理視窗使設定生效
```

### 使用方式
```bash
# 針對 Web UI (如 ChatGPT, Claude) / API 系統提示詞 (System Prompt)
# 1. 導航至系統設定或 System Prompt 配置欄位
# 2. 將 PWG-V3 markdown 規範層完整注入
# 3. 若使用 API, 請確保 system_role 被正確設定為最高權限
```

### 授權
本專案採用 MIT 授權, 詳見 [LICENSE](./LICENSE).

---

## English

### Table of Contents
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

### About
PWG-Governance (PWG-V3-LLM-Optimized) is an industrial-grade, zero-bloat workflow governance prompt designed for long-cycle conversations. Through a deterministic dynamic router, it completely decouples high-density technical engineering implementations from creative narrative workflows, effectively preventing context drift and over-engineering. Acting as a Middleware Layer governance structure, it serves as the "constitution" for the LLM execution environment. By constraining model weights, response structures, and cognitive pathways, it forces the LLM to remain strictly within developer-defined engineering boundaries. The V3 iteration further enhances stability with a self-audit loop and dynamic i18n protocols, ensuring maximum reliability in complex AI collaborations.

### Features
- Deterministic Context Routing: Automatically switches between DEV MODE, CREATIVE MODE, and HYBRID MODE, strictly isolating technical and narrative logic to prevent stylistic cross-contamination.
- Self-Audit Loop: Proactively detects knowledge gaps, incomplete logic chains, or output format drift, auto-generating constraints and completion prompts to halt error propagation.
- Convergence Gate & Zero-Tolerance Interrogation: Enforces an engineering sweet spot assessment to reject sub-marginal micro-optimizations. Instantly halts generation and demands crucial context when facing ambiguity, preventing hallucinations and blind development.
- Dynamic i18n Protocol: Mandates English for all internal reasoning to maximize LLM parsing efficiency, switching to the target language exclusively for code comments and external documentation.
- Literate Programming & Architecture Review: Standardizes dependency indices, function responsibilities, and inline state comments. Executes internal code reviews prior to output, checking for memory leaks, race conditions, and compatibility.
- Zero-Bloat & No-Apology Policy: Ruthlessly prunes emotional padding and low-value politeness. When encountering error logs, it executes an instant cognitive pivot to provide optimized code without apologies.

### Installation
```bash
# For GitHub Copilot / Cursor
# 1. Create the configuration file
touch .github/copilot-instructions.md

# 2. Copy the entire PWG-V3 core prompt and paste it into the file
# 3. Reload your editor or restart the AI assistant window to apply changes
```

### Usage
```bash
# For Web UI (e.g., ChatGPT, Claude) / API System Prompt
# 1. Navigate to system settings or the System Prompt configuration field
# 2. Inject the complete PWG-V3 markdown specification layer
# 3. If using an API, ensure the system_role is set with the highest authority
```

### License
This project is licensed under the MIT License, see [LICENSE](LICENSE).
