🌐 Node.js 專案完整說明文件

---

<div align="center">

📜 序（摘要）

Node.js 是一個 開源 (Open Source)、跨平台 (Cross-Platform) 的 JavaScript 執行環境，提供 高效能、事件驅動 (Event-Driven)、非阻塞 I/O (Non-Blocking I/O) 的 伺服器端開發能力。由 [OpenJS 基金會][OpenJS Foundation] 支持並採用 開放治理模型 (Open Governance)，強調 社群協作、建設性溝通 與 共識決策，並遵循 [行為準則][Code of Conduct]。

> 🌟 特點：快速、輕量、模組化、豐富生態系，適合現代 Web 與後端服務開發。

</div>

---

📑 目錄

📞 支援
🗂 版本類型
📥 下載
📦 目前與 LTS 發行
🌙 每日構建
📚 API 文件
🔐 驗證二進位檔
🛠 編譯-Nodejs
🛡 安全性
🤝 貢獻-Nodejs
👥 目前專案團隊成員
📄 授權

---

📞 支援

若您在使用 Node.js 遇到問題，請參考以下官方支援資源：

官方網站：[Node.js website]
社群討論與協助：
GitHub Issues（提交錯誤與建議）
Stack Overflow（程式問題問答）
OpenJS 社群論壇（社群交流與公告）

> 💡 提示：遇到安全性或版本問題，建議優先檢視 安全性 與 版本類型 章節。

---

🗂 版本類型

<table>
<thead>
<tr>
<th>類型</th><th>特點</th><th>支援週期</th><th>範例版本</th>
</tr>
</thead>
<tbody>
<tr>
<td>**Current（目前版）**</td>
<td>持續開發中，包含最新功能，可能含破壞性變更</td>
<td>8 個月</td>
<td>v22.x</td>
</tr>
<tr>
<td>**LTS（長期支援）**</td>
<td>專注穩定性與安全性，偶數版本號成為 LTS</td>
<td>主動支援 12 個月 + 維護 18 個月</td>
<td>v20.x Hydrogen</td>
</tr>
<tr>
<td>**Nightly（每日構建）**</td>
<td>每日自動編譯，用於測試與實驗</td>
<td>無正式支援</td>
<td>v22.0.0-nightly20240424ddd0a9e494</td>
</tr>
</tbody>
</table>

> 📌 發行規則：Node.js 每年 四月與十月 發布主要版本，十月版 優先進入 LTS 線路。

---

📥 下載

最新版本二進位、安裝程式與原始碼：https://nodejs.org/en/download/
LTS 與歷史版本：https://nodejs.org/download/release/
每日構建版：https://nodejs.org/download/nightly/

> 💾 提示：latest 目錄指向最新目前版本；latest-codename 指向 LTS 版本，例如 latest-hydrogen。

---

📦 目前與 LTS 發行

Node.js 遵循 語意化版本 (SemVer) 規範，由 發行團隊簽署。發行包目錄結構範例如下：

/v22.x/
  ├─ bin/
  ├─ docs/
  ├─ SHASUMS256.txt.asc

> 詳細說明請參考 Release README。

---

🌙 每日構建

檔名格式：

v<主版本>.<次版本>.<修訂版>-nightly<YYYYMMDD><commitSHA>

範例： v22.0.0-nightly20240424ddd0a9e494
包含 UTC 日期 與 短提交 SHA，僅建議用於 測試環境。

---

📚 API 文件

最新版本文件：https://nodejs.org/api/
指定版本文件：https://nodejs.org/download/docs/

> 📂 各版本 API 文件可在 下載包的 docs/ 目錄 中找到。

---

🔐 驗證二進位檔

下載對應版本的 SHASUMS256.txt.asc
取得信任金鑰

curl -fsLo "/path/to/nodejs-keyring.kbx" \
  "https://github.com/nodejs/release-keys/raw/HEAD/gpg/pubring.kbx"
驗證檔案

curl -fsO "https://nodejs.org/dist/${VERSION}/SHASUMS256.txt.asc" \
&& gpgv --keyring="/path/to/nodejs-keyring.kbx" --output SHASUMS256.txt < SHASUMS256.txt.asc \
&& shasum --check SHASUMS256.txt --ignore-missing

---

🛠 編譯 Node.js

請參考 BUILDING.md 了解如何 從原始碼編譯 Node.js 及 支援平台列表。完成編譯後，可進行 單元測試 (Unit Test) 以確保功能完整性與穩定性。

---

🛡 安全性

漏洞回報請參見 SECURITY.md
所有重大安全更新將於 LTS 線優先發布

---

🤝 貢獻 Node.js

[貢獻專案][Contributing to the project]
[工作小組][Working Groups]
[策略性倡議][Strategic initiatives]
[技術價值與優先順序][Technical values and prioritization]

> ⚠️ 注意：請遵循 [行為準則][Code of Conduct] 及 貢獻流程，TSC 保留處理負面行為的權限。

---

👥 目前專案團隊成員

請參見 GOVERNANCE.md 了解完整團隊與治理架構，包括：

TSC（技術指導委員會）
協作者 (Collaborators)
問題分流者 (Triagers)
發行金鑰與安全性管理者

---

📄 授權

Node.js 使用 MIT 授權。

專案亦依賴第三方開源函式庫，詳細授權內容請參見 LICENSE。

> 💡 提示：貢獻原始碼或文件時，請確認符合授權規範。

---

[Node.js website]: https://nodejs.org/
[OpenJS Foundation]: https://openjsf.org/
[Code of Conduct]: https://github.com/nodejs/admin/blob/HEAD/CODEOFCONDUCT.md
[Contributing to the project]: CONTRIBUTING.md
[Working Groups]: https://github.com/nodejs/TSC/blob/HEAD/WORKING_GROUPS.md
[Strategic initiatives]: doc/contributing/strategic-initiatives.md
[Technical values and prioritization]: doc/contributing/technical-values.md
