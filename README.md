# 🧭 創業策略思考知識庫暨麥肯錫簡報教材門戶 (Startup Strategy & Executive Briefing Portal)

> **系統歸屬**：大衛雲 2.0 ｜ A1. 事業職涯 ▸ A1.4 創業 ▸ A1.4.1 策略思考  
> **視覺規範**：McKinsey & Company Executive Briefing Standard（深藍 Navy `#051C2C` × 亮藍 `#0066CC` × 琥珀金 `#D97706`）  
> **線上網址**：[https://davidyeh51.github.io/startup-strategy-portal/](https://davidyeh51.github.io/startup-strategy-portal/)

---

## 🎯 核心功能與架構特色

1. **支援 50+ 本書籍模組化擴充之入口網站 (`index.html`)**
   - 依六大創業策略領域（商業模式與超級個體、精益驗證與產品矩陣、品牌定位與私域增長、AI 組織與逆分工架構、企業破繭與新事業開發、領導力與高績效教練）分類檢索。
   - 內建「6P 創業全鏈路戰略視覺地圖（SVG 互動架構圖）」、「學員四大處境快速分流診斷表」與「跨書策略法則對照總表」。

2. **毫秒級全站跨書／跨簡報頁關鍵字深層檢索 (`search-index.js` + `app.js`)**
   - 學員於首頁或簡報內輸入任何關鍵字（如 `6P`、`老媽測試`、`MVP`、`私域`、`7-11-4`、`孔乙己`、`定價`、`非雇傭`、`數位槓桿`、`老鼠陷阱`、`高績效教練`、`逆分工`、`FDE`），系統即時檢索所有書籍與每一頁簡報。
   - 支援**關鍵字螢光高亮標記 (`<mark>`)** 與 **「直達該簡報頁 →」** 單頁精準跳轉（`?q=關鍵字#slide-XX`）。

3. **首發完整教材：BOOK #001《把熱愛變成事業：等著每月領工資，是人生最大的陷阱》（凱莉彭）**
   - 線上互動簡報教材：[`book-passion-to-business.html`](https://davidyeh51.github.io/startup-strategy-portal/book-passion-to-business.html)（共 16 頁完整麥肯錫簡報）。
   - 離線 PowerPoint 簡報：[`downloads/passion-to-business-mckinsey-briefing.pptx`](./downloads/passion-to-business-mckinsey-briefing.pptx)。
   - **雙視覺保證**：全 16 頁簡報**每一頁皆同時具備「麥肯錫 SVG 戰略模型圖 / 視覺插畫 (Exhibit 1–16)」與「結構化比較／落地行動表格 (Table 1–16)」**，並附帶三段式顧問講稿備忘錄（快捷鍵 `N` 開關）。

---

## ➕ 未來新增書籍教材標準作業流程 (Book #002 ~ #050)

1. 將新書 PDF 與逐章分析 `.md` 放入 `參考書籍/`。
2. 複製簡報模板建立 `book-{slug}.html`（維持每頁 Action Title 結論先行 ＋ Exhibit 圖表 ＋ 結構化表格 ＋ 講稿備忘錄）。
3. 於 `search-index.js` 的 `books` 與 `slides` 陣列新增該書元資料與逐頁索引，全站搜尋與領域分類即自動生效。
