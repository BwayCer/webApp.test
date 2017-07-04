革新網絡應用程式
=======


> 2017.07.04



## 頁籤


* [簡介](#簡介)
* [優點](#優點)
* [實作](#實作)
* [參考](#參考)



## 簡介


> 尋求 `progressive` 的翻譯。


革新網絡應用程式 Progressive Web Apps （PWA） 或許是網頁開發者的下一個春天！

在移動的年代， 手機應用程式大鳴大放，
但， 我們的使用習慣仍如同使用電腦一般， 「審慎」的選擇要載入安裝的應用程式。
在這方面， 網頁可說是用戶認識、瞭解並吸引用戶安裝， 一個如同門面的存在。
以往網頁與應用程式間除了效能外，
最大的差異莫過於許多只專屬於原生應用程式的功能無法使用（如： 推播、本地儲存空間 ...），
而現在透過新草案的發布及瀏覽器的更新這道隔閡漸漸在消失。



## 優點


網絡應用程式是我們熟悉的網頁體驗再加上：

  * 可靠的： 立即啟動且不會再見到[斷線恐龍](/appendix/bilingual.md#斷線恐龍)， 即使在網路無法連線的情況。
     ![斷線恐龍](/mmrepo/chrome_downasaur.png)
  * 快速的： 以接續平順的動畫來呈現畫面而非糟糕的捲動
    （[原文說明](https://developers.google.com/web/progressive-web-apps/#fast)
     應該是指緩載入等等的優化細節，似乎不是特別因為網絡應用程式的使用才能改善的）。
  * 迷人的 - 如同原生應用程式般的用戶體驗。


為何喜歡開發網絡應用程式：

  * 跨平台、簡易鏈結分享。
  * 強制要求安全的傳輸協定（HTTPs）。
  * 讓程式自動更新， 維持最新的狀態。
  * 可被搜尋（透過 `manifests` 和 `service worker`）。
  * 可添加啟動捷徑到主畫面。
  * 自動生成啟動畫面。
  * 減緩網路影響並也減少傳輸數據。
  * 發送推播， 增加用戶參與度。
  * 增加新增用戶數、提高網頁瀏覽數及黏著度。



## 實作


#### 文件


* [谷歌開發者文件](https://developers.google.com/web/)
* [摩斯拉開發者共筆文件](https://developer.mozilla.org/zh-TW/Apps/Progressive)
* [開發完成後的複檢清單](https://developers.google.com/web/progressive-web-apps/checklist)



#### 評分工具


燈塔 Lighthouse 是個自動化分析網絡應用程式優缺的開源工具。
可簡易得知目前程式的弱勢並生成評分報告， 一個方便開發者提升程式品質的實用工具。



## 參考

* [Progressive Web App 渐进式网页应用程序 - 知乎专栏](https://zhuanlan.zhihu.com/p/24436020)
* [Progressive Web Apps | Web | Google Developers](https://developers.google.com/web/progressive-web-apps/)
* [你的首個 Progressive Web App | Web | Google Developers](https://developers.google.com/web/fundamentals/getting-started/codelabs/your-first-pwapp/)

