[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

[![C++](https://img.shields.io/badge/Server-C%2B%2B-00599C?logo=cplusplus)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Unity](https://img.shields.io/badge/Client-Unity-111?logo=unity)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Tars](https://img.shields.io/badge/RPC-Tars-2368C4)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Stars](https://img.shields.io/github/stars/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro?style=social)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/stargazers)

# 德州扑克俱乐部、私人局与好友局源码

> 面向**德州扑克俱乐部、德州私人局、德州好友局/朋友局**的多人实时项目公开技术快照。仓库同时包含 Unity 工程素材、C++/Tars 服务端入口和真实产品截图，适合做功能梳理、架构评估与合规二次开发。

<table><tr><td width="50%" align="center"><img src="./Screenshots/%E5%88%9B%E5%BB%BA%E4%BF%B1%E4%B9%90%E9%83%A8.jpg" width="300" alt="德州扑克俱乐部源码 - 创建俱乐部"><br><strong>创建俱乐部</strong><br><sub>建立俱乐部并进入成员运营流程</sub></td><td width="50%" align="center"><img src="./Screenshots/%E5%A5%BD%E5%8F%8B%E5%B1%80.jpg" width="300" alt="德州好友局源码 - 好友局大厅"><br><strong>好友局 / 朋友局</strong><br><sub>面向熟人邀请与私人牌桌场景</sub></td></tr></table>

## 这是什么产品

这是一套围绕“俱乐部关系 + 邀请制牌桌 + 多人实时对局 + 锦标赛”组织的德州扑克产品资料与源码快照。普通玩家可以申请加入俱乐部、进入好友局或赛事；俱乐部管理者可以处理加入流程、联盟关系和俱乐部币等业务。截图展示产品界面，源码目录用于核验公开技术范围。

## 产品功能矩阵

| 场景 | 玩家可以做什么 | 对应产品证据 |
|---|---|---|
| **德州俱乐部** | 创建俱乐部、申请加入、进入成员体系 | `创建俱乐部.jpg`、`申请加入俱乐部.jpg` |
| **联盟体系** | 俱乐部加入联盟，形成多俱乐部关系 | `加入联盟.jpg` |
| **私人局 / 好友局 / 朋友局** | 进入邀请制房间，与熟人进行牌桌对局 | `好友局.jpg`、`打牌房间.jpg` |
| **俱乐部币** | 查看俱乐部内部积分/币相关页面 | `俱乐部币.jpg` |
| **赛事系统** | 查看 MTT 赛事、使用门票报名 | `MTT赛事.jpg`、`MTT-报名（门票）.jpg` |
| **玩家中心** | 查看账号与个人资料入口 | `个人中心.jpg` |

产品资料还提到经典德州、AOF、短牌、奥马哈、大菠萝和 SNG。具体规则、结算方式及交付范围应以配置和授权清单为准。

## 从俱乐部到牌桌的用户流程

1. **建立关系**：玩家创建俱乐部，或提交加入申请。
2. **进入社交场景**：俱乐部可以加入联盟；玩家进入俱乐部、好友局或朋友局。
3. **选择玩法**：进入私人桌、常规桌或 MTT/SNG 赛事入口。
4. **实时对局**：完成入座、计时、下注/弃牌、房间消息与牌局流程。
5. **结果与运营**：展示战绩、赛事结果、俱乐部币或个人信息；具体结算由实际部署配置决定。

## 真实产品界面

<table><tr><td width="50%" align="center"><img src="./Screenshots/%E7%94%B3%E8%AF%B7%E5%8A%A0%E5%85%A5%E4%BF%B1%E4%B9%90%E9%83%A8.jpg" width="300" alt="德州扑克俱乐部加入申请"><br><strong>加入俱乐部</strong></td><td width="50%" align="center"><img src="./Screenshots/%E5%8A%A0%E5%85%A5%E8%81%94%E7%9B%9F.jpg" width="300" alt="德州扑克俱乐部联盟"><br><strong>加入联盟</strong></td></tr><tr><td width="50%" align="center"><img src="./Screenshots/%E6%89%93%E7%89%8C%E6%88%BF%E9%97%B4.jpg" width="300" alt="德州私人局牌桌"><br><strong>实时牌桌</strong></td><td width="50%" align="center"><img src="./Screenshots/%E4%BF%B1%E4%B9%90%E9%83%A8%E5%B8%81.jpg" width="300" alt="德州俱乐部币"><br><strong>俱乐部币</strong></td></tr><tr><td width="50%" align="center"><img src="./Screenshots/MTT%E8%B5%9B%E4%BA%8B.jpg" width="300" alt="德州扑克 MTT 赛事"><br><strong>MTT 赛事</strong></td><td width="50%" align="center"><img src="./Screenshots/MTT-%E6%8A%A5%E5%90%8D%EF%BC%88%E9%97%A8%E7%A5%A8%EF%BC%89.jpg" width="300" alt="德州扑克 MTT 门票报名"><br><strong>MTT 门票报名</strong></td></tr></table>

## 可核验的技术架构

| 层级 | 仓库中的真实文件/目录 | 用途 |
|---|---|---|
| Unity 客户端素材 | `ProjectSettings/`、`Packages/`、`Scenes/`、`src/` | Unity 工程配置、场景及协议素材 |
| 登录服务 | `LoginProto.tars`、`LoginServant.tars`、`LoginServantImp.cpp` | 登录协议、请求处理与用户状态入口 |
| 游戏核心 | `gameroot.cpp`、`Processor.cpp` | 游戏根对象与主要业务处理流程 |
| 牌桌动作 | `autobet.cpp`、`autofold.cpp`、`sitdown.cpp` | 自动下注、自动弃牌和入座流程 |
| 时间与消息 | `begintimer.cpp`、`endtimer.cpp`、`sendroommessage.cpp` | 计时与房间消息入口 |
| 扩展模块 | `insure.h`、`robotaction.cpp`、`robotwinrate.cpp` | 保险及机器人相关逻辑 |
| 数据访问 | `DBOperator.cpp`、`DBOperator.h` | 数据库操作入口 |

## 专题文档

- [德州扑克俱乐部源码：产品与技术全览](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-cn/poker-club-source-code.html)
- [德州私人局、好友局与朋友局流程](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-cn/private-poker-friend-game.html)
- [多人实时德州扑克 Unity + C++ 架构](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-cn/multiplayer-poker-source-code.html)
- [德州俱乐部与 MTT 赛事流程](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/zh-cn/club-tournament-flow.html)

## 公开范围、授权与品牌说明

公开仓库可证明上述文件和截图存在，但不能单凭 README 证明系统无缺陷、完整后台已经公开、可以直接上线或达到特定并发量。商业使用受 [LICENSE](./LICENSE) 中单独商业授权条款约束。WPK 是第三方品牌，本项目仅作为同类德州扑克俱乐部与私人局产品的技术评估参考，与 WPK 无官方隶属或授权关系。

## 联系

Telegram：@xuzongbin001 · Email：masterai918@gmail.com
