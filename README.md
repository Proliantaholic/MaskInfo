## MaskInfo 健保特約機構口罩剩餘數量資訊 [![MaskInfo](https://img.shields.io/github/v/release/Proliantaholic/MaskInfo?include_prereleases&style=social)](https://github.com/Proliantaholic/MaskInfo/releases/download/v0.99/MaskInfo_0.99.rmskin) [![MaskInfo](https://img.shields.io/github/license/Proliantaholic/MaskInfo?color=blue)](https://raw.githubusercontent.com/Proliantaholic/MaskInfo/master/LICENSE)
## Rainmeter Skin / Rainmeter 面板
> 顯示健保特約機構口罩剩餘數量資訊

#### 本說明亦發表在: [proliantaholic.blogspot.com](https://proliantaholic.blogspot.com/2020/03/MaskInfo.html)

![proliantaholic.blogspot.com](https://tinyurl.com/rderwtg)
![proliantaholic.blogspot.com](https://tinyurl.com/r862qcd)

----
## 使用說明

### 安裝
* 下載 [![MaskInfo](https://img.shields.io/github/v/release/Proliantaholic/MaskInfo?label=MaskInfo.rmskin&logoColor=brightgreen&style=social)](https://github.com/Proliantaholic/MaskInfo/releases/download/v0.99/MaskInfo_0.99.rmskin) 然後使用 [Rainmeter](https://www.rainmeter.net) 的 SkinInstaller.exe 安裝

### 設定
指定醫事機構代碼(NhiCode):
* 在 Settings.txt 內設定. (在 MaskInfo\@RESOURCES\Settings 目錄內)
* 也可以在面板上按右鍵 -> 自訂面板動作 -> 手動設定醫事機構代碼及其他參數 (會打開 Settings.txt)
* 醫事機構代碼可參考: [健保特約機構口罩剩餘數量明細清單](https://data.nhi.gov.tw/Datasets/Download.ashx?rid=A21030000I-D50001-001&l=https://data.nhi.gov.tw/resource/mask/maskdata.csv) 醫事機構代碼欄位. 例如: 2101150012 (士林健康服務中心)

用滑鼠右鍵單擊不同區域可以變更設定: (輸入代碼後請按Enter確定變更)
* 代碼 XXXXXXXXXX: 設定要顯示口罩剩餘數量資訊的 醫事機構代碼
* 來源資料時間/每X分鐘更新文字: 設定 資料更新頻率 (分鐘)
* 常用機構1/常用機構2/常用機構3: 設定常用的 醫事機構代碼 (3組可供滑鼠左鍵雙擊切換使用)

### 使用
用滑鼠左鍵雙擊不同區域可以帶出不同資訊:
* 醫事機構名稱: 開啟該醫事機構在 [藥局口罩採購地圖 (江明宗先生製作)](https://kiang.github.io/pharmacies) 的網頁
* 醫事機構地址: 開啟該地址的GoogleGoogle Maps網頁
* 常用機構1/常用機構2/常用機構3: 切換 醫事機構代碼 為設定的常用代碼, 並更新面板資訊

將滑鼠指標移至不同區域可以顯示不同資訊:
* 常用機構文字: 顯示該醫事機構口罩剩餘數量資訊

### 教學影片
* [安裝Rainmeter及MaskInfo面板](https://i.imgur.com/m6dAxZ6.gifv)

----
## 資料來源與授權
* 資料來源: [衛生福利部中央健康保險署](https://data.gov.tw/license)

----
## Changelog
### Version 0.99 / 2020-11-24
* 修正 健保特約機構口罩剩餘數量明細清單連結為https

### Version 0.98 / 2020-05-15
* 調整 滑鼠指標移至常用機構文字上的顯示方式, 醫事機構名稱前面加上號碼
* 其他小調整

### Version 0.97 / 2020-05-02
* 新增 滑鼠指標移至常用機構文字上會顯示該醫事機構口罩剩餘數量資訊
* 調整 醫事機構代碼錯誤或資料來源有問題時的顯示與處理方式

### Version 0.96 / 2020-04-11
* 修正 醫事機構代碼錯誤或資料來源有問題時的顯示方式

### Version 0.95 / 2020-04-10
* 新增 MIT授權條款
* 新增 WebParser UserAgent設定
* 新增 根據**成人/兒童口罩剩餘數**狀況顯示**常用醫事機構**不同文字底色: 文字前半底色為成人口罩剩餘數狀況, 文字後半底色為兒童口罩剩餘數狀況
* 其他小調整

### Version 0.94 / 2020-03-24
* 新增 滑鼠右鍵單擊變更設定: 資料更新頻率 (分鐘)
* 調整 自訂面板動作 -> 資料更新頻率: 最短 每5分鐘 -> 每3分鐘
* 修正 刪除多餘的 @Include="#@#Settings\Settings.txt"

### Version 0.93 / 2020-03-20
* 新增 根據**成人口罩剩餘數**狀況顯示**常用醫事機構**不同文字底色

### Version 0.92 / 2020-03-18
* 新增 根據**口罩剩餘數**狀況顯示**成人/兒童**不同文字底色

### Version 0.91 / 2020-03-16
* 新增 根據醫事機構名稱開啟 藥局口罩採購地圖 (https://kiang.github.io/pharmacies 江明宗先生製作) 網頁

### Version 0.9 / 2020-03-15
* First release