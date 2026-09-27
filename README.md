[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

# 德州扑克俱乐部、私人局与好友局源码

[![C++](https://img.shields.io/badge/server-C%2B%2B-00599C)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Unity](https://img.shields.io/badge/client-Unity-222)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Stars](https://img.shields.io/github/stars/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro?style=social)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/stargazers)

本仓库用于展示多人实时德州扑克俱乐部系统的公开技术快照。产品截图覆盖创建俱乐部、加入联盟、好友局、俱乐部币、牌桌、MTT 赛事和门票报名；源码可核验 Unity 工程结构、C++/Tars 登录服务、游戏流程、计时、自动下注/弃牌、房间消息、保险、机器人与数据库入口。

## 产品功能

俱乐部创建与加入审核、联盟关系、好友局/朋友局/私人桌、俱乐部币、牌桌对局、个人中心、MTT 报名与赛事展示。产品资料也提到经典德州、AOF、短牌、奥马哈、大菠萝与 SNG；具体规则、客户端完整度和后台交付范围必须以授权清单核验。

## 玩法与用户流程

玩家创建或申请加入俱乐部，经审核进入俱乐部；可加入联盟或创建仅限邀请的好友局/朋友局，选择房间后进入牌桌。赛事玩家通过 MTT 页面查看条件并使用门票报名。房主权限、积分结算、保险和奖励规则应由实际部署配置决定。

## 可验证的技术结构

`ProjectSettings/`、`Packages/`、`Scenes/` 与 `src/` 表明存在 Unity 工程素材；`LoginProto.tars`、`LoginServantImp.cpp` 负责登录协议与服务；`gameroot.cpp`、`Processor.cpp`、`autobet.cpp`、`autofold.cpp`、`begintimer.cpp`、`endtimer.cpp`、`sitdown.cpp` 和房间消息文件提供服务器流程入口；`insure.h`、机器人文件和 `DBOperator.cpp` 分别对应保险、机器人及数据库相关代码。

## 产品截图

### 创建俱乐部

![产品截图 - 创建俱乐部](./Screenshots/%E5%88%9B%E5%BB%BA%E4%BF%B1%E4%B9%90%E9%83%A8.jpg)

### 好友局

![产品截图 - 好友局](./Screenshots/%E5%A5%BD%E5%8F%8B%E5%B1%80.jpg)

### 申请加入俱乐部

![产品截图 - 申请加入俱乐部](./Screenshots/%E7%94%B3%E8%AF%B7%E5%8A%A0%E5%85%A5%E4%BF%B1%E4%B9%90%E9%83%A8.jpg)

### 加入联盟

![产品截图 - 加入联盟](./Screenshots/%E5%8A%A0%E5%85%A5%E8%81%94%E7%9B%9F.jpg)

### 俱乐部币

![产品截图 - 俱乐部币](./Screenshots/%E4%BF%B1%E4%B9%90%E9%83%A8%E5%B8%81.jpg)

### 打牌房间

![产品截图 - 打牌房间](./Screenshots/%E6%89%93%E7%89%8C%E6%88%BF%E9%97%B4.jpg)

### MTT 赛事

![产品截图 - MTT 赛事](./Screenshots/MTT%E8%B5%9B%E4%BA%8B.jpg)

### MTT 门票报名

![产品截图 - MTT 门票报名](./Screenshots/MTT-%E6%8A%A5%E5%90%8D%EF%BC%88%E9%97%A8%E7%A5%A8%EF%BC%89.jpg)

### 个人中心

![产品截图 - 个人中心](./Screenshots/%E4%B8%AA%E4%BA%BA%E4%B8%AD%E5%BF%83.jpg)

## 公开范围与授权

公开仓库可证明上述文件与截图存在，但不能据此证明“无 bug”“可直接上线”“完整后台”或具体并发量。商业使用受仓库 LICENSE 的单独商业授权条款约束。WPK 是第三方品牌，本项目仅作为同类俱乐部/私人局产品的技术评估参考，与 WPK 无官方隶属或授权关系。

## Documentation

- [德州扑克俱乐部源码](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-cn/poker-club-source-code.html)
- [德州私人局与好友局](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-cn/private-poker-friend-game.html)
- [多人实时技术架构](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-cn/multiplayer-poker-source-code.html)
- [俱乐部与赛事流程](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-cn/club-tournament-flow.html)

## Contact

Telegram: @xuzongbin001 · Email: masterai918@gmail.com
