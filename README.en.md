# PanguHA

#### Description
PanguHA is a dual machine cluster system on the Windows platform, providing a high availability solution for the system. It is generally composed of two nodes, divided into active and standby nodes.

#### Instructions

### 1.  IP drift
Provide a cluster IP externally, and this IP will always be set only on the active host. When a node goes down, this IP will automatically drift to the node that has not gone down. The backup node will be upgraded to the active node, and the IP of the system site and database can be set as the cluster IP to improve system availability without being aware of business.
![1695042278763](https://github.com/s899000/PanguHA/assets/33239560/3bf53b17-23cd-4732-b720-adaede5ab473)



### 2.  Execution Management
It can be used to set up processes and Windows service groups, and ensure that processes and Windows services only run on one node (active node).
![1695042578069](https://github.com/s899000/PanguHA/assets/33239560/e5d75c14-b425-41e3-8e57-cfd1d2917ece)


### 3.  File synchronization
By using NFS shared files, it is possible to synchronize files on a certain path between two servers, using mirror replication. The primary node pushes differential files to the backup node, and the backup node always remains the same as the primary node. At the same time, filter conditions can be set to ignore folders or files with fixed names or suffixes
![文件同步](https://github.com/s899000/PanguHA/assets/33239560/869c8768-3f51-4e4e-8287-b3fb6595f270)


### 4.  Mariadb/Mysql dual master replication one click deployment
![Mysql双主](https://github.com/s899000/PanguHA/assets/33239560/f66151fe-150b-43e4-9dd5-64cf5b31e34d)



### 5.  Operating instructions
https://blog.csdn.net/sss899000/article/details/132921678?spm=1001.2014.3001.5502

### 6.  Contact information

![1694855799819](https://github.com/s899000/PanguHA/assets/33239560/8ae631b2-ca08-41f6-9521-60c4c82943d6)

Email 435031783@qq.com



