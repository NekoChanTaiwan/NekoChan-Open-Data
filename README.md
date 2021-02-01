# Goindex 自用

**fork from [yanzai/goindex](https://github.com/yanzai/goindex)**

### 預覽
![image1](https://i.imgur.com/0Jp32GQ.png)
![image2](https://i.imgur.com/FiS723T.png)
![image3](https://i.imgur.com/QG6O42u.png)

## 已知問題
- ~~有時會發生 POST 請求錯誤 狀態碼：500 （導致列表渲染不出來的主要原因）~~

## 1.9.0 更新內容
- 新增 進度條預覽圖 切換按鈕（預設關閉）
- 隱藏 !head.md, !readme.md 檔案（可搜尋到）
- 修改 項目排序

### 1.8.9 更新內容
- 新增 DPlayer 快捷鍵
    - 數字鍵（包括上排）：影片進度跳轉（1=10%, 2=20%...）,
    - M：靜音（解除靜音）,
    - Z：上一集,
    - X：下一集,
    - F：全螢幕（退出全螢幕）
- 當前路徑不會顯示檔案，只有資料夾
- 簡化 JS

### 1.8.8 更新內容
- 更新 MDUI 排版、CSS
- 移除 修改時間
- 移除 不必要的 JS 函式、HTML 元素
- 壓縮 JS Worker

### 1.8.7 更新內容
- DPlayer 進度條預覽圖 將只在 WIN、MAC 系統下開啟。（考慮到手機或平板用戶的網速）

### 1.8.5 更新內容
- 優化 DPlayer 進度條預覽圖

### 1.8.4 更新內容
- 新增 DPlayer 進度條預覽圖（感謝 Horis、mp0530 參與）

（由於是及時獲取畫面，並不像其他影音平台在上傳時就處裡好的。所以還有可優化的空間。）

### 1.8.2 更新內容
- 更換 背景圖片
- 以顏色區分 連載中、完結、R18 項目

### 1.8.1 更新內容
- 新增 返回頂部 按鈕
- 修正 檔案順序 不忽略資料夾的問題
- 升級 DPlayer 1.26.0

### 1.8.0 更新內容
- 關閉 搜尋欄提示內容

### 1.7.9 更新內容
- 新增 日文字體
- 簡化 JS、CSS
- 修改 每次讀取項目量 999 -> 100

### 1.7.8 更新內容
- 新增 搜尋欄
- 移除 網址時間戳
- 修復 列表有時為空的問題（狀態碼 500）

### 1.7.2 更新內容
- 在檔案圖標前方新增順序（不包括資料夾）

### 1.6.8 更新內容
- 網址後方新增時間戳，確保當前頁面為最新資料
- 簡化JS

### 1.6.3.1 更新內容
- 更新 背景圖片
- 新增 連結預覽圖片

### 1.6.1 更新內容
- 新增 Twitter 按鈕
- 新增 重新整理 按鈕

### 1.5.7 更新內容
- 新增 DPlayer 載入失敗或跳轉 發生載入失敗時，自動重新讀取並跳轉至 上一次的播放時間 或 正在跳轉時間 或 已跳轉的時間

### 1.5.1 更新內容
- 修復 DPlayer 有時無法正常載入 問題

### 1.4.7 更新內容
- 改寫了部分語法、以 ES6 語法壓縮檔案
- 新增 網站 icon
- 移除 Twitter 按鈕
- 移除 Donate 按鈕 
- 移除 notyf 通知
- 移除 自動切換下一集
- 更新 jQuery 3.5.1
- 更新 mdui 1.0.1
- 更新 markdown-it 12.0.4
- 更新 DPlayer 1.25.1
- 修復 DPlayer影片載入失敗 問題
- 修復 console 警告的錯誤

### 1.1.7 更新內容
- 新增 notyf 通知

### 1.0.7 更新內容
- 影片結束後自動切換下一集（如果有的話）
- 啟用 Dplayer 截圖功能

### 更新內容
- 新增 自訂背景
- 新增 支援繁體中文字體
- 新增 [Dplayer](https://github.com/MoePlayer/DPlayer) 播放器 [v1.25.1](https://github.com/MoePlayer/DPlayer/releases/tag/v1.25.1)
- 支援 各裝置的 播放器串流 [PotPlayer(Win)](https://potplayer.daum.net/?lang=zh_TW)、[IINA(Mac)](https://iina.io/)、[MX Player(Android)](https://play.google.com/store/apps/details?id=com.mxtech.videoplayer.ad)、[Infuse(iOS)](https://apps.apple.com/tw/app/infuse-6/id1136220934)

## 聯絡
Discord：NekoChan#2851
