## 主要功能

1. 显示当前中国 IP 信息
2. 显示当前代理后的国外 IP 信息
3. 通过以上 2 个 IP 的差异判断当前是否能正常访问全世界的网络
4. 可以查询任意 IP 的信息
5. 检测一些网站的可用性：Google, Github, Youtube, 网易, 百度

## IP 信息类型

IP 信息里会显示以下信息：

1. 国家
2. 地区
3. 城市
4. 经纬度
5. ISP
6. AS 号

## 原理

1. 通过访问 taobao 获取本机的中国 IP
2. 通过 ipapi.co 获取本机的代理后的 IP（前提是你的代理规则里，ipapi.co 不走直连）
3. 通过 ipapi.co 查询这两个 IP 的信息并展示
4. 通过加载 Google, Github 等网站的一些小图片，看看是否超时来进行连通性判断

## 如何使用

直接下载所有代码，放到你本地或服务器上就行，没啥额外步骤。

## 额外说明

这个程序的 90% 的代码不是我写的，是通过 ChatGPT 写的。大概来回 30 个回合，外加一些细微的手动修改，完成了全部代码。