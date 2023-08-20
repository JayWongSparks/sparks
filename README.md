<div id="top"></div>

<div align="center">

# sparks

<h2>一款矿池级别的运维工具👍 </h2>

<img src="/image/logo.png" alt="Logo" width="670">
   <img src="/image/1.png" alt="Logo" width="670">
      <img src="/image/2.png" alt="Logo" width="670">

[![CakeSystem][CakeSystem.io-badge]][CakeSystem.io]
[![Downloads][downloads-badge]][releases]
[![Stargazers][stars-shield]][stars-url]

<a href="https://github.com/JayWongSparks/sparks/blob/main/README.md">简体中文</a>｜<a href="https://github.com/JayWongSparks/sparks/blob/main/i18n/zh_en.md">English</a>

强大且经验丰富的监控和记录系统可以立即解决矿场异常情况。

在矿池级别上统计哈希率，并可以一目了然地查看任何货币的哈希率。

根据终端设备自动调整工作模式和数据流量，避免高度低效的任务共享。

主动防御和过滤系统提高了环境的安全性并及时发现危险。

前端客户端具有高性能的TCP集成和压缩技术。无论矿场距离矿池有多远，它们都可以有效地减少矿场延迟并防止所有中间人攻击。

兼容各种算法的佣金系统可以合理地提高矿场利润。

内置算法引擎可以更新流行货币而不会产生热量。

仪表盘完美兼容各种设备，PC、MOBILE、PAD一目了然。

完美的控制逻辑，即使开启了服务费，矿池端也不会显示设备离线。

基于Rust的开发，高效的语言带来无与伦比的性能。

高性能，下一代运维体验，是由硅谷顶尖的研发团队和Cake专家带来的专业矿场运维系统-CakeSystem

（部分预览）

<img src="/image/1.png" alt="Logo" width="670">

</div>

# 加入聊天组

Telegram：<a href="https://t.me/+OiG7xOS-ZZg1ZDI1">https://t.me/+OiG7xOS-ZZg1ZDI1</a>

<!-- Discord：<a href="sadfasfdasfsa">sadfasfdasfsa</a> -->

# 特别感谢

<img src="/image/icon-logo-blue.png" alt="Logo" width="100">

<img src="/image/poolin.svg" alt="Logo" width="100">

<p>感谢以上矿池在一定范围内提供了技术支持😊</p>

# 支持的算法

对于支持的算法，相应的货币将随时热更新，客户端0将承担负担


| arithmetic      | Support     | Relevant currency |
| --------------- | ------------| ------------------|
| SHA256          | ✅          | BTC、BCH...        
| ETHASH          | ✅          | ETC、ETHW、ETHF、ETC+ZIL、ETHW+ZIL、ETHF+ZIL
| SCRYPT          | ✅          | LTC...
| KHEAVYHASH      | ✅          | KASPA...


# 服务协议

CakeSystem受香港法律监管。请注意，不同国家/地区的法律要求可能会限制此类产品和服务。因此，该产品和服务以及某些功能可能不可用，或者在某些司法管辖区或地区或某些用户中可能受到限制。您应该理解并遵守当地的法律法规。如果您使用此产品，默认代表将接受上述许可证。如果本产品引起的法律问题与本产品无关。




[CakeSystem.io]: https://github.com/JayWongSparks/sparks
[CakeSystem.io-badge]: https://img.shields.io/badge/CakeSystem-v3.2.4-green?logo=rust
[downloads-badge]: https://img.shields.io/github/downloads/ajeetdsouza/zoxide/total?logo=github&logoColor=white&style=flat-square
[releases]: https://github.com/JayWongSparks/sparks/releases
[stars-url]: https://github.com/JayWongSparks/sparks/stargazers
[stars-shield]: https://github.com/JayWongSparks/sparks/CakeSystem.svg?style=flat
[stars-url]: https://github.com/JayWongSparks/sparks/stargazers

# 安装 

1. **Install**

   选择适合您的操作系统

   <details open>
   <summary>Linux</summary>

   > 运行以下shell指令以运行工具包
   >
   > ```sh
   >  bash <(curl -s -L https://github.com/JayWongSparks/sparks/raw/main/install.sh)
   > ```
   >
   > 成功运行后，您将看到以下菜单。
   >

   </details>

   <details open>
   <summary>Windows</summary>

   > 请直接从此项目的Windows目录下载指定的版本：
   >
   > ```sh
   > https://github.com/JayWongSparks/sparks/tree/main/windows
   > ```
   >

   </details>


# 更新日志
```
# 更新日志
```
3.2.4已发布
大幅提升当前支持的所有币种的算力统计及抽水的精准度

3.2.3已发布
彻底解决kas爆内存问题（1千台机器测试）

3.2.2+3.2.1合并发布
修复了kas缓慢爆内存的bug
修复了多台设备相同钱包但没有配置矿机名称导致的高无效bug

3.2.0已发布
增加了对k1矿池的支持
优化了蚂蚁矿池的连接次数统计
增加了kas系列机型币种对应的端口
彻底解除跨池抽水限制
开放了RMS服务的配置
优化了抽水的精准度，现在大算力波动的机器也能抽到较为精准的比例了
增加了清除单独矿机抽水的选项
持续优化算力统计

3.1.0已发布
调优ETC算法下新算法的表现
单台矿机详情页面增加平均算力统计信息

KAS专业机无损抽水！！！支持ks0，ks1，ks2，ks3l等机器！
humpool，herominer，kas-pool，tw-pool测试后抽1得1！！！
币印鱼池等可以抽到herominer池1207端口，低损耗！

3.0.0已发布

重构了抽水算法, 现在所有币种都可以精准到千分位的抽水了

在容易发生损耗的矿池和矿机, 现在能确保终端客户减少的算力不会大于设置的比例

ks0、ks1、ks2这种机器，基于现有算法保证客户最小的算力损耗，不同矿池可能抽到的算力也不同,  通常不会抽到设置的百分比算力，为了保证客户尽量少损耗只能这样啦

e9pro完美优化, 且rust内可计算出与矿池一致的算力

重构了界面, 增加了钱包列表、设备列表筛选条件等等

增加了单矿机抽水的设置

优化了算力统计, 现在算力统计不再凌乱

优化了无效

2.1.0已发布
彻底解决卡死问题

2.0.9已发布
解决卡死问题
优化抽水

2.0.8已发布
合并了两种抽水算法
再次修复假死

2.0.7已发布
修复了.6版本假死的问题
优化了均衡模式下的算力抽不够的问题

2.0.6已发布
优化了算力补偿, 现在隐藏掉了算力补偿的选项, 算力默认分配给所有矿机
优化了E9pro, 现在所有矿池的E9pro都可以跑满了, 且cake里计算的e9pro算力精准的与矿池一致
增加了一种抽水的模式
增加了一种连接矿池的模式
优化了大算力的矿机

2.0.5已发布
[重要更新] 修复了CAKE在windows下假死的bug
修复了kas冰河以及其他芯片机的高无效
兼容了etc gtv66芯片机，完善了etc的算力计算
修复了一些算力统计的bug

2.0.4已发布
优化了算力补偿默认模式,  进一步降低了无效率
优化了kaspa在不同矿池协议下的表现, 现在lolminer和gminer可以在所有矿池正常工作了
优化了etc相关算法的算力计算逻辑, 现在计算和抽水更精准了
底层优化,  提升了硬件利用率
优化份额显示bug
优化首页活跃分布列表

2.0.2
修复了一个并发导致的软件崩溃
算力统计优化

2.0.0
多处客户端细节优化

现在抽水精准度MAX

增加算力补偿配置, 现在端口上可以配置损耗的算力补偿

增加了断线重连机制，最大限度保证频繁掉线的矿机也可以正常抽水

修复kas高无效的bug

算法引擎底层更新重构, 开始飞速支持小币种了

增加了SC币种

增加了CFX币种

修复了LTC在viabtc内高无效的问题

修复LTC算力显示不准确的问题

修复了LTC算力损耗大的问题

解除配置抽水钱包数量限制

解除跨池抽水限制

优化了端口日志，增加了程序运行时日志, 开启了设备日志

底层优化, 避免了几处容易引发程序崩溃的bug

1.0.4
优化了一些BTC机型的效率，优化了viabtc以及蚂蚁矿池的拒绝率
优化了一个细节bug, 无效率进一步降低
   
1.0.3
性能优化
增加了json、kt、excel格式的配置导入导出
   
1.0.2
底层重构，优化了多链接的处理与统计
针对e9pro进行了深度优化
开放错误日志
   
1.0.1
修复了因为链接导致的一些bug
   
1.0.0
公开测试版本发布
修复了证书相关问题
优化了e9pro
细节优化
   
0.9.999
修复了一个严重的安全漏洞
优化了所有币种的抽水逻辑
   
0.9.99
优化了一些btc的矿池
细节优化
   
0.9.98   
底层优化, 降低损耗
   
0.9.97
修复了程序假死的严重BUG

0.9.96
完美的btc&kaspa
多个细节修复

0.9.95
效率提升大大滴
多个细节修复

0.9.94
大大降低无效率

0.9.93
修复了一些bug
尝试使用新的方式解决延迟带来的无效

0.9.92
修复了部分内核kas连不进来的问题

完善了ltc小算力显示的bug

0.9.91
修复了热更新钱包导致程序崩溃的bug

修复了因为上个版本改动导致的kas无法正常工作的问题

0.9.9
优化了很多细节

优化的亚米设备

进一步降低无效的概率（尽管已经很低）

优化的内存和CPU使用率

0.1.4
优化e9以及e9pro

0.1.3
优化了蚂蚁s17

0.1.2
修复了Rust下多台设备任务混乱的严重问题

修正了kas无法接收任务的问题

0.1.0
内部测试版本
```

# Other issues

这是一个免费软件，不收取任何费用。从技术角度来看，它只需要终端设备计算能力的0.3%作为技术回报。由于不同货币的矿池逻辑，计费能力可能会上下波动。一般情况下，浮动范围不会超过+-%0.3


