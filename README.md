<h4 align="center">访客数 :eyes:</h4>

<p align="center">
<img  src="https://profile-counter.glitch.me/Leon406_SubCrawler/count.svg" alt="Sub :: Visitor's Count" />
 <img width=0 height=0 src="https://profile-counter.glitch.me/Leon406/count.svg" alt="Leon406:: Visitor's Count" />
</p>

## <span id="top">订阅链接</span>

- https://github.com/JACKUSR2089/v2ray-subscribed
- https://github.com/clashconfig/online
- https://github.com/colatiger/v2ray-nodes
- :star:https://github.com/freefq/free
- https://github.com/skywolf627/VmessActions
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2)
- https://github.com/adiwzx/freenode

## 优质节点池

[大部分都停用,自行搜索](https://www.google.com/search?client=aff-cs-360se&ie=UTF-8&q=inurl%3A%2Fclash%2Fproxies&)

## 节点池搭建

> 有服务器的可自行搭建 [proxypool](https://github.com/Leon406/proxypool)  配置文件 [source.yaml](https://github.com/Leon406/proxypool/blob/master/config/source.yaml) 

## <span id="subCon">订阅转换</span>

- [github acl4ssr-sub](https://acl4ssr-sub.github.io/)
- [sub v1](https://sub.v1.mk/)
- [:star:本地搭建 推荐](https://github.com/tindy2013/subconverter/releases)
- [品云](https://id9.cc/)
- [肥羊转换](https://sub.mcwy.cloud/)


## 节点测速

- 本地测速
    - [stairspeedtest-reborn](https://github.com/tindy2013/stairspeedtest-reborn)
    - [:star:LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest)
    - [nodescatch ](https://github.com/bulianglin/demo)     [个人组件更新版 提取码 8c0d](https://leon.lanzoub.com/b0db6sooh#8c0d)
- 在线测速(基于上面本地测速搭建的服务,建议自行搭建,目前大部分都挂了)



## 节点过滤

删除以下可能存在测速问题的节点

- SSR
  - none
  - rc4
  - rc4-md5
- SS
  - aes-128-cfb
  - aes-256-cfb
  - rc4-md5
- VMESS
  -  none
  -  grpc
  -  h2
  -  auto

## 项目生成内容

### 节点

- github action (  [节点详情](./sub/info.md) )
  - [ss](https://raw.fastgit.org/Leon406/SubCrawler/master/sub/share/ss)
  - [ssr](https://raw.fastgit.org/Leon406/SubCrawler/master/sub/share/ssr)
  - [v2ray](https://raw.fastgit.org/Leon406/SubCrawler/master/sub/share/v2)
  - [trojan](https://raw.fastgit.org/Leon406/SubCrawler/master/sub/share/tr)
  - [vless](https://raw.fastgit.org/Leon406/SubCrawler/master/sub/share/vless) 未测速,litespeed不支持测速
  - [四合一转换(不含vless)](https://raw.githubusercontent.com/Leon406/SubCrawler/main/sub/share/all2)


- 本地构建 (github action 节点测试为国外服务器,国内不保证能用)

```
## windows系统执行
localFilter.bat
## Linux /Mac OS系统执行
bash localFilter  
## 或者
chmod +x localFilter && ./localFilter
```




> 默认生成的为base64编码(v2rayN/ss/ssr等客户端可直接使用),其他请自行使用[订阅转换](#subCon)进行转换

### Hosts

- [广告屏蔽hosts](https://raw.fastgit.org/Leon406/SubCrawler/master/sub/share/blackhosts) 
- [googlehosts重筛](https://raw.fastgit.org/Leon406/SubCrawler/master/sub/share/whitehost)
- [github及常用域名](https://raw.fastgit.org/Leon406/SubCrawler/master/sub/share/host)

## 走代理后ip匿名检测

- https://bgp.he.net/
- https://browserleaks.com/
- https://ip.voidsec.com/
- https://ipinfo.io/
- https://ipleak.com/
- https://ipleak.net/
- https://ipleak.org/
- https://ipx.ac/run
- https://nstool.netease.com/
- https://test-ipv6.com/
- https://whatismyipaddress.com/blacklist-check
- https://whoer.net/
- https://www.astrill.com/dns-leak-test
- https://www.astrill.com/ipv6-leak-test
- https://www.astrill.com/port-scan
- https://www.astrill.com/vpn-leak-test
- https://www.astrill.com/what-is-my-ip
- https://www.deviceinfo.me/
- https://www.dnsleaktest.com/
- https://www.doileak.com/
- https://www.expressvpn.com/webrtc-leak-test


## 使用软件

| 平台    | 软件                                                         | 支持协议                                                     |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Windows | [V2rayN](https://github.com/2dust/v2rayN/releases)           | SS、Trojan、Vmess、VLESS                                     |
| Windows | [Clash CFW  **(推荐)**](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS、SSR、Trojan、Vmess、VLESS                                |
| macOS   | [ClashX](https://github.com/yichengchen/clashX/releases)     | SS、SSR、Trojan、V2ray                                       |
| macOS   | [V2rayU](https://github.com/yanue/V2rayU/releases)           | SS、SSR、Trojan、V2ray                                       |
| Android | [V2rayNG](https://github.com/2dust/v2rayNG/releases)         | SS、Trojan、V2ray（Vmess、VLESS）、Xray                      |
| Android | [ClashForAndroid  **(推荐)**](https://github.com/Kr328/ClashForAndroid/releases) | SS、SSR、Trojan、Vmess、VLESS                                |
| Android | [SSRAY](https://github.com/xxf098/shadowsocksr-v2ray-trojan-android/releases) | SSR、V2ray、Trojan                                           |
| Android | [SagerNet](https://github.com/SagerNet/SagerNet/releases)    | VMess / VLESS / SSR / Trojan / Trojan-Go/ NaiveProxy / HTTP(S) / SOCKS5/etc. |
| Android | [Matsuri (茉莉)**(推荐)**](https://github.com/MatsuriDayo/Matsuri) sager分支 | VMess / VLESS / SSR / Trojan / Trojan-Go/ NaiveProxy / HTTP(S) / SOCKS5/etc. |
| IOS     | Shadowrocket 小火箭 IOS非国区购买                            | SS、SSR、Trojan、V2ray、VLESS                                |
| IOS     | Quantumult  IOS非国区购买                                    | SS、SSR、Trojan、V2ray                                       |
| IOS     | QuantumultX  IOS非国区购买                                   | SS、SSR、Trojan、V2ray                                       |



## Stargazers over time

[![Stargazers over time](https://starchart.cc/Leon406/SubCrawler.svg)](https://starchart.cc/Leon406/SubCrawler)

## 声明

本项目仅限个人自己使用，禁止使用本项目进行营利和做其他违法事情，产生的一切后果本项目概不负责

[回到顶部](#top)

