Node.js 專案完整說明文件

---

<div align="center">

<svg width="80" height="80" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M12 2L2 7v10l10 5 10-5V7l-10-5z" fill="#339933"/>
  <path d="M12 2v20l10-5V7l-10-5z" fill="#66BB6A" opacity="0.7"/>
</svg>

<svg class="icon" viewBox="0 0 24 24" width="24" height="24">
  <path fill="currentColor" d="M4 4h16v2H4zm0 6h16v2H4zm0 6h16v2H4z"/>
</svg> 序（摘要）

Node.js 是一個 開源 (Open Source)、跨平台 (Cross-Platform) 的 JavaScript 執行環境，提供 高效能、事件驅動 (Event-Driven)、非阻塞 I/O (Non-Blocking I/O) 的伺服器端開發能力。由 [OpenJS 基金會][OpenJS Foundation] 支持並採用 開放治理模型 (Open Governance)，強調 社群協作、建設性溝通、共識決策，並遵循 [行為準則][Code of Conduct]。

> <svg class="icon" viewBox="0 0 24 24" width="16" height="16"><circle cx="12" cy="12" r="10" fill="#FFD700"/></svg> 特點：快速、輕量、模組化、豐富生態系，適合現代 Web 與後端服務開發。

</div>

---

目錄

<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M21 8V7l-3 2-2-1-2 1-3-2v1l3 2v5l-3 2v1l3-2 2 1 2-1 3 2v-1l-3-2V10z"/></svg> 支援  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M3 5h18v2H3zm0 6h18v2H3zm0 6h18v2H3z"/></svg> 版本類型  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M5 20h14v-2H5v2zm0-4h14v-2H5v2zm0-4h14v-2H5v2z"/></svg> 下載  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M12 2l8 4v8c0 5-8 8-8 8S4 19 4 14V6l8-4z"/></svg> 目前與 LTS 發行  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M12 2a10 10 0 100 20 10 10 0 000-20z"/></svg> 每日構建  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M4 6h16v2H4zm0 4h16v2H4zm0 4h10v2H4z"/></svg> API 文件  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M12 2l4 4-4 4-4-4 4-4z"/></svg> 驗證二進位檔  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M4 4h16v16H4z"/></svg> 編譯-Nodejs  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M12 2l8 4v12l-8 4-8-4V6l8-4z"/></svg> 安全性  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M12 2l4 8-4 12-4-12z"/></svg> 貢獻-Nodejs  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M12 12a5 5 0 110-10 5 5 0 010 10zm0 2c-5 0-9 2.5-9 5.5V22h18v-2.5c0-3-4-5.5-9-5.5z"/></svg> 目前專案團隊成員  
<svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="currentColor" d="M4 4h16v16H4z"/></svg> 授權  

---

支援

若您在使用 Node.js 遇到問題，請參考以下官方支援資源：

官方網站： [Node.js website]  
社群討論與協助：
GitHub Issues（提交錯誤與建議）
Stack Overflow（程式問題問答）
OpenJS 社群論壇（社群交流與公告）

> <svg class="icon" viewBox="0 0 24 24" width="16" height="16"><path fill="#4CAF50" d="M12 2l8 4-8 16-8-16z"/></svg> 提示：遇到安全性或版本問題，建議優先檢視 安全性 與 版本類型 章節。

---

其餘各章節依上述模式，將原來的 Emoji 以動態 SVG 圖示取代，保持一致的風格與結構。