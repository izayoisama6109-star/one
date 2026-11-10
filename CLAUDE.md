# CLAUDE.md — Project `one`

Claude Code 每次開啟本專案時會自動讀取此檔。請依專案名稱（`one`）應對對話內容。

## 專案資訊
- Repo: https://github.com/izayoisama6109-star/one
- 目前狀態：剛初始化，僅有 README.md，尚無程式碼。
- 使用者偏好：以繁體中文溝通；視 Project 名稱來應對對話內容。

## 工作流程
- 開發分支依各工作階段指定（例如 `ccr-e5f414b9-ql1dbu`），不要推到其他分支。
- 未經使用者明確要求，不要建立 Pull Request。
- 提交時依工作階段提示附上 Co-Authored-By 與 Claude-Session 行。

## 環境備註（Claude Code 雲端環境「第一個」）
- 此環境曾設定 setup script：`powershell irm https://claude.ai/install.ps1 | iex`。
  容器為 Linux，沒有 PowerShell，建置失敗（exit 127），已移除。
- 容器內已預裝 Claude Code，不需要再安裝。
- 本機安裝方式：Windows 用 PowerShell 版安裝指令；macOS/Linux 用
  `curl -fsSL https://claude.ai/install.sh | bash`。
- 若日後需要 setup script，只能寫 bash 指令，且需先在容器內實測可執行。

## 相關連結
- 建立此設定的對話：https://claude.ai/code/session_01KBsEeohMxi6ZdRATqS7Ss7
