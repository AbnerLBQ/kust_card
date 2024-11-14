# kust_card
create a code for Kust punch data





#### 描述

给昆工怡园的学生写的一个简单打卡的程序，参考相关资料，用go构建，很简单。

#### 使用方法



1 将本项目fork到自己的仓库中



2 到自己的fork仓库页面

![image-20240925205514846](README/image-20240925205514846-1727276619575.png)

3点击setting



4找到左侧的environment 

![image-20240925201858500](README/image-20240925201858500-1727276619576.png)

![image-20240925201918752](README/image-20240925201918752-1727276619577.png)

5点击 new environment

6输入CONFIG_01

![image-20240925201943703](README/image-20240925201943703-1727276619577.png)

并点击确认 



然后点进去 向下翻页



![image-20240925202021580](README/image-20240925202021580-1727276619577.png)

找到add environment





然后输入三个变量即可



>username ： 自己的我在校园账号
>
>password  ： 对应的密码
>
>tencent_key : 腾讯api的 秘钥 这里后面会提到。

设置好之后是这个样子



![image-20240925202205636](README/image-20240925202205636-1727276619577.png)

之后 点击上方的action



![image-20240925202420941](README/image-20240925202420941-1727276619577.png)

进入页面后点击左侧的 new workflow

![image-20240925202451154](README/image-20240925202451154-1727276619577.png)

然后点击 “我在校园打卡"



![image-20240925202509647](README/image-20240925202509647-1727276619578.png)

点击run workflow 

![image-20240925202551916](README/image-20240925202551916-1727276619578.png)

点击这个查看情况

![image-20240925202629247](README/image-20240925202629247-1727276619578.png)

![image-20240925202657985](README/image-20240925202657985-1727276619578.png)

![image-20240925202705713](README/image-20240925202705713-1727276619578.png)

如若没有报错则正常 ，等待自动打卡即可





接下来说一下这个秘钥



点击这个秘钥 

[腾讯api](https://lbs.qq.com/)

登录之后进入控制台

![image-20240925203335106](README/image-20240925203335106-1727276619578.png)

点击左侧的我的应用 创建应用 

![image-20240925203352800](README/image-20240925203352800-1727276619578.png)

随便填



创建好之后就有一个秘钥了



我们进入左侧的配额管理

![image-20240925204028371](README/image-20240925204028371-1727276619578.png)

然后给对应的接口分配配额即可



![image-20240925203549763](README/image-20240925203549763-1727276619578.png)

这两个接口





至此全部完成，如果能帮到你的话，欢迎star。

by the way 
#### 免责声明

此项目由个人/团队开发并维护，提供的代码仅供学习、参考与实验用途。项目不对任何因使用此代码或本项目相关内容引发的损失、故障或其他后果负责。请自行评估并使用该代码。

使用本项目前，请确保您了解并遵守当地法律和适用的使用规定。

本项目采用 [MIT 许可证](LICENSE)（或其他许可证类型），请参阅相关许可协议以了解详细的使用条款。