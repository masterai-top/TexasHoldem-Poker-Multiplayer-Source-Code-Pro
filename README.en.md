[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

# Texas Holdem Poker Club, Private Table and Friend Game Source Code

[![C++](https://img.shields.io/badge/server-C%2B%2B-00599C)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Unity](https://img.shields.io/badge/client-Unity-222)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro) [![Stars](https://img.shields.io/github/stars/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro?style=social)](https://github.com/masterai-top/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/stargazers)

This repository presents a public technical snapshot of a real-time multiplayer Texas Holdem club system. Product screenshots cover club creation, union membership, friend games, club credits, table play, MTT events and ticket registration. Verifiable code includes Unity project structure, C++/Tars login services, game processing, timers, automatic actions, room messaging, insurance, bots and database entry points.

## Product functions

Club creation and approval, unions, invite-only friend/private tables, club credits, table play, profile, MTT registration and event presentation. Product materials also mention Classic Holdem, AOF, Short Deck, Omaha, Pineapple and SNG. Exact rules, client completeness and admin delivery scope require separate verification.

## Games and player flow

A player creates or applies to join a club, passes approval, and can join a union or create an invite-only friend game. Tournament players review MTT conditions and register with a ticket. Host permissions, point settlement, insurance and rewards depend on deployment configuration.

## Verifiable technical structure

`ProjectSettings/`, `Packages/`, `Scenes/` and `src/` establish Unity project material. `LoginProto.tars` and `LoginServantImp.cpp` cover login contracts and service code. `gameroot.cpp`, `Processor.cpp`, auto-action, timer, seating and room-message files provide server-flow entry points. `insure.h`, bot files and `DBOperator.cpp` cover insurance, robot logic and database access.

## Product screenshots

### 创建俱乐部

![Product screenshot - 创建俱乐部](./Screenshots/%E5%88%9B%E5%BB%BA%E4%BF%B1%E4%B9%90%E9%83%A8.jpg)

### 好友局

![Product screenshot - 好友局](./Screenshots/%E5%A5%BD%E5%8F%8B%E5%B1%80.jpg)

### 申请加入俱乐部

![Product screenshot - 申请加入俱乐部](./Screenshots/%E7%94%B3%E8%AF%B7%E5%8A%A0%E5%85%A5%E4%BF%B1%E4%B9%90%E9%83%A8.jpg)

### 加入联盟

![Product screenshot - 加入联盟](./Screenshots/%E5%8A%A0%E5%85%A5%E8%81%94%E7%9B%9F.jpg)

### 俱乐部币

![Product screenshot - 俱乐部币](./Screenshots/%E4%BF%B1%E4%B9%90%E9%83%A8%E5%B8%81.jpg)

### 打牌房间

![Product screenshot - 打牌房间](./Screenshots/%E6%89%93%E7%89%8C%E6%88%BF%E9%97%B4.jpg)

### MTT 赛事

![Product screenshot - MTT 赛事](./Screenshots/MTT%E8%B5%9B%E4%BA%8B.jpg)

### MTT 门票报名

![Product screenshot - MTT 门票报名](./Screenshots/MTT-%E6%8A%A5%E5%90%8D%EF%BC%88%E9%97%A8%E7%A5%A8%EF%BC%89.jpg)

### 个人中心

![Product screenshot - 个人中心](./Screenshots/%E4%B8%AA%E4%BA%BA%E4%B8%AD%E5%BF%83.jpg)

## Public scope and licensing

The public repository establishes that the listed files and screenshots exist. It does not prove a bug-free system, immediate production readiness, a complete operations console or a specific concurrency level. Commercial use is subject to the separate commercial-license requirement in LICENSE. WPK is a third-party brand; this project is only a technical reference for a similar product category and has no official affiliation with WPK.

## Documentation

- [Poker club source code](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/en/poker-club-source-code.html)
- [Private table and friend game](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/en/private-table-friend-game.html)
- [Multiplayer architecture](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/en/multiplayer-poker-architecture.html)
- [Tournament and club flow](https://masterai-top.github.io/TexasHoldem-Poker-Multiplayer-Source-Code-Pro/en/multiplayer-poker-architecture.html)

## Contact

Telegram: @xuzongbin001 · Email: masterai918@gmail.com
