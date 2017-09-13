# 最新动态
Easy Hosts 项目一直以来都是根据上游 Github Hosts 规则，在服务器上无人工干预自动完成整合更新的，但是大陆网络环境复杂，Google 网域 IP 封锁严重，如果遇到无法访问Google网域的状况，可在 Issues 进行反馈，核实后我们将会尽快手动更新最新可用的 Google 网域 IP，以确保项目可用性，感谢网友反馈与关注，谢谢。

# easyhosts
基于 Github 项目整合的远程 Hosts 直链，适配多种规则、终端。

每 30 分钟 自动同步一次 Github 最新可用项目并提供打包下载。

# hosts 支持站点
目前支持访问以下网域，具体自行搜索规则文件：

Google 全家桶，Facebook，Instagram，Twitter，Tumblr，Youtube视频，Google Play下载等。

注意：Hosts方式访问以上站点，大部分**只允许以HTTPS方式打开**。

# 文件说明
更多说明请访问 easyhosts 项目主页：[https://windows.cat][1]


----------


***常规增强 Hosts：(racaljk 常用网站 + sy618 Google Play 下载源 + sy618 Youtube 视频源)***

**[hosts.txt][2]**：常规增强 Hosts 规则，适用于Android/iOS/Windows/Mac OS/Linux等。

**[dnsmasq.txt][3]**：常规增强 dnsmasq规则，适用于 Linux 及 OpenWrt，路由器可用。

**[surge.txt][4]**：常规增强 Surge 规则，适用于Surge/Shadowrocket等各种代理软件。


----------


***去广告增强 Hosts：(racaljk 常用网站 + sy618 Google Play 下载源 + sy618 Youtube 视频源 + vokins 去广告源)***

**[hosts-noad.txt][5]**：去广告增强 Hosts 规则，适用于Android/iOS/Windows/Mac

**[dnsmasq-noad.txt][6]**：去广告增强 dnsmasq规则，适用于 Linux 及 OpenWrt，路由器可用。

**[surge-noad.txt][7]**：去广告增强 Surge 规则，适用于Surge/Shadowrocket等各种代理软件。


----------


***其他文件：***

**log.txt**：最新检测时间（更新周期以此文件为准）

检测周期为30分钟，本 Github 项目中的所有规则只会在上游Hosts发生变化时自动与Github同步，同步周期往往超过30分钟。

**hosts.tar.gz**：包含所有规则的压缩包文件

**windows_hosts_manager_tools.zip**：Windows Hosts 管理工具(批处理)




# 感谢
[racaljk][8] / [sy618][9] / [vokins][10] / [景文互联][11]


  [1]: https://windows.cat
  [2]: https://windows.cat/hosts.txt
  [3]: https://windows.cat/dnsmasq.txt
  [4]: https://windows.cat/surge.txt
  [5]: https://windows.cat/hosts-noad.txt
  [6]: https://windows.cat/dnsmasq-noad.txt
  [7]: https://windows.cat/surge-noad.txt
  [8]: https://github.com/racaljk/hosts
  [9]: https://github.com/sy618/hosts
  [10]: https://github.com/vokins/yhosts
  [11]: https://www.jwdns.com/