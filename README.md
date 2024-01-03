# srv00-vless

在 Serv00 免费托管网站上部署 vless 节点

## 部署教程

待更新

    Serv00.com是一家提供免费虚拟主机服务的网站，用户可以免费申请一个虚拟主机，享受无限流量，支持PHP,Ruby,Python,NodeJS等多种编程语言和SSH登录。下面，我们将更加详细地介绍Serv00.com的特点和申请及使用方法。


![](https://img.baxx.eu.org/202304142337704.png)
特点 
免费 
    Serv00.com提供免费虚拟主机服务，用户可以免费申请一个虚拟主机，享受无限流量和多种编程语言支持。 

无限流量
    Serv00.com提供无限流量，用户可以不用担心流量超标的问题。 

多种编程语言支持
    Serv00.com支持多种编程语言，包括Python、Node.js、Java等，用户可以根据自己的需求选择合适的编程语言进行开发。 

SSH登录
    Serv00.com支持SSH登录，用户可以使用命令行进行操作，更加灵活方便。 

使用方法
注册和申请虚拟主机 
    在Serv00.com上注册和申请虚拟主机非常简单，只需要按照以下步骤进行： 

1.打开Serv00官网 https://www.serv00.com/ ，点击“Register”按钮进入注册页面。 

2.填写所需信息，其中“What is the cost of hosting on serv00.com?”一栏需要填写0。 

3.点击“Register”按钮完成注册。 

4.登录账号后，点击“Create New Account”按钮申请一个新的虚拟主机。 

SSH登录
    在申请虚拟主机后，用户可以使用SSH登录虚拟主机进行操作。以下是使用SSH登录的步骤： 

1.打开终端，输入以下命令登录虚拟主机： 

```ssh username@server_address -p port_number```

    其中，username是你在Serv00.com上注册的用户名，server_address是虚拟主机的地址，port_number是SSH端口号。

2.输入密码登录虚拟主机。

定时任务
    为了避免账号被清除，需要每3个月登录一次SSH或控制面板。为了方便，可以设置定时任务来实现自动登录。以下是设置定时任务的步骤：

1.编辑定时任务：

```crontab -e```

2.在打开的文件中添加以下内容：

```0 0 1 */3 * ssh username@server_address -p port_number```

    其中，username是你在Serv00.com上注册的用户名，server_address是虚拟主机的地址，port_number是SSH端口号。

## 免责声明

* 本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
* 使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责.

## 赞助

爱发电：https://afdian.net/a/Misaka-blog

![afdian-MisakaNo の 小破站](https://user-images.githubusercontent.com/122191366/211533469-351009fb-9ae8-4601-992a-abbf54665b68.jpg)
