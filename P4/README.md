# P4

## 理论

## 实验

### 0.预备知识

描述实验相关背景以及支撑

### 1.基于IPv4数据包的转发

P4交换机实现IPv4数据报的基本转发，即查找路由表进行转发，具体操作包括更新报文的源、目的MAC地址、更改IP首部的TTL字段，以及将数据报转发至某一端口。

### 2.基于隧道的转发

本实验中在IP首部和以太网首部之间增加一个新的Tunnel首部以实现隧道的功能。数据包的转发不再根据目的IP地址，而是隧道首部。

### 3.INT实验

本实验实现INT（带内遥测），在数据包进行IPv4转发时，将路径上经过的交换机以及对应的端口队列长度作为遥测信息假如到数据包中。


