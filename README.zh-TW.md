[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

[![C++](https://img.shields.io/badge/Server-C%2B%2B-00599C?logo=cplusplus)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Unity](https://img.shields.io/badge/Client-Unity-111?logo=unity)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Tars](https://img.shields.io/badge/RPC-Tars-2368C4)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Stars](https://img.shields.io/github/stars/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro?style=social)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/stargazers)

# 德州撲克俱樂部、私人局與好友局原始碼

> 面向**德州撲克俱樂部、德州私人局、德州好友局/朋友局**的多人即時專案公開技術快照。倉庫包含 Unity 工程素材、C++/Tars 服務端入口及真實產品截圖，適合功能梳理、架構評估與合規二次開發。

<table><tr><td width="50%" align="center"><img src="./Screenshots/%E5%88%9B%E5%BB%BA%E4%BF%B1%E4%B9%90%E9%83%A8.jpg" width="300" alt="德州撲克俱樂部原始碼 - 建立俱樂部"><br><strong>建立俱樂部</strong><br><sub>建立俱樂部並進入成員營運流程</sub></td><td width="50%" align="center"><img src="./Screenshots/%E5%A5%BD%E5%8F%8B%E5%B1%80.jpg" width="300" alt="德州好友局原始碼 - 好友局大廳"><br><strong>好友局 / 朋友局</strong><br><sub>面向熟人邀請與私人牌桌場景</sub></td></tr></table>

## 產品定位

這是一套以「俱樂部關係、邀請制牌桌、多人即時對局、錦標賽」為核心的德州撲克產品資料與原始碼快照。玩家可申請加入俱樂部、進入好友局或賽事；管理者可處理加入流程、聯盟關係及俱樂部幣。截圖展示產品介面，原始碼目錄用於核驗公開技術範圍。

## 功能矩陣

| 場景 | 使用者流程 | 產品證據 |
|---|---|---|
| **德州俱樂部** | 建立俱樂部、申請加入、進入成員體系 | `创建俱乐部.jpg`、`申请加入俱乐部.jpg` |
| **聯盟體系** | 俱樂部加入聯盟 | `加入联盟.jpg` |
| **私人局 / 好友局 / 朋友局** | 進入邀請制房間及熟人牌桌 | `好友局.jpg`、`打牌房间.jpg` |
| **俱樂部幣** | 查看俱樂部內部積分/幣頁面 | `俱乐部币.jpg` |
| **賽事系統** | 查看 MTT、使用門票報名 | `MTT赛事.jpg`、`MTT-报名（门票）.jpg` |
| **玩家中心** | 查看帳號與個人資料入口 | `个人中心.jpg` |

產品資料亦提到經典德州、AOF、短牌、奧馬哈、大菠蘿及 SNG；實際規則、結算與交付範圍以設定及授權清單為準。

## 使用者流程

1. 建立俱樂部或提交加入申請。
2. 加入聯盟，或進入好友局/朋友局。
3. 選擇私人桌、常規桌或 MTT/SNG。
4. 完成入座、計時、下注/棄牌及房間訊息流程。
5. 查看戰績、賽事結果、俱樂部幣或個人資料。

## 真實產品介面

<table><tr><td width="50%" align="center"><img src="./Screenshots/%E7%94%B3%E8%AF%B7%E5%8A%A0%E5%85%A5%E4%BF%B1%E4%B9%90%E9%83%A8.jpg" width="300" alt="德州撲克俱樂部加入申請"><br><strong>加入俱樂部</strong></td><td width="50%" align="center"><img src="./Screenshots/%E5%8A%A0%E5%85%A5%E8%81%94%E7%9B%9F.jpg" width="300" alt="德州撲克俱樂部聯盟"><br><strong>加入聯盟</strong></td></tr><tr><td width="50%" align="center"><img src="./Screenshots/%E6%89%93%E7%89%8C%E6%88%BF%E9%97%B4.jpg" width="300" alt="德州私人局牌桌"><br><strong>即時牌桌</strong></td><td width="50%" align="center"><img src="./Screenshots/%E4%BF%B1%E4%B9%90%E9%83%A8%E5%B8%81.jpg" width="300" alt="德州俱樂部幣"><br><strong>俱樂部幣</strong></td></tr><tr><td width="50%" align="center"><img src="./Screenshots/MTT%E8%B5%9B%E4%BA%8B.jpg" width="300" alt="德州撲克 MTT 賽事"><br><strong>MTT 賽事</strong></td><td width="50%" align="center"><img src="./Screenshots/MTT-%E6%8A%A5%E5%90%8D%EF%BC%88%E9%97%A8%E7%A5%A8%EF%BC%89.jpg" width="300" alt="德州撲克 MTT 門票報名"><br><strong>門票報名</strong></td></tr></table>

## 可核驗技術架構

| 層級 | 檔案/目錄 | 用途 |
|---|---|---|
| Unity | `ProjectSettings/`、`Packages/`、`Scenes/`、`src/` | 工程設定、場景與協定素材 |
| 登入 | `LoginProto.tars`、`LoginServantImp.cpp` | 登入協定與服務 |
| 遊戲核心 | `gameroot.cpp`、`Processor.cpp` | 遊戲及業務處理 |
| 牌桌流程 | `autobet.cpp`、`autofold.cpp`、`sitdown.cpp` | 自動操作與入座 |
| 訊息與資料 | `sendroommessage.cpp`、`DBOperator.cpp` | 房間訊息與資料庫入口 |

## 專題文件

- [德州撲克俱樂部原始碼](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-tw/poker-club-source-code.html)
- [私人局、好友局與朋友局](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-tw/private-poker-friend-game.html)
- [多人即時 Unity + C++ 架構](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-tw/multiplayer-poker-source-code.html)
- [俱樂部與 MTT 賽事流程](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-tw/club-tournament-flow.html)

## 範圍、授權與品牌

公開倉庫可證明所列檔案及截圖存在，但不能證明無缺陷、完整後台已公開、可直接上線或達到特定併發量。商業使用受 LICENSE 的單獨商業授權約束。WPK 是第三方品牌，本專案僅供同類產品技術評估，與 WPK 無官方關係。

Telegram：@xuzongbin001 · Email：masterai918@gmail.com
