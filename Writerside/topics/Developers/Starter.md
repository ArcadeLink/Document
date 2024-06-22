# 快速开始

本文档仍在施工中

<a href="Contribute.md">了解如何贡献</a>

<a href="Serial.md">了解如何开发串口设备</a>

## 通过二进制文件部署录制端

<a href="https://github.com/ArcadeLink">组织地址 (Github)</a>

<tabs>
<tab title="部署街机端">
下载 ArcadeLink.ArcadeSide 项目中对应的二进制文件，配置为开机自启动即可

在初次开启时，需要通过控制台进行运行细节的设置，请参阅
<a href="Console.md">控制台</a>
</tab>
<tab title="部署服务端">
自行部署 .NET 项目 ArcadeLink.Api, ArcadeLink.Web 即可.

正在重构基于 .NET Aspire 框架的 ArcadeLink.Cloud, 可自动记录各个请求，配置数据源等.
</tab>
</tabs>
