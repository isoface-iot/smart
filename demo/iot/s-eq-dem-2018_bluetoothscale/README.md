# Smart 藍芽電子秤

Smart 智慧控制平臺，實現集中監控、資訊共用、智慧控制，與 ERP 企業經營管理系統協調互動。社區版僅供個人且非商業使用。

> **加入 Facebook 社團**
>
> [https://www.facebook.com/groups/isoface/](https://www.facebook.com/groups/isoface/)
> 
> **點讚追蹤 Facebook 粉絲專頁**
> 
> [https://www.facebook.com/AIOT.ERP](https://www.facebook.com/AIOT.ERP)

範例採用藍芽通訊協議，讀取電子秤並控制電子秤的去皮清零操作。PC 端發送讀取指令，電子秤返回稱重重量的資訊；PC 端發送去皮與置零的指令，電子秤端執行相應的操作。在使用該功能前需要將裝置與電子秤進行藍芽配對連線。對應的 PIN 以及藍芽的 MAC 地址可以在電子秤的產品說明中檢視。

範例使用到的電子秤為耀華 XK3190-A12+E，該型號的電子秤可提供藍芽連線的支援。在使用範例前，請先確認計算機是否支援藍芽，是否已與電子秤進行藍芽配對連線，否則會導致範例執行失敗。

![](images/20220924171343.png)

* **Smart 簡介**：https://isoface.net/isoface/production/software/smart/smart
* **Smart 下載**：[點選此處下載](https://github.com/isoface-iot/Smart/releases/latest)
* **Smart 使用手冊**：https://isoface.net/isoface/doc/smart/main/
* **範例手冊**：https://isoface.net/isoface/doc/smart/demo/ble-scale/
* **範例視訊**：https://isoface.net/isoface/component/k2/video-tutorial/smart/s-eq-dem-2018
* **Smart 快速上手**：https://isoface.net/isoface/study/quick-start/2022-05-28-03-08-29/smart
* **無需安裝，Smart線上試用**：https://isoface.net/isoface/support/trial/smart

## 注意事項：
1. Smart 智慧控制開發工具採用 Pascal 程序語言，開發物聯網相關運用。
2. Smart 因支援多種通訊協定與視訊處理程序，在 4K 顯示器的設計模式下，字體顯示偏小，如不適應請先調整 4K 顯示器解析度在 1920 * 1080 與 2560 * 1440 之間，不便之處敬請見諒。