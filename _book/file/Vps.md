# VPS的购买

## 服务商

选择[Vultr](https://www.vultr.com/)

优点：

* 多机房：线路多
* 价格：每月最优惠套餐3.5美元，所有套餐带宽都相同
* 便利：支持支付宝

## 注册

![avatar](/image/VPSIndex.png)

点击红框处sign up按钮进入注册页面

![avatar](/image/VPSRegister.png)

输入邮箱和密码进行获取验证码操作

## 控制台介绍

![avatar](/image/VPSControl.png)

## 充值流程

![avatar](/image/VPSRecharge.png)

之后将会出现支付宝的付款码，扫码付账即可

## 主机的创建

![avatar](/image/VPSAdd.png)

![avatar](/image/VPSSelectPerformance.png)

![avatar](/image/VPSSelectLocation.png)

关于地区选择

[下载Windows平台测试软件](/resources/vultr-auto-ping-test.bat)

* 软件将ping所有机房30次查看丢包，直接选丢包最少的机房即可

[其他平台使用的web版工具](https://cloud.feitsui.com/vultr)

* web版工具只ping所有机房1次，无法测试丢包只能测试延迟

![avatar](/image/VPSSelectServerType.png)

系统选择，一般CentOS 8 x64 默认即可

![avatar](/image/VPSSelectSize.png)

* 服务器配置，由于所有类型的服务器带宽都是相同的，所以选择最便宜的就可以

![avatar](/image/VPSCreate.png)

最后点击创建按钮创建服务器