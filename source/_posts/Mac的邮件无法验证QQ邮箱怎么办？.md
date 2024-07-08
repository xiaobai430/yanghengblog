---
title: Mac的邮件无法验证QQ邮箱怎么办？
date: 2024-07-08 11:38:55
tags:
---

原文地址：https://zhuanlan.zhihu.com/p/558953563

一、配置教程

1、打开Mac中的“邮件”软件。

2、选择QQ邮箱选项。

3、输入邮箱地址和密码，发现“无法验证账户或密码”的问题。

![img](https://pic3.zhimg.com/80/v2-b131d0cfc5aef6a6bb5c4a130790e81a_1440w.webp)

4、解决办法从此处开始。进入网页QQ邮箱，点击“设置”-“账户”，往下拉，启用POP3/SMTP服务和IMAP/SMTP服务。

![img](https://pic2.zhimg.com/80/v2-cd24e293e32bde7b96d11ad8a39b571d_1440w.webp)



5、弹出下图，按照要求，用自己绑定该QQ邮箱的手机号码向指定号码发送内容为“配置邮件客户端”的短信，发送短信后，点击“我已发送“。

![img](https://pic4.zhimg.com/80/v2-90098e970636a50538ca510fa3956303_1440w.webp)



6、页面会出现一串密码，然后返回Mac的“邮件”软件，该串密码输入，**注意密码不是自己邮箱的密码。**

<font color="red">不是自己的邮箱密码，是授权码</font>

![img](https://pic3.zhimg.com/80/v2-fb59c532180335db01bfe8f42d957676_1440w.webp)



7、选择后即可进入邮箱页面，绑定成功，

![img](https://pic4.zhimg.com/80/v2-12ba63248a51a3082be2c08684743447_1440w.webp)



二、相关理论

邮件中比较相关的协议主要包括POP3（Post Office Protocol 3）、SMTP（Simple Mail Transfer Protocol）和IMAP（Internet Mail Access Protocol）三种。

POP3作用：从接收方服务器上把邮件存储到本地主机；

SMTP作用：用户邮件传到发送方邮件服务器，且可以将发送邮件传输到指定的接收方邮件服务器；

IMAP作用：发送端与接收端服务器交互，如常见删除邮件，标记已读、收信状态等功能都用IMAP协助完成；

