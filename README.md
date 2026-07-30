# sheep_enya
由 EZPage 建立的網站 - Deployed by EZPage

---

<!-- BEGIN:PROJECT_GUIDE -->
## 專案導覽

由 EZPage 建立的網站 - Deployed by EZPage

- 專案定位：主題網站／活動資訊專案
- Repository：`cagoooo/sheep_enya`
- 可見性：公開
- 主要技術：HTML
- 線上入口：[https://cagoooo.github.io/sheep_enya](https://cagoooo.github.io/sheep_enya)

### 可以怎麼應用

- 活動導覽、成果展示、親師生資訊發布
- 依新的活動、校本主題或旅遊內容複製調整
- 作為響應式單頁網站與 GitHub Pages 發布範例

這些是依目前專案定位整理的延伸方向，不代表所有情境都已內建完成；實作前請先確認現有功能與資料格式。

### 技術與專案結構

- `README.md`
- `index.html`

檔案結構會隨版本演進；若本節與程式碼不一致，以目前預設分支的原始碼為準。

### 本機執行

這是可直接由瀏覽器載入的靜態網站。可用任一靜態檔案伺服器預覽，例如：
```bash
python -m http.server 8000
```
接著開啟 `http://localhost:8000`。請避免直接以 `file://` 測試需要模組、請求或 Service Worker 的功能。

### 給 AI Agent 的接手指南

1. 先閱讀本 README、`AGENTS.md`（若有）、套件腳本與部署設定。
2. 先確認內容資料、導覽結構、外部連結與部署入口。
3. 更新文字與圖片時檢查版權、替代文字、手機閱讀與連結有效性。
4. 發布前驗證主要頁面、導覽、互動元件與 GitHub Pages 路徑。
5. 不要捏造尚未存在的功能；README 與實作有落差時，應同時更新文件。
6. 提交前只納入本次任務檔案，並記錄實際執行過的驗證。

### 安全與資料注意事項

- 不要提交 `.env`、服務帳號、API 金鑰、token、學生個資或正式環境匯出資料。
- 使用 Firebase、Supabase、Google API 或其他雲端服務時，請建立自己的測試專案並套用最小權限。
- 若要公開衍生作品，請先確認程式碼、圖片、音訊、字型與教材內容的授權。

### 貢獻與客製化

歡迎依教學現場、活動或工作流程需求進行 fork／客製化。建議在變更說明中交代使用情境、主要修改、測試方式，以及是否影響資料格式或部署設定。
<!-- END:PROJECT_GUIDE -->
