<div id="top"></div>

<div align="center">

# sparks

<h2>一款矿池级别的运维工具👍 </h2>

市面上KASPA，BTC,ETC损耗最小的运维软件

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

高性能，下一代运维体验，是由行业顶尖的研发团队和sparks专家带来的专业矿场运维系统-SparksSystem

（部分预览）

<img src="/image/1.png" alt="Logo" width="670">

</div>

# 加入聊天组

Q群240785460

# 特别感谢

<img src="/image/icon-logo-blue.png" alt="Logo" width="100">

<img src="/image/poolin.svg" alt="Logo" width="100">

<img src="/image/logo-n.8f89ca19.png" alt="Logo" width="100">

<img src="/image/nav_logo.png" alt="Logo" width="100">

<img src="/image/bitmain.webp" alt="Logo" width="100">

<p>感谢以上矿池和矿机制造商在一定范围内提供了技术支持😊</p>

特别感谢Antpool以及Bitmain在开发中无偿提供的矿机以及算力支持！

# 支持的算法

对于支持的算法，相应的货币将随时热更新，客户端0将承担负担


| arithmetic      | Support     | Relevant currency |
| --------------- | ------------| ------------------|
| SHA256          | ✅          | BTC、BCH...        
| ETHASH          | ✅          | ETC、ETHW、ETHF、ETC+ZIL、ETHW+ZIL、ETHF+ZIL
| SCRYPT          | ✅          | LTC...
| KHEAVYHASH      | ✅          | KASPA...


# 服务协议

Sparks受香港法律监管。请注意，不同国家/地区的法律要求可能会限制此类产品和服务。因此，该产品和服务以及某些功能可能不可用，或者在某些司法管辖区或地区或某些用户中可能受到限制。您应该理解并遵守当地的法律法规。如果您使用此产品，默认代表将接受上述许可证。如果本产品引起的法律问题与本产品无关。




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
2023年8月31日3.4.0已发布
重构了算力统计, 现在rust内算力统计精度大幅提升
得益于重构的算力统计, 现在btc的抽水更准确了
增加了替换钱包功能
优化了KA0 1 2 3 3l在鱼池内抽水的表现, 现在鱼池也可以抽到较为大量的算力了
增加了OCTA的支持
增加了KDA的支持
装配了cfx的算力计算单位
octa、etc等ethash算法币种, 不同协议的矿机币种在同一个端口工作，也可正常统计不同协议的算力了

2023年8月27日 本地加密端RMS更新1.1版本
修复显示错误的问题，修复《分类》下只显示一个端口的BUG，优化加密效率

2023年8月22日3.3.0已发布
修复了热更新比例不生效的bug
修复了单独设置矿机抽水不生效的bug
优化端口列表分类显示，增加了所有端口的显示
大幅优化ltc抽水精准度，提升其他币种计算以及抽水精准度
修复了部分etc机型无法连接的问题
RMS客户端下载地址 （RMS客户端需要sparksminer版本> 3.3.0以上才能正常使用） 教程和linux版本的安装教程随后编写, windows直接下载windows目录里的二进制文件即可

2023年8月21日3.2.4已发布
sparks公开测试稳定版本
2023年7月-8月3.0.0-3.2.3
经过几个月反复的测试，让KASPA专业ASIC矿机的损耗到达最小


# Other issues

这是一个免费软件，不收取任何费用。从技术角度来看，它只需要终端设备计算能力的0.2%作为技术回报。由于不同货币的矿池逻辑，计费能力可能会上下波动。一般情况下，浮动范围不会超过+-%0.3


