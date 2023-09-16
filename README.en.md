# PanguHA

#### Description
PanguHA is a dual machine cluster system on the Windows platform, providing a high availability solution for the system. It is generally composed of two nodes, divided into active and standby nodes.

#### Instructions

### 1.  IP drift
Provide a cluster IP externally, and this IP will always be set only on the active host. When a node goes down, this IP will automatically drift to the node that has not gone down. The backup node will be upgraded to the active node, and the IP of the system site and database can be set as the cluster IP to improve system availability without being aware of business.
![1694848438588](https://github.com/s899000/PanguHA/assets/33239560/6ec696ec-4901-4a3c-a126-a207e0c0a972)


### 2.  Execution Management
It can be used to set up processes and Windows service groups, and ensure that processes and Windows services only run on one node (active node).
![1694848255972](https://github.com/s899000/PanguHA/assets/33239560/a0f7efbb-c94f-4dfa-af9a-1c0de08286d3)

### 3.  Resource mirroring (under development)


### 4.  Contact information

![1694855799819](https://github.com/s899000/PanguHA/assets/33239560/8ae631b2-ca08-41f6-9521-60c4c82943d6)

email 435031783@qq.com



