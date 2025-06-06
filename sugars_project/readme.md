您好！感謝您點開我的 GitHub 專案。我是 [陳彥豪](https://github.com/YenHao-coder)，一位熱衷於程式開發的工程師，目前正積極尋找能貢獻技術並共同成長的機會。  
已將[甜點線上商城專案](http://sugars.byethost5.com/project01_cloud/)部署至雲端，透過以下連結您可以即時預覽：[🚀 專案預覽](http://sugars.byethost5.com/project01_cloud/)  

## **📖專案簡介**
這是一個模組化開發的模擬電商購物平台，展示我在前端開發、前後端協作以及網站部署方面的綜合能力。核心功能涵蓋了使用者互動與資料管理，為使用者提供流暢的購物體驗。  
資料庫連結請自行建立。請求路徑"Connections/conn_db.php"

## **👍專案優勢與特色**
  1. 直觀清晰的網站地圖引導[^1]：我高度重視使用者體驗，因此為此專案設計了簡潔直觀的網站導航。您可以輕易地在以下頁面之間切換
  ![網站導覽列]()
  > *首頁* | *商品分類* | *訂單查詢* | *會員登入* | *購物車* | *會員註冊*

  2. 高效穩定的前後端資料互動[^2]：
     專案前端透過 AJAX 技術與後端 PHP 進行非同步資料交換，實現了：
     * 無刷新頁面加載：使用者在瀏覽商品或操作購物車時，無需重新整理頁面即可即時更新內容，大幅提升操作流暢度。
     * 動態數據展示：商品資訊、購物車內容等均從 MySQL 資料庫動態提取並渲染，確保數據的即時性和準確性。

  3. 穩健的網站部署與問題解決能力：
  獨立完成了整個專案的從本地端到雲端主機（Byet.host）的部署過程。包含：  
  - 檔案權限設定 (```644```、```755```、資料庫連線檔 ```600```) 的精確掌握，確保網站運行安全。
  - MySQL 資料庫的建立、匯入與連線配置。
  - 面對部署過程中常見的 ```500 Internal Server Error``` 及 ```SQLSTATE[HY000] [2002] No such file or directory``` 等問題時，我能迅速定位錯誤原因（例如：資料庫主機名稱配置錯誤），並透過錯誤日誌追蹤與設定檔調整（```ini_set('display_errors', 1); ```等）有效解決。

  4. 基於標準技術棧的實戰經驗：
  此專案使用了業界主流且穩定的技術：  
  - 前端： **HTML5**, **CSS3** (響應式設計，確保跨裝置瀏覽體驗), **JavaScript** (運用 jQuery 提升開發效率)。
  - 後端：**PHP** (核心邏輯處理), **MySQL** (數據儲存與管理)。
  - 資料庫連線： 採用 PDO (PHP Data Objects) 實現資料庫安全連線，並搭配 ``` try...catch ```進行錯誤處理。

## ☀️未來展望與自我提升
我深知技術領域的日新月異，並持續學習與進步技術。未來，我計劃為此專案導入：
> - 更完善的安全性措施：例如使用 prepared statements 防止 SQL 注入、更嚴格的輸入驗證。
> - 前端框架應用：嘗試整合 Vue.js 或 React，提升組件化和開發效率。
> - 優化載入效能：進行圖片壓縮、資源懶加載等優化。
***
## 🤝期許與邀請
> 透過這個專案，我希望您能看到我作為前端工程師在技術實作、問題解決、使用者導向思維以及獨立專案管理上的潛力。無論是作為新人工程師快速學習成長，或是作為資深工程師貢獻解決方案，我都已準備好迎接挑戰。期待能有機會與您進一步交流，深入探討我的專案細節與未來發展方向。

## 陳彥豪🇹🇼
## 📬[Email: lgr504123@gmail.com](lgr504123@gmail.com)
## 📃[LinkedIn: 陳彥豪](https://www.linkedin.com/in/%E5%BD%A5%E8%B1%AA-%E9%99%B3-441506331/)

> [!CAUTION]
> 特別聲明：本專案為個人學習與技術展示目的，其中部分商品數據及圖片內容引用自參考網站，該內容版權歸原網站所有。
> [參考網站](https://www.sugar.com.tw/?srsltid=AfmBOorVBnhjPcq6SgwkNM5cw8JLupH2q6ySEnfZTQQZjbz2W-hOkaKq)


[^1]:[點擊此處查看網站地圖及主要頁面說明] (請替換為您 GitHub README 中指向網站地圖或關鍵頁面截圖的連結)

[^2]:AJAX技術: [會員驗證]() | [訂單驗證]() | [鄉鎮市查詢]() | [縣市查詢]()
