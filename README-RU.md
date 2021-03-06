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
  <a href="README.md">EN</a> | <a href="README-CN.md">CN</a> | <a href="README-ES.md">ES</a> | RU
</p>


## Оглавление

- [Введение](#Введение)
- [Чем Genesis уникален?](#Чем-genesis-уникален)
- [Получи свои токены github-юзер!](#Получи-свои-токены-github-юзер)
- [Интеграция с github](#Интеграция-с-github)
- [Как Genesis работает](#Как-genesis-работает)
- [Быстрый старт](#Быстрый-старт)
- [Планы](#Планы)
- [Участие в разработке](#Участие-в-разработке)
- [Документация](#Документация)
- [Версионность](#Версионность)
- [Разработчики](#Разработчики)
- [Лицензия](#Лицензия)

## Введение
Genesis - opensource блокчейн платформа, основа которой была заложена в 2011 году программистом Олегом Стреленко. Код платформы был написал полностью с нуля. Сейчас над проектом работает команда из более чем 15-и высококлассных разработчиков. Мы не можем проводить ICO для той концепции Genesis, которая нам нравится, поэтому мы приняли решение раздать бесплатно 85% токенов максимальному количеству программистов, чтобы c помощью сообщества Genesis стал лучшей блокчейн платформой в мире.

## Чем Genesis уникален?
 - В Genesis вы можете создать собственную блокчейн-экосистему со своими правилами, по сути, создать свой Ethereum и он сможет взаимодействовать с Ethereum (экосистемой на Genesis) вашего соседа.
 - Чтобы начать разрабатывать на языках Simvolio и Protypo, нужно потратить на их изучение всего около 4 часов.
 - Свою разработку на Simvolio и Protypo можно сразу будет загрузить на мобильный телефон с IOS и Android. Делается это либо с помощью нашего приложения, которое будет скоро выложено в Appstore и Google Play, либо вы сможете немного изменив исходники нашего мобильного приложения разместить свой вариант.
 - Все системные параметры платформы полностью настраиваемые, даже алгоритм консенсуса, и изменять их можно при помощи голосования сообщества или любыми другими алгоритмами.

## Получи свои токены, github-юзер!
Для защиты от атак в Genesis, как и в других публичных блокчейн-платформах, есть оплата использования ресурсов сети токенами GEN. В генезис-блоке платформы будет эмиссировано 100 млн токенов и 85% (85 млн GEN) будет распределено между примерно 850 тысячами гитхаб-юзеров, чьи аккаунты существуют не менее одного года (для защиты от ботов). Мы решили выбрать такой способ раздачи токенов, потому что гитхаб-юзеров более 24 млн человек и почти все они программисты.
<br>

В итоге около 850 тыс программистов получат полный контроль над блокчейн платформой и смогут начать строить новый мир с новыми правилами.<br> <br>



## Как Genesis работает
Разрабатывайте приложения на  [Simvolio](http://GenesisCommunity.readthedocs.io/en/latest/introduction/script.html#simvolio-contracts-language). Simvolio - это С-подобный язык программирования на котором пишутся контракты и который компилируется в байт-код. Имеет минимально необходимое количество управляющих конструкций и встроенных функций.
<p align="center">
    <img src="https://i.imgur.com/qHosOsw.jpg">
</p><br>

Создавайте интерфейсы на [Protypo](http://GenesisCommunity.readthedocs.io/en/latest/introduction/templates2.html#protypo-template-language). Protypo - язык описания страниц для фронтенда. Является по сути шаблонизатором который переводит последовательность функций с параметрами в древовидное представление элементов для фронтенда.

<p align="center">
    <img src="https://i.imgur.com/CYL1b95.jpg">
</p>
<br>

Устанавливайте [права](https://GenesisCommunity.readthedocs.io/en/latest/introduction/what-is-Apla.html#access-rights-control-mechanism) на изменение кода контрактов/интерфейсов и данных реестров

<p align="center">
    <img src="https://i.imgur.com/DkvR7MZ.jpg">
</p>
Размещайте свое блокчейн-приложение в плей-маркете и апсторе. <br>
https://github.com/GenesisCommunity/genesis-reactnative<br><br><br>
<p align="center">
    <img src="https://i.imgur.com/m46Kxwc.png" alt="" width=250>
</p>


## Быстрый старт
<p align="center">
    <img src="https://i.imgur.com/6oYykyk.jpg">
</p>

https://github.com/GenesisCommunity/quick-start<Br>

Развернуть стенд на macos:
```bash
bash manage.sh install 3 (поднимает 3 локальные ноды)
```
Развернуть стенд на linux:
```bash
bash manage.sh install 3 (поднимает 3 локальные ноды)
```
Развернуть стенд на windows:<br>
https://github.com/GenesisCommunity/quick-start-win/releases<br>
```bash
win_install.exe
```


#### Blockexplorer в консоли
```bash
bash manage.sh db-shell 1
```
```bash
select id, time, node_position, key_id, tx from block_chain ORDER BY ID DESC LIMIT 20;
```
Список нод, генерирующих блоки:<br>
```bash
select value from system_parameters where name='full_nodes';
```
web-версия Blockexplorer скоро будет доступна.<br>


## Планы

Мы считаем, что наш код можно сделать лучше, поэтому будем работать над его качеством и производительностью.

#### Testnet

[date to be announced]<br>
В тестовой сети можно будет проверить работу системы используя свой приватный ключ.<br>

#### Mainnet

[date to be announced]<br>
## Участие в разработке
Пожалуйста, прочитайте [CONTRIBUTING.md](https://github.com/GenesisCommunity/go-genesis/blob/master/CONTRIBUTING.md) для получения подробной информации о процессе отправки Pull Requests.

## Документация
Пожалуйста, изучайте и дополняйте нашу [документацию](https://GenesisCommunity.readthedocs.io/ru/latest/#contents)


## Версионность
Мы используем [SemVer](http://semver.org/) для управления версиями. Доступные версии см. [tags on this repository](https://github.com/GenesisCommunity/go-genesis/tags)


## Разработчики

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

See also the list of [contributors](https://github.com/GenesisCommunity/go-genesis/graphs/contributors) who participated in this project.<br>
[Join](mailto:hello@apla.io) the Genesis team!


## Лицензия

This project is licensed under the GPLv3 License - see the [LICENSE](https://github.com/GenesisCommunity/go-genesis/blob/master/LICENSE) file for details

<p align="center">
<a href="#"><img src="http://www.kgsbo.com/wp-content/themes/kgsbo/images/top.png" width=100 align="center"></a><br>
  <a href="#">Подняться вверх</a>
</p>


