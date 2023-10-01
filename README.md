# PanguHA

#### 介绍
PanguHA是Windows平台的双机集群系统，是提供系统高可用性的解决方案，一般由两个节点构成，分为活动节点及备用节点。


#### 功能介绍

### 1. IP漂移
对外提供一个集群IP,并且该IP始终只会设置在活动主机上，当一台节点宕机，
该IP会自动漂移到未宕机的节点上，备用节点升级为活动节点，系统站点和数据库的IP可以设置为集群IP,
用于提高系统可用性，对业务无感知。
![1695042278763](https://github.com/s899000/PanguHA/assets/33239560/1a0f5184-b348-462b-a08f-ad07bf686f19)


### 2. 执行管理 
可用于设置进程和windows服务组，并且保证进程和windows服务只会在一台节点上运行(活动节点)。
![1695042578069](https://github.com/s899000/PanguHA/assets/33239560/75f73f38-f727-4a67-8647-0297effb3be1)


### 3. 文件同步
利用NFS共享文件，可以同步两个服务器某个路径下的文件，采用镜像复制，主节点向备节点推送差异文件， 备节点始终和主节点保持相同，
同时可以设置过滤条件忽略文件夹或者固定名称或后缀的文件
![文件同步](https://github.com/s899000/PanguHA/assets/33239560/4f216fbf-9bac-4ad7-afe1-a8f19305d002)

### 4. Mariadb/Mysql双主复制一键部署



### 5.操作说明
https://blog.csdn.net/sss899000/article/details/132921678?spm=1001.2014.3001.5502
![Mysql双主](https://github.com/s899000/PanguHA/assets/33239560/a54f713d-d8bb-4bf5-8262-8d14f13d5a42)



### 6. 联系方式

![1694855799819](https://github.com/s899000/PanguHA/assets/33239560/497507eb-0b23-4bbf-bd43-4e553b727496)

邮箱 435031783@qq.com





