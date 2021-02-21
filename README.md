win10home 天池docker练习场
===============
# 一、安装docker工具
>>本文主要以win10家庭版为例记录在安装过程中遇到的问题，在win10上安装docker主要分为以下几个步骤：
* 1、Hyper-V安装
* 2、本地安装WLS2环境
* 3、安装docker desktop for windows
>>具体实现步骤可以参照 https://zhuanlan.zhihu.com/p/351208803 ,严格按照步骤可以在win10上顺利安装docker desktop。
# 二、配置Docker Desktop
* 根据官网中的说明基于wls2的docker无法直接在advanced中设置镜像的存储位置，因此需要在命令行中打包并删除c盘镜像，然后在d盘重新创建，具体实现命令可参考https://blog.csdn.net/shanghaibao123/article/details/112968528
* 在docker engine中的json编辑框内可以输入镜像加速器地址
# 三、开通容器镜像服务
根据官方教程一步一步执行即可 https://tianchi.aliyun.com/forum/postDetail?&postId=165595
# 四、提交结果截图
![](http://www.baidu.com/img/bdlogo.gif)
