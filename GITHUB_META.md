# GitHub Repo Metadata（About + Topics）

> 這個檔案紀錄本站 repo 的 About 描述與 topics，供有 admin 權限的帳號套用。
> 設定需要 admin 權限（目前 gh 帳號 `shumingyang-opencode` 僅有 write，無法設定）。

## About（Description）

```
codebase-memory-mcp（MIT）的非官方繁體中文教學站——把整個 repo（程式碼／文件／MCP 工具／測試／案例）做成中英對照講解：概念地圖、學習路線、安裝指南、13 個文件教學頁、12 個程式碼對照頁，並收錄用 graphify 掃描 CBM 自己做出的可操作互動知識圖譜。
```

## Topics（16 個）

```
codebase-memory-mcp
mcp
mcp-server
knowledge-graph
code-analysis
code-intelligence
developer-tools
opencode
chinese-translation
traditional-chinese
github-pages
i18n
documentation
educational
graphify
open-source
```

## 套用指令

用有 admin 權限的帳號（Shuming-Yang）執行：

```bash
# 切換到有 admin 權限的帳號
gh auth switch --user Shuming-Yang

gh repo edit Shuming-Yang/codebase-memory-mcp-zh-tw \
  --description "codebase-memory-mcp（MIT）的非官方繁體中文教學站——把整個 repo（程式碼／文件／MCP 工具／測試／案例）做成中英對照講解：概念地圖、學習路線、安裝指南、13 個文件教學頁、12 個程式碼對照頁，並收錄用 graphify 掃描 CBM 自己做出的可操作互動知識圖譜。"

gh repo edit Shuming-Yang/codebase-memory-mcp-zh-tw \
  --add-topic codebase-memory-mcp \
  --add-topic mcp \
  --add-topic mcp-server \
  --add-topic knowledge-graph \
  --add-topic code-analysis \
  --add-topic code-intelligence \
  --add-topic developer-tools \
  --add-topic opencode \
  --add-topic chinese-translation \
  --add-topic traditional-chinese \
  --add-topic github-pages \
  --add-topic i18n \
  --add-topic documentation \
  --add-topic educational \
  --add-topic graphify \
  --add-topic open-source
```
