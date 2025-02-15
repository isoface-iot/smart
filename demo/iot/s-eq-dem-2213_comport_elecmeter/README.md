# Smart 通訊埠電錶數據採集


Smart 智慧控制平臺，實現集中監控、資訊共用、智慧控制，與 ERP 企業經營管理系統協調互動。社區版僅供個人且非商業使用。

> **加入 Facebook 社團**
>
> [https://www.facebook.com/groups/isoface/](https://www.facebook.com/groups/isoface/)
> 
> **點讚追蹤 Facebook 粉絲專頁**
> 
> [https://www.facebook.com/AIOT.ERP](https://www.facebook.com/AIOT.ERP)

採用通訊埠通訊協議，連線至電錶讀取電錶的讀數資訊。

電能表是用來測量電能的儀表，又稱電度表，火表，千瓦小時表，指測量各種電學量的儀表。

電能表在低電壓（不超過 500 伏）和小電流（幾十安）的情況下，可直接接入電路進行測量。一般的家用電路是以這種方式接入電能表進行電費計量的。在高電壓或大電流的情況下，電能表不能直接接入線路，需配合電壓互感器或電流互感器使用。工廠的電能表通常會使用這種方式進行測量。

目前市面上使用的絕大多數數字液晶顯示屏電能表均有 RS485 的通訊介面，除了用於連線電路的接線柱外，還包含了 RS485 介面的接線柱，用於與計算機進行連線。範例中使用的電能表通過 RS485 通訊介面與計算機連線，計算機通過通訊埠向該電能表發送讀取電能數據的Modbus指令，電能表對應返回數據，計算機進行解析后顯示讀取的結果數值。我們可以將讀取到的數值寫入至資料庫中實現能源分析的功能。

![](images/20220927160511.png)

* **Smart 簡介**：https://isoface.net/isoface/production/software/smart/smart
* **Smart 下載**：[點選此處下載](https://github.com/isoface-iot/Smart/releases/latest)
* **Smart 使用手冊**：https://isoface.net/isoface/doc/smart/main/
* **Smart 快速上手**：https://isoface.net/isoface/study/quick-start/2022-05-28-03-08-29/smart
* **無需安裝，Smart線上試用**：https://isoface.net/isoface/support/trial/smart

## 注意事項：
1. Smart 智慧控制開發工具採用 Pascal 程序語言，開發物聯網相關運用。
2. Smart 因支援多種通訊協定與視訊處理程序，在 4K 顯示器的設計模式下，字體顯示偏小，如不適應請先調整 4K 顯示器解析度在 1920 * 1080 與 2560 * 1440 之間，不便之處敬請見諒。