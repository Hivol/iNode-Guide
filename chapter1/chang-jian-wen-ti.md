## Q: 客户端打不开

* 卸载并重装客户端（卸载后重启）

* 安装过程中没有关闭杀毒软件

## 

## Q: 显示「连接失败，请与管理员联系」

* 账号密码错误

* 有人在用你的号

* 登陆了无线网但没有正确下线

> 可以重新连接至无线网并点击“下线”

* 你的账号被拉进了小黑屋

> 需要到其孜楼2-3老师处询问

## 

## Q: 显示「网络电缆没插好」

* 硬件有问题

* 客户端网卡选错【再断开连接的情况下单击右键，选择属性】

> 选择网卡是无视bluetooth、无视wireless，选择PCIe/USB字样的网卡

## 

## Q: 显示「网卡被禁用」

* 客户端网卡选错（同上）

* 网卡被禁用

> 单击计算机右键，按顺序找到：管理-设备管理器-网络适配器，选择带PCIe/USB的网卡，单击右键，选择启用网卡

* 网卡驱动出问题

> 在设备管理器中卸载网卡驱动，再扫描检测硬件改动（计算机-属性-设备管理器-网络适配器）

## 

## Q: 提示「身份验证成功」后没下文 / 获取不到IP地址

* 取消各种无线协议，如猎豹WIFI

> 网络和共享中心-以太网-属性

* IP/DNS设置为自动获取

> 网络和共享中心-以太网-属性-ipv4/ipv6

* 在“服务”中重启动 DHCP/WLAN 这两项服务

> 右键单击计算机-管理-服务

* 重置浏览器设置

> Internet 选项-高级-重置

* 刷新DNS和WINSOCK（管理员权限下）

> 在cmd中输入 ipconfig/flushdns \(回车\) netsh winsock reset

## 

## Q: 获取到了IP地址\(IP地址开头为10.2x\)，却无法上网

* 欠费了，缴费吧qwq

## 

## Q: 连上网，可以上qq，却无法打开网页

* 一般是DNS服务出问题了

> IP/DNS 选为自动获取\(见5. 提示「身份验证成功」后没下文\)

> 刷新DNS和WINSOCK



## Q: 见到了不同于以上所有的失败提示，或者根据上面方法解决不了你的问题？

* 版本问题：卸载重装正确版本

* 校园网问题：去其孜楼2-3问老师自己账号有没有问题

* 来找义修队的小可爱们呐



