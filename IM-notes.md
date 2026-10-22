# I–M 設計說明

產出時間：2026-10-22（約堡時間 UTC+2）。只放在 /workspace/hua-guide-design/，沒有改正式檔，沒有 push。

## 共通規格
- 字型：內文全部用系統字型（PingFang TC、Microsoft JhengHei、Noto Sans CJK TC），不另外下載。
- 只有 L 加一個標題用的子集字型：fonts-l-serif-subset.woff2，9,000 bytes（實測）。
- 配圖：6 張新圖，都是 AI 生成（GenerateImage），轉成 WebP，每張都在 80KB 以內（實測）：
  - n-jipai.webp：50.6KB
  - n-dumplings.webp：29.4KB
  - n-joburg.webp：77.7KB
  - n-grocery.webp：62.8KB
  - n-clinic.webp：18.6KB
  - n-port.webp：37.6KB
- 沒有用到舊的 a-editorial、b-city、c-market 圖。
- 圖示：Lucide，ISC 授權。
- 假資料都標「範例」。
- 產生腳本：gen4.py。

## 版型邏輯參考來源
只借版型邏輯，沒有用任何品牌的名稱、Logo 或配色。
- I：超商會員 App 的首頁功能入口格，加上優惠置頂。
  - https://www.bnext.com.tw/article/57601/open-point-app-2.0
  - https://play.google.com/store/apps/details?id=tw.net.pic.m.openpoint
- J：外送 App 的分類捷徑、篩選標籤、大張店家卡片。
  - https://www.bnext.com.tw/article/59941/uber-eats-taiwan-delivery-services-new-strategy
  - https://medium.com/@kiranriazart/redesigning-foodpanda-670cee3c5ece
- K：社區管理 App 的「首頁集中公告與功能入口」、公告分類、置頂。
  - https://smarthouse.topmso.com.tw/
  - https://www.smartdaily.com.tw/web/post/
- L：美食與生活媒體的頭條、專欄、熱門排行榜。
  - https://www.hk01.com/旅遊/366645/
- M：訂位平台的「先選條件再找店」篩選表單，以及結果卡片上的行動按鈕。
  - https://www.hk01.com/旅遊/366645/
  - https://task.com.tw/blog/table-booking-system-2026/zh-CN
