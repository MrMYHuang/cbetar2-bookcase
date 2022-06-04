 # CBETA 電子佛典閱讀器 2 離線經文下載說明 (非官方)
## 介紹

CBETA 電子佛典閱讀器 2 (非官方)，簡寫 [cbetar2]( https://github.com/MrMYHuang/cbetar2)，預設使用 CBETA API 連線存取電子佛經，可利用加至書籤作離線瀏覽。

cbetar2 是一款 PWA 程式，類似於網頁，可在不同平台運行，如 iOS, Android, Windows, macOS, Linux。從 PWA 7.0.0 版開始，首度支援使用離線經文 - CBETA Bookcase 資料庫存取電子佛經，達到完全離線瀏覽體驗。雖然部分功能仍須連網，如全文搜索。

由於 Android 平台的檔案大小限制，cbetar2 PWA 無法載入 CBETA 官方 Bookcase 檔。因此以下提供刪除 cbetar2 未使用檔案後的非官方精簡版 Bookcase 以利匯入。

## 下載/匯入非官方精簡離線經文檔

1. [點此下載 bookcase_min_v070_20220321.zip](https://github.com/MrMYHuang/cbetar2-bookcase/raw/main/bookcase_min_v070_20220321.zip)
2. 開啟 cbetar2、切至設定頁。
3. 在"離線經文 DB 下載"一項，按匯入即可。過程僅一開始須連線下載約 1 MB 相關檔案。

## 已測試環境
    * iPad iOS 14.5 (模擬器): 可匯入官方 Bookcase 包。
    * Android 9: 須匯入精簡經文檔。
    * macOS 12 + Chrome: 可匯入官方 Bookcase 包。

## 自行製作 Bookcase for cbetar2
1. [下載官方 Bookcase zip](http://www.cbeta.org/download/cbreader.htm#data)
2. 解壓縮後，至此資料夾 Bookcase/CBETA。
3. 保留以下檔案或資料夾，其餘可刪除：
    * rj-gif
    * sd-gif
    * XML
    * bulei_nav.xhtml
    * advance_nav.xhtml
    * catalog.txt
    * spine.txt
    * figures
4. 將 Bookcase 資料夾壓縮，壓縮檔名無限制。
5. 完成。

## 第三方軟體版權聲明

1. <a href="http://www.cbeta.org/copyright.php" target="_new">CBETA 版權宣告</a>
