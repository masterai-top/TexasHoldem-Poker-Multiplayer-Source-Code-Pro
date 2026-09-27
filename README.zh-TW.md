[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

# 德州撲克俱樂部、私人局與好友局原始碼

[![C++](https://img.shields.io/badge/server-C%2B%2B-00599C)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Unity](https://img.shields.io/badge/client-Unity-222)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Stars](https://img.shields.io/github/stars/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro?style=social)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/stargazers)

本倉庫展示多人即時德州撲克俱樂部系統的公開技術快照。產品截圖包含建立俱樂部、加入聯盟、好友局、俱樂部幣、牌桌、MTT 賽事及門票報名；原始碼可核驗 Unity 工程結構、C++/Tars 登入服務、遊戲流程、計時、自動下注/棄牌、房間訊息、保險、機器人與資料庫入口。

## 產品功能

俱樂部建立與加入審核、聯盟關係、好友局/朋友局/私人桌、俱樂部幣、牌桌對局、個人中心、MTT 報名與賽事展示。產品資料亦提到經典德州、AOF、短牌、奧馬哈、大菠蘿與 SNG；規則、客戶端完整度及後台交付範圍須以授權清單核驗。

## 玩法與使用者流程

玩家建立或申請加入俱樂部，經審核後進入；可加入聯盟或建立邀請制好友局/朋友局，選擇房間後進入牌桌。賽事玩家從 MTT 頁面查看條件並以門票報名。房主權限、積分結算、保險及獎勵規則依部署設定。

## 可驗證的技術結構

`ProjectSettings/`、`Packages/`、`Scenes/` 與 `src/` 顯示 Unity 工程素材；`LoginProto.tars`、`LoginServantImp.cpp` 為登入協定與服務；`gameroot.cpp`、`Processor.cpp`、自動下注/棄牌、計時、入座及房間訊息檔案提供服務端流程入口；`insure.h`、機器人檔案及 `DBOperator.cpp` 對應保險、機器人與資料庫相關程式。

## 產品截圖

### 创建俱乐部

![產品截圖 - 创建俱乐部](./Screenshots/%E5%88%9B%E5%BB%BA%E4%BF%B1%E4%B9%90%E9%83%A8.jpg)

### 好友局

![產品截圖 - 好友局](./Screenshots/%E5%A5%BD%E5%8F%8B%E5%B1%80.jpg)

### 申请加入俱乐部

![產品截圖 - 申请加入俱乐部](./Screenshots/%E7%94%B3%E8%AF%B7%E5%8A%A0%E5%85%A5%E4%BF%B1%E4%B9%90%E9%83%A8.jpg)

### 加入联盟

![產品截圖 - 加入联盟](./Screenshots/%E5%8A%A0%E5%85%A5%E8%81%94%E7%9B%9F.jpg)

### 俱乐部币

![產品截圖 - 俱乐部币](./Screenshots/%E4%BF%B1%E4%B9%90%E9%83%A8%E5%B8%81.jpg)

### 打牌房间

![產品截圖 - 打牌房间](./Screenshots/%E6%89%93%E7%89%8C%E6%88%BF%E9%97%B4.jpg)

### MTT 赛事

![產品截圖 - MTT 赛事](./Screenshots/MTT%E8%B5%9B%E4%BA%8B.jpg)

### MTT 门票报名

![產品截圖 - MTT 门票报名](./Screenshots/MTT-%E6%8A%A5%E5%90%8D%EF%BC%88%E9%97%A8%E7%A5%A8%EF%BC%89.jpg)

### 个人中心

![產品截圖 - 个人中心](./Screenshots/%E4%B8%AA%E4%BA%BA%E4%B8%AD%E5%BF%83.jpg)

## 公開範圍與授權

公開倉庫可證明上述檔案與截圖存在，但不能證明「無 bug」「可直接上線」「完整後台」或特定併發量。商業使用受 LICENSE 的單獨商業授權條款約束。WPK 為第三方品牌，本項目僅供同類俱樂部/私人局產品技術評估，與 WPK 無官方關係。

## Documentation

- [德州撲克俱樂部原始碼](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-tw/poker-club-source-code.html)
- [私人局與好友局](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-tw/private-poker-friend-game.html)
- [多人遊戲架構](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-tw/multiplayer-poker-source-code.html)
- [俱樂部與賽事流程](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-tw/club-tournament-flow.html)

## Contact

Telegram: @xuzongbin001 · Email: masterai918@gmail.com
