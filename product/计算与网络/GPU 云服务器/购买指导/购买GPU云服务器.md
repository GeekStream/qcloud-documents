1) 登录腾讯云官网，进入[GPU 云服务器购买页面](https://buy.qcloud.com/buy/cvm)

2) 选择计费模式：包年包月

3) 选择地域和可用区。目前 GPU 云服务器仅支持**上海一区**及**广州三区**。

4) 选择机型和配置。

- **机型：**【系列2】-【GPU型G2】
- **配置：**可根据您的需要挑选，具体配置，请参考[ GPU 机型配置](todo)


5) GPU 云服务器提供Centos、Ubuntu、Windows三种公共镜像，您可根据您的需要挑选公共镜像的版本。


6) 系统盘与数据盘
**系统盘：**Windows云服务器默认赠送50GB系统盘，Linux 实例默认赠送20GB系统盘。

**数据盘：**GPU 云服务器提供本地 SSD 硬盘的数据盘。您也可以购买 GPU 实例成功之后[创建云硬盘](https://www.qcloud.com/document/product/362/5744#.E5.88.9B.E5.BB.BA.E5.BC.B9.E6.80.A7.E4.BA.91.E7.9B.98)并挂载。



7) 选择网络类型（基础网络或私有网络）及公网带宽（按固定带宽计费或按使用流量计费）。
网络类型：

- 基础网络：适合新手用户，同一用户的云服务器内网互通。
- 私有网络：适合更高阶的用户，不同私有网络间逻辑隔离。

公网带宽：

- 按固定带宽计费：选择固定带宽，超过本带宽时将丢包。适合网络波动较小的场景。
- 按使用流量计费：按实际使用流量收费。可限制峰值带宽避免意外流量带来的费用，当瞬时带宽超过该值时将丢包。适合网络波动较大的场景。

8) 确定服务器数量、购买时长。
目前 GPU 云服务器单次购买时长最长支持5个月。

9) 选择安全组（<font color="red">确保登录端口3389开放</font>，更多信息见[安全组](http://www.qcloud.com/doc/product/213/%E5%AE%89%E5%85%A8%E7%BB%84)），点击【立即购买】按钮，完成支付后即可进入[控制台](https://console.qcloud.com/cvm)查收您的云服务器。

GPU 云服务器创建好后用户将会收到站内信，内容包括实例名称、公网 IP 地址、内网 IP 地址、登录名、初始登录密码等信息。您可以使用这些信息登录和管理实例，也请尽快更改您的登录密码保障主机安全性。



