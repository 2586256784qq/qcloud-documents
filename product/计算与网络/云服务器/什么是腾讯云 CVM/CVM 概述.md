## 简介
腾讯云云服务器 (CVM) 在云中提供可扩展的计算容量，避免了使用传统服务器时需要预估资源用量及前期投入的情况。通过使用腾讯云 CVM ，您可以在短时间内快速启动任意数量的云服务器并即时部署应用程序。腾讯云 CVM 支持用户自定义一切资源：CPU、内存、硬盘、网络、安全等等，并可在访问量和负载等需求发生变化时轻松地调整它们。

## 相关概念
了解腾讯云 CVM 时，通常会涉及到以下概念：

- 云上的虚拟计算资源，也即[实例](/doc/product/213/4939)。
- 实例和其他资源的启动位置，也即[地域和可用区](/doc/product/213/6091)。
- 实例预置模版，包含服务器的预配置环境（操作系统和其他已安装的软件），也即[镜像](/doc/product/213/4940)。
- 实例的不同配置： CPU、内存、存储和网络等，也即[实例类型](/doc/product/213/4833)。
- 与实例处于同一台物理服务器上的，可被实例用作持久存储的设备，也即[本地盘](/doc/product/213/5798)。
- 提供的分布式持久块存储设备，可以用作实例的系统盘或可扩展数据盘使用，也即[云硬盘](/doc/product/213/4953)。
- 使用安全性高的 [SSH 密钥对](/doc/product/213/6092)登录方式（腾讯云存储公有密钥，用户在安全位置存储私有密钥）和使用普通密码的[登录密码](/doc/product/213/6093)登录方式。
- 实例对内和对外的服务地址，也即[内网 IP 地址](/doc/product/213/5225)和[公网 IP 地址](/doc/product/213/5224)。
- 对实例进行安全的访问控制，指定进出实例的IP、协议及端口规则，也即[安全组](/doc/product/213/5221)。
- 自定义的虚拟网络空间，与其他资源逻辑隔离，也即[私有网络](/doc/product/215/4927)。
- 专为动态网络设计的静态公网 IP，满足快速排障需求，也即[弹性 IP](/doc/product/213/5733)。
- 实例内部标识实例资源的标签，也即[元数据](/doc/product/213/4934)。
- 基于 Web 的用户界面，也即[腾讯云控制台](https://console.qcloud.com/)。


如果这是您第一次开始使用腾讯云云服务器，可以参考 [快速入门 Windows 云服务器](/doc/product/213/2764) 和 [快速入门 Linux 云服务器](/doc/product/213/2936)。


## 相关服务

- 您可以使用一个预设模版来启动新的云服务器。预设模版可以包含任何您希望在初始化时就包含在云服务器中的环境或应用程序。腾讯云提供大量经审核的第三方预设模版，帮助用户快速搭建环境。有关更多信息，可以参考[服务市场](http://market.qcloud.com/)。

- 可使用负载均衡横跨多个云服务器实例自动分配来自客户端的请求流量。有关更多信息，请参阅 [负载均衡产品文档](https://www.qcloud.com/doc/product/214)。

- 可以使用弹性伸缩定时或根据条件地自动增加及减少服务器集群数量。有关更多信息，请参阅 [弹性伸缩产品文档](https://www.qcloud.com/doc/product/377)。

- 要监控云服务器实例的运行统计数据，可使用云监控。有关更多信息，请参阅 [云监控产品文档](https://www.qcloud.com/doc/product/248)。

- 在云上部署您的关系数据库，可以使用腾讯云云数据库。有关更多信息，请参阅相应的云数据库产品文档，如：[云数据库MySQL](https://www.qcloud.com/doc/product/236)。

## 使用 CVM

腾讯云 CVM 提供基于 Web 的用户界面，即控制台，如果您已注册腾讯云账户，您可以直接 [登录 CVM 控制台](https://console.qcloud.com/cvm)，对您的 CVM 进行操作。

腾讯云 CVM 提供 API 接口，这些请求属于 HTTP 或 HTTPS 请求，有关 CVM API 操作的更多信息，请参阅 [API 文档](https://www.qcloud.com/document/api/213/568)。

如果您倾向于使用 API 的方式对您的资源、应用和数据进行管理操作，您可以使用 SDK（支持 PHP/Python/Java/.NET/Node.js）编程或使用腾讯云命令行工具调用 CVM API，具体请参考：
- [使用 SDK >>](https://www.qcloud.com/document/developer-resource)
- [使用命令行工具 >>](https://www.qcloud.com/document/product/440/6317)

## 定价

有关云服务器的收费模式和具体价格，请参阅[云服务器实例价格](https://www.qcloud.com/doc/product/213/2176)。

