# easyhosts
基于 Github 项目整合的远程 Hosts 直链，适配多种规则、终端。

每 30 分钟 自动同步一次 Github 最新可用项目并提供打包下载

# hosts 支持站点
目前支持访问以下网域有：

Google 全家桶,Facebook,Instagram,Twitter,Tumblr,Youtube视频,Google Play下载等。

注意：Hosts方式访问以上站点，大部分**只允许以HTTPS方式打开**。

# 文件说明
更多说明请访问 Easyhost 项目主页：[https://windows.cat][1]


----------


***常规增强 Hosts：(racaljk 常用网站 + sy618 Google Play 下载源 + sy618 Youtube 视频源)***

**hosts.txt**：常规增强 Hosts 规则，适用于Android/iOS/Windows/Mac OS/Linux等。

**dnsmasq.txt**：常规增强 dnsmasq规则，适用于 Linux 及 OpenWrt，路由器可用。

**surge.txt**：常规增强 Surge 规则，适用于Surge/Shadowrocket等各种代理软件。


----------


***去广告增强 Hosts：(racaljk + sy618 Google Play 下载源 + sy618 Youtube 视频源 + vokins 去广告源)***

**hosts-noad.txt**：去广告增强 Hosts 规则，适用于Android/iOS/Windows/Mac

**dnsmasq-noad.txt**：去广告增强 dnsmasq规则，适用于 Linux 及 OpenWrt，路由器可用。

**surge-noad.txt**：去广告增强 Surge 规则，适用于Surge/Shadowrocket等各种代理软件。


----------


***其他文件：***
**log.txt**：最新检测时间以此文件显示时间为准

检测周期为30分钟，本 Github 项目中的所有规则只会在上游Hosts发生变化时自动与Github同步，同步周期往往超过30分钟。

**hosts.tar.gz**：含所有规则的压缩包文件

**windows_hosts_manager_tools.zip**：Windows Hosts 管理工具(批处理)




# 感谢
[racaljk][2] / [sy618][3] / [vokins][4] / [景文互联][5]


  [1]: https://windows.cat
  [2]: https://github.com/racaljk/hosts
  [3]: https://github.com/sy618/hosts
  [4]: https://github.com/vokins/yhosts
  [5]: https://www.jwdns.com/