# 德州撲克多人對戰源碼 Pro | Texas Holdem Poker Multiplayer Source Code

[簡體中文](README.md) | [English](README.en.md) | [繁體中文](README.zh-TW.md)

本項目是一套面向商業化部署與二次開發的德州撲克多人對戰源碼，覆蓋即時對局、私人局、俱樂部、聯盟、代理體系、比賽玩法、保險、戰績、後台管理與高性能 C++ 服務端架構，適合德州源碼、德撲俱樂部、WPK 類產品、線上撲克平台與完整棋牌解決方案評估。

## 核心定位

- 德州撲克源碼 / Texas Holdem Poker Source Code
- 多人即時對戰 / Multiplayer Real-Time Poker
- 德州俱樂部、聯盟、私人局、朋友局
- 代理系統、後台管理、數據統計
- C++ 高性能遊戲服務端與 TARS/協議服務結構
- Unity 雙端客戶端、iOS/Android 產品交付方向
- 可用於商業評估、客製開發與私有化部署

## 功能清單

- 經典德州撲克、AOF、短牌、奧馬哈、大菠蘿等擴展玩法
- 私人局、朋友局、俱樂部、大聯盟、代理體系
- MTT 多桌錦標賽、SNG 坐滿即玩、排行榜與戰績統計
- 保險系統、語音視頻聊天、禮物系統、機器人陪玩
- 後台管理、會員管理、房間配置、營運數據與風控配置
- 高併發遊戲房間、登入服務、GM 服務、協議文件與結算邏輯

## 項目結構建議

```text
client/                 # Unity 客戶端或演示工程
server/                 # C++ 即時遊戲服務、登入服務、GM 服務
admin/                  # 營運後台、代理後台、配置管理
database/               # 數據庫結構與遷移說明
config.example/         # 脫敏配置示例
docs/                   # GitHub Pages 產品與技術文檔
scripts/                # 構建、部署與維護腳本
tests/                  # 規則、結算、接口與風控測試
.github/workflows/      # CI 與 GitHub Pages 工作流
```

## 適用場景

- 搭建德州撲克平台、德撲俱樂部、私人局與朋友局系統
- 評估線上撲克、俱樂部代理體系、比賽系統與完整解決方案
- 用於 Unity 客戶端、C++ 服務端、後台系統的二次開發
- 面向東南亞、歐美、南美等市場的撲克遊戲平台技術驗證

## 公開倉庫安全建議

公開倉庫適合展示產品結構、部分源碼、截圖與技術文檔。不要公開真實用戶數據、支付密鑰、後台帳號、生產數據庫、私有營運數據、風控參數、線上配置或未授權素材。

## 文檔

- [項目主頁](docs/index.html)
- [功能介紹](docs/features.html)
- [架構說明](docs/architecture.html)
- [部署指南](docs/deployment.html)
- [合規使用](docs/responsible-use.html)

## 聯繫方式

Telegram：`@xuzongbin001`  
Email：`masterai918@gmail.com`

## License

僅限技術評估、商務溝通與授權合作，具體以倉庫 License 文件為準。
