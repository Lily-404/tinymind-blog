---
title: OepnConnect VPN在Mac系统的超时的问题
date: 2024-10-14T14:26:10.129Z
---

### 介绍

起因是因为公司需要使用OpenVPN Connect，正确配置也无法解决超时问题，无法使用

后来东搜西找，最后在openvpn的github上找到了问题的解决方案，这个方法适用于M芯片

Issues：https://github.com/OpenVPN/openvpn3/issues/139



### 解决

在Terminal运行：

```
sudo /Library/Frameworks/OpenVPNConnect.framework/Versions/Current/usr/sbin/ovpnagent
```

