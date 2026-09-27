[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

[![C++](https://img.shields.io/badge/Server-C%2B%2B-00599C?logo=cplusplus)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Unity](https://img.shields.io/badge/Client-Unity-111?logo=unity)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Tars](https://img.shields.io/badge/RPC-Tars-2368C4)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Stars](https://img.shields.io/github/stars/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro?style=social)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/stargazers)

# Texas Holdem Poker Club, Private Table and Friend Game Source Code

> A public technical snapshot for a **multiplayer Texas Holdem poker club, invite-only private table and friend-game platform**. It combines Unity project material, C++/Tars server entry points and real product screenshots for architecture review and licensed development.

<table><tr><td width="50%" align="center"><img src="./Screenshots/%E5%88%9B%E5%BB%BA%E4%BF%B1%E4%B9%90%E9%83%A8.jpg" width="300" alt="Texas Holdem poker club source code - create club"><br><strong>Create a poker club</strong><br><sub>Start a club and member workflow</sub></td><td width="50%" align="center"><img src="./Screenshots/%E5%A5%BD%E5%8F%8B%E5%B1%80.jpg" width="300" alt="Private poker friend game source code"><br><strong>Private friend game</strong><br><sub>Invite-based tables for known players</sub></td></tr></table>

## Product overview

The product material is organized around club membership, invite-only rooms, real-time multiplayer tables and tournaments. Players can apply to a club, enter a friend game or register for an event. Club operators can manage applications, union relationships and club-credit views. Screenshots establish the interface material; repository files establish the visible technical scope.

## Feature matrix

| Area | Player or operator workflow | Evidence |
|---|---|---|
| **Poker club** | Create a club, apply to join, enter the member structure | Club and application screenshots |
| **Union** | Connect a club to a wider union | Union screenshot |
| **Private/friend game** | Join an invite-only room and enter the table | Friend-game and table screenshots |
| **Club credits** | View internal club-credit information | Club-credit screenshot |
| **Tournament** | Browse an MTT and register with a ticket | MTT and ticket screenshots |
| **Player profile** | Access player/account information | Profile screenshot |

Product material also references Classic Holdem, AOF, Short Deck, Omaha, Pineapple and SNG. Exact rules, settlement behavior and delivery scope depend on configuration and the licensed delivery inventory.

## Player journey

1. Create a club or submit a membership application.
2. Join a union or enter an invite-only friend/private game.
3. Select a private table, regular room or MTT/SNG event.
4. Complete seating, timers, betting/folding and room-message flow.
5. Review results, event status, club credits or profile information.

## Product interface gallery

<table><tr><td width="50%" align="center"><img src="./Screenshots/%E7%94%B3%E8%AF%B7%E5%8A%A0%E5%85%A5%E4%BF%B1%E4%B9%90%E9%83%A8.jpg" width="300" alt="Poker club membership application"><br><strong>Club application</strong></td><td width="50%" align="center"><img src="./Screenshots/%E5%8A%A0%E5%85%A5%E8%81%94%E7%9B%9F.jpg" width="300" alt="Poker club union"><br><strong>Club union</strong></td></tr><tr><td width="50%" align="center"><img src="./Screenshots/%E6%89%93%E7%89%8C%E6%88%BF%E9%97%B4.jpg" width="300" alt="Private Texas Holdem table"><br><strong>Real-time table</strong></td><td width="50%" align="center"><img src="./Screenshots/%E4%BF%B1%E4%B9%90%E9%83%A8%E5%B8%81.jpg" width="300" alt="Poker club credits"><br><strong>Club credits</strong></td></tr><tr><td width="50%" align="center"><img src="./Screenshots/MTT%E8%B5%9B%E4%BA%8B.jpg" width="300" alt="Texas Holdem MTT event"><br><strong>MTT event</strong></td><td width="50%" align="center"><img src="./Screenshots/MTT-%E6%8A%A5%E5%90%8D%EF%BC%88%E9%97%A8%E7%A5%A8%EF%BC%89.jpg" width="300" alt="MTT ticket registration"><br><strong>Ticket registration</strong></td></tr></table>

## Verifiable architecture

| Layer | Repository artifacts | Purpose |
|---|---|---|
| Unity material | `ProjectSettings/`, `Packages/`, `Scenes/`, `src/` | Project settings, scenes and protocol assets |
| Login | `LoginProto.tars`, `LoginServantImp.cpp` | Login contracts and service logic |
| Game processing | `gameroot.cpp`, `Processor.cpp` | Game root and business processing |
| Table actions | `autobet.cpp`, `autofold.cpp`, `sitdown.cpp` | Automatic actions and seating |
| Messaging/data | `sendroommessage.cpp`, `DBOperator.cpp` | Room messaging and database entry |

## Documentation

- [Poker club source code](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/en/poker-club-source-code.html)
- [Private table and friend game](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/en/private-table-friend-game.html)
- [Unity and C++ multiplayer architecture](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/en/multiplayer-poker-architecture.html)

## Scope, license and brand statement

The public repository verifies the listed files and screenshots. It does not establish a bug-free product, immediate production readiness, a complete public admin console or a specific concurrency level. Commercial use is subject to the separate commercial-license requirement in LICENSE. 
Telegram: @xuzongbin001 · Email: masterai918@gmail.com
