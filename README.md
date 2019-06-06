
## 严重声明：

此项目仅限于技术交流和探讨，在您测试完毕后必须在1秒钟内彻底删除项目副本。

此项目为bash一键脚本，其中涉及到的任何软件版权和责任归原作者所有。

## 友情提示：

在中国境内使用、传播、售卖、免费分享等任何翻墙服务，都是违法的。

如果你在中国境内使用、测试此项目脚本，或者使用此脚本搭建服务器发生以上违法行为，都有违作者意愿！

你必须立刻停止此行为！并删除脚本！


# V2RAY 基于 CADDY 的 VMESS+H2+TLS+Website(Use Host) 

### HTTP Header 分流，自带 Website 伪装站点 http 强制跳转 https，支持ssl非443端口，自动生成客户端config.json配置文件 web在线下载，重装自动清除残余的Http服务，每天自动升级最新的V2ray内核，支持 cdn 嵌套，自动续签ssl证书，自动生成Windows客户端和便捷启动脚本 一键添加开机自启动服务 一键开启系统ie代理。

使用：1.解析好域名； 2.运行一键安装脚本；
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/liyanglan/Website/master/h.sh" && chmod +x h.sh && bash h.sh
```
[新手请使用 Debian8/9 纯净系统安装]

备用1：一键更换新的 UUID，同时升级 Windows 客户端
```
bash h.sh -n
```

备用2：一键删除服务器中储存的客户端 config.json 配置文件，防止 Website 被抓取
```
bash h.sh -r
```

共享你的 V2ray 账号 （share）
```
bash h.sh -s

开启共享模式后，每周一自动更换 UUID 并推送至 Website 伪装站点首页。
为防止被恶意抓取，该模式下不提供客户端 config.json 文件下载。
```
