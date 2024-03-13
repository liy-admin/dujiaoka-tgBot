# dujiaoka-tg-bot
基于独角兽发卡网后台 开发的电报机器人
<p align="center">
<a href="https://www.oracle.com/cn/java/technologies/javase/javase8-archive-downloads.html"><img src="https://img.shields.io/badge/Java-8-green.svg" alt="java 1.8"></a>
<a href="https://t.me/djsk_bot_group"><img src="https://img.shields.io/badge/Telegram-Group-blue"></a>
<a href="https://github.com/liy-admin/dujiaoka-tgBot/releases/tag/1.0.2"><img src="https://img.shields.io/badge/version-1.0.2-red" alt="version 1.0.2"></a>

</p>

## 写在前面

- 基于**独角数卡**的机器人，如果你没有搭建这玩意儿。可以先去  <b><a href="https://github.com/assimon/dujiaoka">看看</a></b>
- 机器人. 与基本的 **epusdt** 支付对接，内置 **易支付** 接口，可根据需求填写。
- 本程序有一定的上手难度（对于小白而言），需要您对linux服务器有基本的认识和操作度。
- 支持本地Linux机器部署（需要代理），vps就不用说了。后面再根据需要来更新客户端
- 最低标准是会用宝塔搭建服务。
- 本程序仅供学习交流使用，不得用于商业用途，如产生法律纠纷与本人无关。

## 搭建环境
1. 一台linux 64位服务器，推荐centos7 x64
2. 一个不常规的子域名，推荐使用cloudflare解析，这样会方便本地运行。如果你不会，可以先去  <b><a href="https://www.google.com/search?q=cloudflare%E4%BD%BF%E7%94%A8">看看</a></b>
3. Java (1.8 | 17)环境 ，推荐使用  <a href="https://www.oracle.com/cn/java/technologies/javase/javase8-archive-downloads.html">java 1.8</a>
4. 我这里使用的是  Mysql 5.7 版本

## 使用交流

### 测试机器人： <a href="https://t.me/djfkw_bot">独角机器人  (由于测试 · 没有易支付接口)</a> 

### Telegram: <a href="https://t.me/djsk_bot_group">交流群</a>

### Telegram 官方频道： <a href="https://t.me/djsk_bot">独角机器人</a>  (系统更新通知，bug更新，重大事件推送)

## 目前功能
- [x] 自动检测SQL是否安装
- [x] 余额查询
- [x] 历史订单查询
- [x] 商品展示，购买
- [x] epusdt 支付对接
- [x] 易支付对接
- [x] 客服功能
- [x] 根据下单数量，判断发送格式（纯文本，xlsx, txt）


## 部署教程

### 1. <a href="https://github.com/liy-admin/dujiaoka-tgBot/wiki/Linux-%E7%BA%AF%E6%89%8B%E5%B7%A5">Linux 纯手工部署</a>
### 2. <a href="https://github.com/liy-admin/dujiaoka-tgBot/wiki/%E5%AE%9D%E5%A1%94-%E2%80%90-%E6%90%AD%E5%BB%BA%E6%95%99%E7%A8%8B">宝塔部署</a>
