### HFish架构

HFish采用B/S架构，系统由管理端和节点端组成，管理端用来生成和管理节点端，并接收、分析和展示节点端回传的数据，节点端接受管理端的控制并负责构建蜜罐服务。

在HFish中，**管理端**只用于**数据的分析和展示**，**节点端**进行**虚拟蜜罐**，最后由**蜜罐来承受攻击**。

<img src="/images/image-20210902163914134.png" alt="image-20210902163914134" style="zoom:50%;" />



### HFish特点

HFish当前具备如下几个特点：

- 安全可靠：主打低中交互蜜罐，简单有效；

- 功能丰富：支持基本网络 服务、OA系统、CRM系统、NAS存储系统、Web服务器、运维平台、无线AP、交换机/路由器、邮件系统、IoT设备等40多种蜜罐服务，支持用户制作自定义Web蜜罐，支持用户进行流量牵引到云蜜网、可开关的扫描感知能力、支持可自定义的蜜饵配置；

- 开放透明：支持对接微步在线X社区API、五路syslog输出、支持邮件、钉钉、企业微信、飞书、自定义WebHook告警输出；

- 快捷管理：支持单个安装包批量部署，支持批量修改端口和服务；

- 跨平台：支持Linux x32/x64/ARM、Windows x32/x64平台、国产操作系统、龙芯、海光、飞腾、鲲鹏、腾云、兆芯硬件



### HFish典型应用场景

![image-20211102125302898](/images/202111021253175.png)

![image-20211102125324125](/images/202111021253180.png)
