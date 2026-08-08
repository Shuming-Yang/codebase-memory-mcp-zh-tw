# codebase-memory-mcp-zh-tw · codebase-memory-mcp 繁體中文教學站

[codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) 的**非官方**繁體中文教學站。把整個 repo（程式碼、文件、MCP 工具、測試、實作）做成中英對照的解說內容，並收錄真實工具產出的**可操作互動知識圖譜**示範。

> **免責聲明**：本站為第三方社群教學站，**與 DeusData 無關**，不代表 codebase-memory-mcp 官方立場。codebase-memory-mcp 與 DeusData 為其各自權利人所有，本站僅在描述性／教學語境下使用該名稱。

**上線網站：<https://shuming-yang.github.io/codebase-memory-mcp-zh-tw/>**

## 目錄

- [網站亮點](#網站亮點)
- [網站地圖](#網站地圖)
- [實作案例總覽](#實作案例總覽)
- [我們怎麼跑的](#我們怎麼跑的)
- [授權](#授權)
- [上游同步](#上游同步)
- [開發](#開發)
- [如何新增一個案例](#如何新增一個案例)
- [已知限制](#已知限制)
- [回饋與貢獻](#回饋與貢獻)

---

## 網站亮點

1. **中英對照** — 中文口語解說為主文，英文原文與程式碼保留上游原貌。文件頁用「可展開的英文原文」，程式碼頁用「附中文註解的原始碼」。
2. **純 C 逐函數講解** — 13 萬行 C 源碼挑「值得教學」的模組（mcp/store/cypher/cli/pipeline/daemon），每個函數一個 `<details>` 收縮塊（signature + 中文用途 + 關鍵邏輯）。
3. **策展式教學而非鏡像** — 2023 檔的 repo 不逐檔翻譯，聚焦 15 個 MCP 工具、圖資料模型、Cypher、Hybrid LSP、效能/安全。
4. **實機互動圖** — 用 graphify 掃描 CBM 自己，收錄真實互動知識圖譜（英文／中文界面雙版本），訪客可直接拖曳、搜尋、點節點。
5. **版本釘選** — 上游對齊 `main @ 2c50c77`（發行版 v0.9.0）；graphify 案例標註 graphify 0.9.36，數據可追溯。

## 網站地圖

純靜態站（HTML + CSS + JS），GitHub Pages 部署於 `main` 根目錄。

```
codebase-memory-mcp-zh-tw/
├── index.html            首頁：CBM 是什麼、三大亮點、入口卡
├── map.html              概念地圖：節點/邊/Cypher/15 工具/Hybrid LSP 概念節點
├── learning-path.html    學習路線 L0→L4：可點卡片
├── install.html          安裝指南：macOS/Linux/Windows、--ui、套件管理器、build from source
├── about.html            授權、方法、免責聲明
├── docs/
│   ├── index.html        文件教學入口（hub）
│   ├── how-it-works.html 運作原理（無內建 LLM／兩層解析／RAM-first）
│   ├── architecture.html 架構總覽（15 模組職責表）
│   ├── data-model.html   圖資料模型（13 節點／23 邊／qualified name）
│   ├── mcp-tools.html    15 個 MCP 工具全解
│   ├── cypher.html       openCypher 唯讀子集
│   ├── performance.html  效能基準
│   ├── security.html     安全模型
│   ├── daemon.html       Session Coordination Daemon
│   ├── config.html       設定
│   ├── graph-artifact.html  Team-Shared Graph Artifact
│   ├── multi-agent.html  43 平台整合
│   ├── changelog-summary.html  版本演進
│   ├── worked.html       實作案例入口
│   ├── case/cbm-source.html  案例：graphify 掃描 CBM 自己
│   └── code/             程式碼對照（12 頁，逐函數 <details>）
├── worked/cbm-source/    案例互動圖與報告（graph.html + graph-zh.html + GRAPH_REPORT.md）
└── assets/               site.css / favicon.svg
```

## 實作案例總覽

每個案例都是「中文解說 + 互動圖（EN/ZH 界面）+ 本站跑的數字 + 重現步驟」。

| 案例 | 語料 | 來源方式 | 本站數字 | 互動圖 |
|---|---|---|---|---|
| [**CBM 自己**](docs/case/cbm-source.html) | `src/` + `tests/` 440 個 C 檔 | **graphify 本站實跑**（`--code-only`，零 LLM），對齊 commit `2c50c77` | 15,815 節點 / 61,988 邊 / 343 社群 | ✅ 雙版本 |

> 所有案例的圖都是**真實工具產出**，不是示意圖。這是「用知識圖譜工具分析知識圖譜工具」的 meta 示範。

## 我們怎麼跑的

CBM 源碼案例用**本機 graphify CLI** 實際跑的（`graphify 0.9.36`）：

```bash
# 0. 安裝（PyPI 套件名是 graphifyy，雙 y）
uv tool install graphifyy

# 1. 準備語料（只保留第一方程式碼）
git clone https://github.com/DeusData/codebase-memory-mcp.git cbm
git -C cbm checkout 2c50c7741ec89dbcf43c2c85e005c0b58a4dbbf3
mkdir corpus && cp -R cbm/src corpus/ && cp -R cbm/tests corpus/

# 2. 跑完整 pipeline（code-only 抽取，純本機 AST、零 API key）
graphify corpus --code-only

# 3. 產出 graphify-out/：graph.html（互動）、graph.json、GRAPH_REPORT.md
# 4. 中文化互動圖：複製 graph.html → 替換 UI 字串 → graph-zh.html
```

- **CBM 本體**（本機也裝了 `codebase-memory-mcp 0.9.0`）：可用 `cli search_graph` / `cli query_graph` / `cli trace_path` 對語料做真實查詢（案例持續補充中）。

## 授權

- 本站內容以 **MIT License** 釋出（與上游相同），並照抄上游的授權檔：
  - [`LICENSE`](LICENSE) — MIT 全文（`Copyright (c) 2025 DeusData`）
  - [`NOTICE`](NOTICE) — 本站為上游非官方教學站的聲明、引用範圍、原創內容授權
- **商標**：codebase-memory-mcp 與 DeusData 為其各自權利人所有。MIT 授權不含商標授權；本站僅在「描述性／教學」語境使用該名稱，並於全站 footer 標示「與 DeusData 無關」。
- **graphify 產出**：`worked/cbm-source/` 的互動圖與報告由 graphify（Apache-2.0）產生，案例頁已標註出處。
- **不做二進位散布**：本站不含官方二進位，因此上游 vendored 第三方元件的 NOTICES 義務不適用於本站；相關清單見上游 [THIRD_PARTY.md](https://github.com/DeusData/codebase-memory-mcp/blob/main/THIRD_PARTY.md)。

## 上游同步

- 本站對齊上游分支 **`main`**，釘選 commit **`2c50c77`**（發行版 v0.9.0）。
- `.github/workflows/check-upstream.yml` **每月自動**檢查上游最新 SHA，並更新首頁的版本徽章。

## 開發

靜態站，純 HTML + CSS + JS，無框架、無建置步驟。

```bash
python3 -m http.server 8000   # 本機預覽
```

### 目錄結構速查

- `assets/site.css` — 全站樣式（深色 × 霓虹設計語言，承襲 graphify-zh-tw / mattpocock-skills-zh-tw）
- 每個 HTML 頁都是自含檔案（head 引入 site.css + Google Fonts）
- `worked/cbm-source/` — 案例的 `graph.html`（英文）、`graph-zh.html`（中文界面）、`GRAPH_REPORT.md`

## 如何新增一個案例

1. **準備語料**：`mkdir raw && git clone <repo> raw/<name>`（或直接指一個資料夾）。
2. **抽取**：`graphify extract ./raw --code-only`（純程式碼零 key）。
3. **分群 + 產出**：`graphify cluster-only ./raw` → 得到 `graph.html`、`GRAPH_REPORT.md`、`graph.json`。
4. **中文化**：複製 `graph.html` → 替換 UI 字串 → `graph-zh.html`。
5. **收錄**：把三樣東西放進 `worked/<slug>/`。
6. **建案例頁**：依 `docs/case/<slug>.html` 的模板（中文解說 + iframe 嵌入互動圖 + 本站數字表 + 重現步驟）。
7. **更新** `docs/worked.html` 的案例卡。

## 已知限制

- **CBM 案例的節點數**排除 vendored grammars（974 檔生成碼）與 docs，不代表全 repo（2023 檔）。
- **互動圖是社群聚合檢視**：15,815 節點超過 graphify 的 5,000 節點視覺化上限，自動聚合為 343 社群節點；想看單節點細節可用 `graph.json`。
- **graphify 的 Leiden 與 CBM 的 Louvain 演算法不同**——數字不直接可比，案例只做結構對照。
- **程式碼對照頁**已全數完成（12 頁，對齊上游 `main @ 2c50c77`）。

## 回饋與貢獻

- 本站是教學站，不是官方文件。發現翻譯錯誤或想補充主題，歡迎開 [issue](https://github.com/Shuming-Yang/codebase-memory-mcp-zh-tw/issues)。
- 想貢獻案例：跑一個真實 repo 的 graphify 產出，依[新增案例流程](#如何新增一個案例)發 PR。

---

**相關連結**

- 上游 repo：[DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)（MIT）
- 研究論文：[arXiv:2603.27277](https://arxiv.org/abs/2603.27277)
- 本站 repo：[Shuming-Yang/codebase-memory-mcp-zh-tw](https://github.com/Shuming-Yang/codebase-memory-mcp-zh-tw)
- 本站上線：[shuming-yang.github.io/codebase-memory-mcp-zh-tw](https://shuming-yang.github.io/codebase-memory-mcp-zh-tw/)
