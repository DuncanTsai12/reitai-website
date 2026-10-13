# 銳泰國際企業網站重新設計

繁體中文、多頁式、響應式靜態網站，可直接上傳 GitHub Pages。無需安裝套件或編譯。

## 預覽
直接打開 `index.html`；或在此資料夾執行 `python -m http.server 8000` 後，開啟 http://localhost:8000。

## GitHub Pages 上線
1. 在 GitHub 新增 repository，將本資料夾內所有檔案上傳至 repository 根目錄（包含 assets）。
2. 到 Settings → Pages，Source 選 Deploy from a branch。
3. Branch 選 main，資料夾選 / (root)，按 Save。
4. 等待 GitHub 顯示網站網址。本站使用相對連結，支援 repository 子路徑。

## 網站架構
- 首頁 `index.html`
- 公司簡介 `about.html`
- 運作原理與功效 `technology.html`
- 應用領域總覽 `applications.html`
  - 食品加工 `application-food.html`
  - 冷藏冷凍 `application-cold-storage.html`
  - 汽車運輸 `application-transport.html`
  - 居住、飯店、辦公及公共環境 `application-buildings.html`
  - 其他／工業 `application-industrial.html`
- 設備介绍 `equipment.html`
- 驗證與案例 `evidence.html`
- 資料下載 `downloads.html`

## 修改方式
各 HTML 包含完整內容，不依賴 JavaScript 才能閱讀。樣式在 assets/style.css；手機選單在 assets/main.js。主選單與頁尾共用相同版型，修改導覽時須同步修改各 HTML。

## 內容來源與上線前核對
內容、品牌標誌、照片及圖表取自使用者提供的《2026銳泰公司簡介與應用說明.pdf》（44 個實際 PDF 頁面，文件自身頁尾顯示 /45）。原官網已失效，依使用者確認，以公司簡介標題作為重建網站的內容架構。

文字按網頁閱讀方式整理，原 PDF 完整附於 assets/company-profile-2026.pdf。原始規劃圖與型號表以圖片保留，點選可放大，下載區可閱讀完整文件。數據、客戶名單與驗證結果均註明來源；醫療功效與無條件安全保證未作額外宣傳。

目前未取得可核實的電話、信箱、地址，故未編造聯絡資訊或設置無法送出的表單。正式上線前可補充聯絡頁及確認資料、圖片使用權、最新規格和完整測試報告。本站無後端、追蹤碼、外部字型或套件依賴。


## 驗證紀錄
12 個 HTML 頁面已通過本機連結、圖片路徑、頁面主標題與主要內容區、圖片替代文字檢查。CSS 包含桌面與手機斷點；瀏覽器預覽受目前環境連線限制，未完成實際桌面／手機畫面驗證。
