# Smart OPCDA 讀取溫濕度

Smart 智慧控制平臺，實現集中監控、資訊共用、智慧控制，與 ERP 企業經營管理系統協調互動。社區版僅供個人且非商業使用。

> **加入 Facebook 社團**
>
> [https://www.facebook.com/groups/isoface/](https://www.facebook.com/groups/isoface/)
> 
> **點讚追蹤 Facebook 粉絲專頁**
> 
> [https://www.facebook.com/AIOT.ERP](https://www.facebook.com/AIOT.ERP)

採用 OPC 通訊協議，讀取連線在 Arduino 上的 DHT22 溫濕度感測器數據。OPC 是標準的工業通訊界面，根據微軟的 OLE、COM、DCOM 標準制定，它解決的是工業裝置互通性的問題，讓裝置資料的存取不再受限於硬體製造商。OPC 依據用途可分成 OPC 服務端（Server）與 OPC 使用者端（Client）兩部分。OPC Server 與 HMI/SCADA 軟體進行通訊，協議 OPC DA (資料存取)，通過 COM/DCOM 技術達成工業自動化數據獲取的架構，OPC Server 提供了許多的方法，Client 端通過這些方法可以獲取與 OPC Server 相連的硬體的數據資訊，而不需要去了解硬體的數據獲取方式。開發者可以通過編寫一套程式碼來實現操作不同的硬體。

範例中 Arduino 開發板與 Ethernet W5100 網路擴充套件板進行組裝。溫濕度感測器 DHT22，負極接入 Ethernet W5100 擴充套件板的 GND 針腳，正極接入擴充套件板的 5V 針腳，訊號線接入擴充套件板的 D8 針腳。

![](images/20220924170553.png)

通過範例學習，可以掌握 OPCDA 的配置方式，並結合 Arduino 開發板進行 DHT22 溫濕度感測器讀取的功能。

* **Smart 簡介**：https://isoface.net/isoface/production/software/smart/smart
* **Smart 下載**：[點選此處下載](https://github.com/isoface-iot/Smart/releases/latest)
* **Smart 使用手冊**：https://isoface.net/isoface/doc/smart/main/
* **範例手冊**：https://isoface.net/isoface/doc/smart/demo/opc-dht/
* **範例視訊**：https://isoface.net/isoface/component/k2/video-tutorial/smart/s-eq-dem-2017
* **Smart 快速上手**：https://isoface.net/isoface/study/quick-start/2022-05-28-03-08-29/smart
* **無需安裝，Smart線上試用**：https://isoface.net/isoface/support/trial/smart

## 注意事項：
1. Smart 智慧控制開發工具採用 Pascal 程序語言，開發物聯網相關運用。
2. Smart 因支援多種通訊協定與視訊處理程序，在 4K 顯示器的設計模式下，字體顯示偏小，如不適應請先調整 4K 顯示器解析度在 1920 * 1080 與 2560 * 1440 之間，不便之處敬請見諒。