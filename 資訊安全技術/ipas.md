
# VPN
```
虛擬私人網路（英語：Virtual Private Network，縮寫：VPN）是一種常用於連接中、大型企業或團體與團體間的私人網路的通訊方法。
它利用隧道協定（Tunneling Protocol）來達到保密、傳送端認證、訊息準確性等私人訊息安全效果，
這種技術可以用不安全的網路（例如：網際網路）來傳送可靠、安全的訊息。需要注意的是，加密訊息與否是可以控制的，
如果是沒有加密的虛擬私人網路訊息依然有被竊取的危險。
常用的虛擬私人網路協定有：
L2F
L2TP
PPTP
IPsec （如Cisco IPSec VPN）
SSL VPN
AnyConnect（Cisco SSL VPN）
```
# 存取控制
DAC 自由存取控制
```
自由存取控制（Discretionary Access Control, DAC)，以創建資訊元件的元件持有者授權為基礎，不需要經過管理者授權，
持有者授權可以決定使用者對於資訊元件的存取權限。
```
MAC 強制存取控制
```
強制存取控制（Mandatory Access Control, MAC)，以管理者授權為基礎，所有的資訊元件都需要經過管理者授權，才能被使用者所存取。
```
RBAC 角色存取控制
```
角色存取控制（Role-base Access Control），存取權限與使用者角色相依，資訊元件的存取被授權給角色，使用者需要先取得角色身份，
才能透過角色身份取得存取權限。
```
ABAC 屬性存取控制
```
屬性存取控制 (Attribute-based access control)，基於屬性的訪問控制，也稱為基於策略的訪問控制，定義了一種訪問控制範例，
通過將屬性組合在一起的策略將訪問權限授予用戶。
```
# ELK
由 3個不同的 open-source 軟體所構成的套件，分別包含 :  
  
E   Elasticsearch
```
是一個實時的分佈式搜索分析引擎,它被用作全文檢索、結構化搜索、分析以及這三個功能的組合。
```
L   Logstash
```
是一款輕量級的日誌搜集處理框架，可以方便的把分散的、多樣化的日誌搜集起來，並進行自定義的處理，然後傳輸到指定的位置。
```
K   Kibana
```
是一款開源的數據分析和可視化平台，能對 Elasticsearch 索引中的數據進行搜索，查看，交互操作。
```

# HONEYPOT 蜜罐
```
是一個電腦術語，專指用來偵測或抵禦未經授權操作或者是駭客攻擊的陷阱，因原理類似誘捕昆蟲的蜜罐因而得名。
蜜罐通常偽裝成看似有利用價值的網路、資料、電腦系統，並故意設定了bug，用來吸引駭客攻擊。
由於蜜罐事實上並未對網路提供任何有價值的服務，所以任何對蜜罐的嘗試都是可疑的。
蜜罐中還可能裝有監控軟體，用以監視駭客入侵後的舉動。

蜜罐在拖延駭客攻擊真正目標上也有一定作用。不過駭客可能發現一個電腦系統是蜜罐，進而提前退出。

而更常見的用法是用來吸引網路的電腦病毒入侵，從而獲得病毒樣本用於研究或破解的電腦，
防毒軟體公司會利用這些電腦來監視或獲得電腦網路中的病毒樣本。
```
# 3A
Authentication 驗證
```
是對用戶的身份進行驗證，判斷其是否為合法用戶。
```
Accounting 帳號管理
```
是記錄用戶使用網路服務的資源情況，這些信息將作為計費的依據。
```
Authorization 授權
```
是對通過認證的用戶，授權其可以使用哪些服務。
```

