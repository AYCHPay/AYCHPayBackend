<p align="center">
  <img src="https://i.imgur.com/4lMw23m.png" width="500">
</p>
<br>

[![Throughput Graph](https://graphs.waffle.io/GenesisCommunity/go-genesis/throughput.svg)](https://waffle.io/GenesisCommunity/go-genesis/metrics/throughput)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Go Report Card](https://goreportcard.com/badge/github.com/GenesisCommunity/go-genesis)](https://goreportcard.com/report/github.com/GenesisCommunity/go-genesis)
[![Build Status](https://travis-ci.org/GenesisCommunity/go-genesis.svg?branch=master)](https://travis-ci.org/GenesisCommunity/go-genesis)
[![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](http://GenesisCommunity.readthedocs.io/en/latest/)
[![](https://tokei.rs/b1/github/GenesisCommunity/go-genesis)](https://github.com/GenesisCommunity/go-genesis)
![](https://reposs.herokuapp.com/?path=GenesisCommunity/go-genesis&style=flat)
[![API Reference](
https://camo.githubusercontent.com/915b7be44ada53c290eb157634330494ebe3e30a/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f676f6c616e672f6764646f3f7374617475732e737667
)](https://godoc.org/github.com/GenesisCommunity/go-genesis)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/GenesisCommunity?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)


<p align="center">
  <a href="README.md">EN</a> | CN | <a href="README-ES.md">ES</a> | <a href="README-RU.md">RU</a>
</p>


## 目录

- [简介](#%E5%BC%95%E8%A8%80)
- [Genesis 的特点？](#%E7%9A%84%E7%89%B9%E7%82%B9)
- [Github 用户快来获取代币！](#%E8%8E%B7%E5%BE%97%E8%87%AA%E5%B7%B1%E7%9A%84github-user%E4%BB%A3%E5%B8%81)
- [接入 Github](#%E4%B8%8Egithub%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%BD%93%E5%8C%96)
- [Genesis 是如何运行的](#genesis%E6%98%AF%E5%A6%82%E4%BD%95%E8%BF%90%E8%A1%8C%E7%9A%84)
- [快速开始](#快速开始)
- [计划](#计划)
- [参与开发](#参与开发)
- [文档](#文档)
- [版本管理](#版本管理)
- [开发者](#开发者)
- [许可证](#许可证)

## 简介

Genesis 是一个开源的区块链平台，最早的开发由程序员奥列格•斯特列雷科在 2011 年完成的。平台源代码完全从零开始编写。参与这一项目的团队由超过15名高级程序员组成。出于 Genesis 的理念，我们并不想以 ICO 的方式来发布我们的平台，为了促使 Genesis 发展成为世界上最优秀的区块链平台，我们决定将85%的代币免费分发给大部分程序员。

## Genesis的特点？

- 您可在 Genesis 中创建带有特定规则的你自己的区块链生态系统，例如你自己的 Ethereum，它可与其他人创建的 Ethereum（Genesis的生态系统）协作。
- 平台使用 Simvolio 和 Protypo 合约编程语言，你只需4个小时就能掌握它们。
- 你可以通过 iOS 或 Android 的手机将编写好的 Simvolio 和 Protypo 程序发布至平台。我们即将在 Appstore 和 Google Play 上线专门的应用，你也可以通过移动应用更新修改你发布的程序。
- 平台中的全部系统数据以及共识算法都可以自定义，可通过社区投票或其他算法进行更改。


## Github 用户快来获取代币！

为了防止 Genesis 的公共区块链平台中受到攻击，你需要使用 GEN 代币支付网络资源使用费用（类似其他平台那样）。我们将在平台的创世块中发行1亿枚代币，其中85%（8500万GEN）将发放给注册时间1年以上（防止机器人）的85万Github 用户。我们之所以选择这种方式分配代币，是因为 Github 用户超过2400万人，大家几乎都是程序员。

最后，约85万程序员可获得对区块链平台的全面掌控，使用新规则建立新世界。




## Genesis是如何运行的

你可以使用一种名为 [Simvolio](http://GenesisCommunity.readthedocs.io/en/latest/introduction/script.html#simvolio-contracts-language) 类似C语言的智能合约编程语言来进行开发，之后被编译成字节码，它只包含非常少的变成指令和预置方法。

<p align="center">
    <img src="https://i.imgur.com/qHosOsw.jpg">
</p>

你可以使用 [Protypo](http://GenesisCommunity.readthedocs.io/en/latest/introduction/templates2.html#protypo-template-language) 来开发前端界面. Protypo 是一种模板引擎，支持一些列方法和树状结构的元素。

<p align="center">
    <img src="https://i.imgur.com/CYL1b95.jpg">
</p>

你可以通过注册表为智能合约\前端界面设置 [规则](https://GenesisCommunity.readthedocs.io/en/latest/introduction/what-is-Apla.html#access-rights-control-mechanism)。

<p align="center">
    <img src="https://i.imgur.com/DkvR7MZ.jpg">
</p>

也可以把你自己开发的区块链应用上传至 Google Play 或 Appstore 应用商店。

[https://github.com/GenesisCommunity/genesis-reactnative](https://github.com/GenesisCommunity/genesis-reactnative)

<p align="center">
    <img src="https://i.imgur.com/m46Kxwc.png" alt="" width=250>
</p>


## 快速开发

<p align="center">
    <img src="https://i.imgur.com/6oYykyk.jpg">
</p>

[https://github.com/GenesisCommunity/quick-start](https://github.com/GenesisCommunity/quick-start)

在 macos 部署:

```bash
bash manage.sh install 3 (抬升3个局域NOD)
```

在 linux 部署：

```bash
bash manage.sh install 3 (抬升3个局域NOD)
```

在 windows 部署:
[https://github.com/GenesisCommunity/quick-start-win/releases](https://github.com/GenesisCommunity/quick-start-win/releases)

```bash
win_install.exe
```

#### Blockexplorer 控制台工具

```bash
bash manage.sh db-shell 1
```

```bash
select id, time, node_position, key_id, tx from block_chain ORDER BY ID DESC LIMIT 20;
```

查看生成的区块表：

```bash
select value from system_parameters where name='full_nodes';
```

Web 版本的 Blockexplorer 马上就会放出。

## 计划

我们觉得代码还有很多可以改进的地方，所以还在不断提高它的质量和产量。

#### Testnet 测试网络

[date to be announced]

#### Mainnet 主网络

[date to be announced]

## 参与开发

请阅读 [CONTRIBUTING.md](https://github.com/GenesisCommunity/go-genesis/blob/master/CONTRIBUTING.md) 以获取有关 Pull Requests 的详细信息。

## 文档

请阅读并帮我们完善 [文档](https://GenesisCommunity.readthedocs.io/en/latest/#contents)


## 版本管理

我们使用 [SemVer](http://semver.org/) 实现版本管理，现有版本请见 [tags on this repository](https://github.com/GenesisCommunity/go-genesis/tags)


## 开发人员

- Oleg Strelenko - founder, Initial work - https://github.com/c-darwin
- Alexey Krivonogov - core developer - https://github.com/gentee
- Alexander Boldachev - Simvolio/Protypo architecture - https://github.com/AleDvin
- Roman Potekhin - backend developer - https://github.com/potehinre
- Evgeny Lerner - backend developer - https://github.com/dvork1ng
- Dmitrij Galitskij - backend developer - https://github.com/yddmat
- Dmitriy Chertkov - backend developer - https://github.com/dchertkov
- Roman Poletaev - backend developer - https://github.com/rpoletaev
- Igor Chertov - frontend developer - https://github.com/Saurer
- Alexey Voskresenskiy - Protypo constructor developer - https://github.com/av-alex
- Vladimir Matsola - mobile developer - https://github.com/2vm
- Alex Stern - bash/python developer - https://github.com/blitzstern5
- Vasily Starovetskiy - Simvolio/Protypo developer - https://github.com/syypoo
- Andrey Voronkov - Simvolio/Protypo developer - https://github.com/CynepHy6
- Viktor Waise - Simvolio/Protypo developer - https://github.com/Waisevi
- Aleksey Sukhanov - Simvolio/Protypo developer - https://github.com/pekanius
- Yuriy Lomakin - MVP frontend, tester - https://github.com/ylomakin
- Elena Konkina - tester - https://github.com/lfreze

请查看该项目的 [参与者](https://github.com/GenesisCommunity/go-genesis/graphs/contributors) 名单。

[加入](mailto:hello@apla.io) Genesis 团队！


## 许可证

该项目获得GPLv3许可-详情请查看文件 [LICENSE](https://github.com/GenesisCommunity/go-genesis/blob/master/LICENSE)

<p align="center">
<a href="#"><img src="http://www.kgsbo.com/wp-content/themes/kgsbo/images/top.png" width=100 align="center"></a><br>
  <a href="#">返回顶部</a>
</p>
