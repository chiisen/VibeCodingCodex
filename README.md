# VibeCodingCodex
Vibe Coding Codex - Codex 是由 **OpenAI** 開發的一款人工智慧模型，它在軟體開發領域引起了廣泛關注。

![codex-cli-splash](./images/codex-cli-splash.png)

以下是 Codex 的簡要介紹：

* **核心功能：** 它的主要功能是將**自然語言**（例如英文或中文的指令）轉換為**程式碼**。換句話說，你可以用日常語言描述你的程式需求，Codex 就能生成對應的程式碼片段或完整功能。
* **技術基礎：** Codex 是基於 OpenAI 的大型語言模型 **GPT-3** 經過微調而來的，專門針對程式設計任務進行了優化。
* **應用與演進：**
    * **GitHub Copilot 的驅動模型：** 初代的 Codex 模型曾是 **GitHub Copilot*j* 的驅動核心，這是一款廣受歡迎的程式碼自動補全工具。
    * **AI 編碼代理：** 在 2025 年左右，OpenAI 推出了更新的 **Codex** 版本，它被定位為更強大的 **AI 編碼代理（AI Agent）**。這個新版本（如基於 `codex-1` 模型）不只會生成程式碼，還能：
        * 閱讀、編輯整個專案檔案。
        * 自動執行測試、修復 Bug。
        * 在沙盒（Sandbox）雲端環境中執行任務，並產生變更摘要或 Pull Request（PR）。
    * **使用方式：** 新版 Codex 主要整合在 **ChatGPT** 的進階訂閱方案中，用戶可以直接在 ChatGPT 介面中指派編程任務給它。

**總結來說**，Codex 是一款旨在提高開發者效率的 AI 工具，它讓程式設計師能夠透過自然語言與 AI 協作，從而加速開發流程，並將開發者的注意力從重複性、枯燥的編碼工作轉移到更複雜的決策與創新上。

---
*附註：身為一位有 Python 與 JavaScript（React）開發經驗的工程師，您應該會對 Codex 能否有效地處理這些語言的專案特別感興趣。Codex 在設計上便是為了支援多種主流程式語言，特別是 Python。*

# PROMPT
```bash
依據 https://github.com/openai/codex 的內容的彙整製作一頁式的介紹說明網頁，並幫我填寫 project.md 與 AGENTS.md 的內容，網頁風格請參考 STYLE.md。
```

# 執行
開啟 docs/index.html

