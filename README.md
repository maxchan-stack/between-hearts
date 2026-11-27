# 心之間 BETWEEN HEARTS V6.0
高中 SEL 情境牌卡，六大面向。不需登入或後端。sessionStorage 保存各面向已抽牌，localStorage 保存收藏，不上傳紀錄。首次連線完成離線快取後才可離線使用。

## 維護
- data/cards.json：牌卡文字及面向 ID；data/dimensions.json：面向與藝術屬性。
- domain.mjs：驗證、抽卡、路由；app.mjs：畫面及互動；art.mjs：向量插畫；styles.css：版面。
- 本機：python -m http.server 8000，開啟 http://localhost:8000/。測試：node scripts/test.mjs。
- GitHub Pages：main 根目錄。發版時同步更新 service worker 快取名稱和資源版本。
- 列印：首頁「列印牌卡」，A4、100% 比例、雙面長邊翻轉（需先試印校準）；亦可另存 PDF。
- 投影：首頁課堂投影或結果頁投影切換。
- V6.0：資料拆分、不重複抽卡、hash 導覽、無障礙、離線、收藏及投影與列印。
- 仍待 iOS/Android 實機及實際印刷校準；字型採系統 fallback。

## V6.1 版面規範
320–374 CSS px：金句 24、提問 22、微行動 18px；375–413：26／24／19；414–599：28／26／20；600以上：32／28／22。以 rem 實作，允許使用者調整瀏覽器字級，內容過高自然捲動，不按句長縮字。按鈕最小高度 44 CSS px。離線採版本化資源與等待更新提示，避免新舊檔案混搭。仍須實機與輔具驗收。

## V6.2 封面視覺
取消閉眼大標，保留引導語，六大面向採各自不規則柔和色塊，保留可辨識選取狀態與鍵盤焦點；底部原文不變。