## MaskInfo 健保特約機構口罩剩餘數量資訊
## Rainmeter Skin / Rainmeter 面板
> 顯示健保特約機構口罩剩餘數量資訊

#### 本說明亦發表在: [proliantaholic.blogspot.com](https://proliantaholic.blogspot.com/2020/03/MaskInfo.html)

![proliantaholic.blogspot.com](https://tinyurl.com/qr42v3y)

----
## 使用說明

### 安裝
* 下載[MaskInfo_x.x.rmskin](https://github.com/Proliantaholic/MaskInfo/raw/master/MaskInfo_0.91.rmskin), 使用 [Rainmeter](https://www.rainmeter.net) 的 SkinInstaller.exe 安裝.

### 設定
指定醫事機構代碼(NhiCode):
* 在 Settings.txt 內設定. (在 MaskInfo\@RESOURCES\Settings 目錄內)
* 也可以在面板上按右鍵 -> 自訂面板動作 -> 手動設定醫事機構代碼及其他參數 (會打開 Settings.txt)
* 醫事機構代碼可參考: [健保特約機構口罩剩餘數量明細清單](http://data.nhi.gov.tw/Datasets/Download.ashx?rid=A21030000I-D50001-001&l=https://data.nhi.gov.tw/resource/mask/maskdata.csv) 醫事機構代碼欄位. 例如: 2101150012 (士林健康服務中心)

用滑鼠右鍵單擊不同區域可以變更設定: (輸入代碼後請按Enter確定變更)
* 代碼 XXXXXXXXXX: 設定要顯示口罩剩餘數量資訊的 醫事機構代碼
* 常用機構1/常用機構2/常用機構3: 設定常用的 醫事機構代碼 (3組可供滑鼠左鍵雙擊切換使用)

### 使用
用滑鼠左鍵雙擊不同區域可以帶出不同資訊:
* 醫事機構名稱: 開啟該醫事機構在 [藥局口罩採購地圖 (江明宗先生製作)](https://kiang.github.io/pharmacies) 的網頁
* 醫事機構地址: 開啟該地址的GoogleGoogle Maps網頁
* 常用機構1/常用機構2/常用機構3: 切換 醫事機構代碼 為設定的常用代碼, 並更新面板資訊

### 教學影片
* [安裝Rainmeter及MaskInfo面板](https://i.imgur.com/m6dAxZ6.gifv)


----
## 資料來源與授權
* 資料來源: 衛生福利部中央健康保險署
* 授權方式: [依政府資料開放平臺使用規範](https://data.gov.tw/license/legacy)

----
## Changelog
### Version 0.91 / 2020-03-16
* 新增 根據醫事機構名稱開啟 藥局口罩採購地圖 (https://kiang.github.io/pharmacies 江明宗先生製作) 網頁

### Version 0.9 / 2020-03-15
* First release
