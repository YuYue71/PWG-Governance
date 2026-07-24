# PWG-Governance

![Version](https://img.shields.io/badge/version-PWG--V2-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Tech](https://img.shields.io/badge/stack-Markdown%20%7C%20LLM%20%7C%20Prompting-lightgrey)

[中文](#中文) | [English](#english)

---

## 中文

### 目錄
- [關於](#關於)
- [功能](#功能)
- [對照表](#對照表)
- [安裝](#安裝)
- [使用方式](#使用方式)
- [授權](#授權)

### 關於
PWG-V2-OpenSource 是一款專為長對話週期設計的工業級, 零冗餘工作流治理提示詞. 透過確定性的動態路由器, 將高密度的技術工程實作與創意的敘事工作流完全解耦, 有效防止上下文漂移(Context Drift)與過度工程化(Over-engineering). 本框架屬於中介層(Middleware Layer)治理框架, 作為 LLM 執行環境的"憲法", 透過約束模型權重, 回應結構與思維路徑, 強制將 LLM 鎖定於開發者定義的工程邊界內.

### 功能
- 確定性上下文路由: 自動切換開發模式(DEV MODE)與創意模式(CREATIVE MODE), 防止風格交叉污染.
- 收斂閘門邏輯: 強制執行工程甜蜜點評估, 直接拒絕微幅優化, 防止遞迴優化循環.
- 底層豁免協議: 提供資深級的記憶體分析與逆向工程結構指引, 無須標準道德說教.
- 文學編程強制: 標準化代碼文檔, 在不增加 Token 消耗的前提下提升維護性.
- 零冗餘治理: 無情刪除情緒性填充詞, 人稱代名詞與冗餘修飾, 保持最大資訊密度.
- 零道歉政策: 消除所有低價值客套語句, 立即進行認知轉向並輸出最佳化方案.

### 對照表

| 項目 | 一般 Prompt | PWG-V2 |
| --- | --- | --- |
| 目標 | 解決特定問題 | 建立長期協作系統 |
| 回應風格 | 友善, 冗長 | 冷靜, 務實, 零冗餘 |
| 風險處理 | 預設規避與說教 | 依設定豁免, 提供底層指導 |
| 優化機制 | 鼓勵嘗試 | 收斂閘門(強制停止無效優化) |

### 安裝
```bash
# 針對 GitHub Copilot / Cursor
# 將完整核心提示詞複製到專案根目錄的指定檔案內
touch .github/copilot-instructions.md

```

### 使用方式

```bash
# 針對 Web UI / API System Prompt
# 將 markdown 規範層完整注入到 System Prompt 配置欄位

```

### 授權

本專案採用 MIT 授權, 詳見 [LICENSE](https://www.google.com/search?q=./LICENSE).

---

## English

### Table of Contents

* [About](https://www.google.com/search?q=%23about)
* [Features](https://www.google.com/search?q=%23features)
* [Comparison](https://www.google.com/search?q=%23comparison)
* [Installation](https://www.google.com/search?q=%23installation)
* [Usage](https://www.google.com/search?q=%23usage)
* [License](https://www.google.com/search?q=%23license)

### About

PWG-V2-OpenSource is an industrial-grade, zero-bloat workflow governance prompt designed for long-cycle conversations. Through a deterministic dynamic router, it completely decouples high-density technical engineering implementation from creative narrative workflows, effectively preventing context drift and over-engineering. This framework acts as a Middleware Layer governance structure, serving as the "constitution" for the LLM execution environment. By constraining model weights, response structures, and cognitive pathways, it forces the LLM to remain strictly within developer-defined engineering boundaries.

### Features

* Deterministic Context Routing: Automatically switches between DEV MODE and CREATIVE MODE to prevent stylistic cross-contamination.
* Convergence Gate Logic: Enforces an engineering sweet spot assessment to directly refuse sub-marginal micro-optimizations and prevent recursive loops.
* Low-Level Exemption Protocol: Provides veteran-level structural guidance for memory analysis and reverse engineering without standard moral lecturing.
* Literate Programming Enforcement: Standardizes code documentation for maintainability without inflating token consumption.
* Zero-Bloat Governance: Ruthlessly prunes emotional padding, personal pronouns, and redundant modifiers to maintain maximum information density.
* No-Apology Policy: Eliminates all low-value polite expressions, executing an instant cognitive pivot to provide optimized solutions directly.

### Comparison

| Item | Standard Prompt | PWG-V2 |
| --- | --- | --- |
| Objective | Solves specific problems | Builds long-term collaborative systems |
| Response Style | Friendly, verbose | Cold, pragmatic, zero-bloat |
| Risk Handling | Default avoidance and lecturing | Exempt based on settings, provides low-level guidance |
| Optimization Mech | Encourages experimentation | Convergence Gate (forces stop on invalid optimization) |

### Installation

```bash
# For GitHub Copilot / Cursor
# Copy the entire core prompt content into the specified file within your project root
touch .github/copilot-instructions.md

```

### Usage

```bash
# For Web UI / API System Prompt
# Inject the complete markdown specification layer into the System Prompt configuration field

```

### License

This project is licensed under the MIT License, see [LICENSE](https://www.google.com/search?q=./LICENSE).