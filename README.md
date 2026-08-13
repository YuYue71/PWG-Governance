# PWG-Governance

[中文](#中文) | [English](#English)

---

## 中文

### 目錄

* [關於](#關於)
* [功能](#功能)
* [安裝](#安裝)
* [使用方式](#使用方式)
* [授權](#授權)

### 關於

PWG-V3-LLM-Optimized 是一款專為長對話週期設計的工業級, 零冗餘工作流治理提示詞(System Prompt). 作為 LLM 執行環境的「憲法」, 它透過確定性的動態路由與嚴格的自我稽核機制, 將高密度的技術工程實作與創意的敘事工作流完全解耦. 此框架能有效約束模型權重, 防堵上下文漂移(Context Drift), 並強制終止無意義的微觀優化, 將 LLM 牢牢鎖定於開發者定義的專業工程邊界內.

### 功能

* 確定性狀態機路由(Deterministic Context Routing): 強制解耦 DEV MODE 與 CREATIVE MODE, 並提供 HYBRID MODE 的安全融合規範, 防止語氣與邏輯交叉污染.
* 動態語言分離協議(Dynamic I18n Protocol): 強制 LLM 內部邏輯推演使用英文, 僅在最終輸出與註解使用目標語言, 貼合底層模型訓練權重以提升運算精準度.
* 零容忍審訊與防幻覺(Zero-Tolerance Interrogation): 當遭遇模糊需求時, 強制中斷生成並拋出具體問題清單, 嚴禁基於假設的盲目代碼生成.
* 收斂閘道(Convergence Gate): 評估優化的邊際效益(Marginal Benefit), 抵達工程甜蜜點後強制拒絕進一步的過度工程化(Over-engineering).
* 強制代碼審查與文檔規範(Code Review & Literate Programming): 規範依賴索引, 函式職責與內聯註解, 並在輸出前自動執行邊界條件檢查.
* 嚴格的技術否決權(Direct Veto): 賦予框架直接駁回不良架構設計的權力, 取消無意義的客套話, 提供資深級的直接工程糾正.

### 安裝

```bash
# 針對 GitHub Copilot / Cursor
# 1. 在專案根目錄建立 .github 資料夾
# 2. 建立 copilot-instructions.md 檔案
# 3. 將 PWG-V3 的完整核心提示詞內容複製並貼入該檔案中
touch .github/copilot-instructions.md

```

### 使用方式

```bash
# 針對 Web UI (如 ChatGPT, Claude) / API 系統提示詞
# 1. 開啟設定介面或 API 配置
# 2. 找到 System Prompt (或 Custom Instructions) 欄位
# 3. 將整份 PWG-V3 規範層文件完整貼入, 確認覆蓋原有設定後儲存

```

### 授權

本專案採用 MIT 授權, 詳見 [LICENSE](https://www.google.com/search?q=./LICENSE).

---

## English

### Table of Contents

* [About](#About)
* [Features](#Features)
* [Installation](#Installation)
* [Usage](#Usage)
* [License](#License)

### About

PWG-V3-LLM-Optimized is an industrial-grade, zero-bloat workflow governance prompt (System Prompt) designed for extended conversational cycles. Acting as the "constitution" for the LLM execution environment, it completely decouples high-density technical engineering implementation from creative narrative workflows through deterministic dynamic routing and strict self-auditing mechanisms. This framework effectively constrains model weights, prevents context drift, and forcibly halts meaningless micro-optimizations, keeping the LLM strictly locked within the professional engineering boundaries defined by the developer.

### Features

* Deterministic State-Machine Routing: Forcibly decouples DEV MODE and CREATIVE MODE, while providing safe integration rules via HYBRID MODE, preventing stylistic and logical cross-contamination.
* Dynamic I18n Protocol: Mandates the LLM to use English for internal logical reasoning, deploying the target language only in the final output and code comments. This aligns with base model training weights to maximize computational precision.
* Zero-Tolerance Interrogation & Anti-Hallucination: Upon encountering ambiguous requirements, it halts generation immediately and outputs a concrete list of questions, strictly prohibiting blind code generation based on assumptions.
* Convergence Gate: Evaluates the marginal benefit of optimizations. Once the engineering sweet spot is reached, it automatically rejects further over-engineering.
* Enforced Code Review & Literate Programming: Standardizes dependency indices, function responsibilities, and inline commenting, while automatically executing edge-case checks before final output.
* Direct Technical Veto: Grants the framework the authority to directly reject flawed architectural designs, eliminating meaningless politeness and providing veteran-level, direct engineering corrections.

### Installation

```bash
# For GitHub Copilot / Cursor
# 1. Create a .github directory in your project root.
# 2. Create a copilot-instructions.md file.
# 3. Copy and paste the entire core prompt of PWG-V3 into this file.
mkdir -p .github
touch .github/copilot-instructions.md

```

### Usage

```bash
# For Web UI (e.g., ChatGPT, Claude) / API System Prompts
# 1. Open the settings interface or API configuration.
# 2. Locate the System Prompt (or Custom Instructions) field.
# 3. Paste the complete PWG-V3 specification document into the field and save.

```

### License

This project is licensed under the MIT License, see [LICENSE](https://www.google.com/search?q=./LICENSE).
