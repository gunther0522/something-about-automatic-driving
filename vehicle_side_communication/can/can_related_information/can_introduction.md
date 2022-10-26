# 1. CAN总线简介

CAN(Controller Area Network)控制器域网的简称，是ISO国际标准化的串行通信协议，旨在==允许微控制器和设备在没有主机的情况下相互通信==。它是一个==基于消息的协议==。对于每个设备来说帧中的数据按照顺序传输的，如果多个设备同时传输，最高优先级的设备可以继续，而其他设备退后，帧由所有设备(包括发送设备)接收。<sup>1</sup>

ISO11898体系结构定义七层，OSI模型最低两层作为数据链路层和物理层

## CAN总线特点

CAN总线具有以下优势：

# 参考文章

[1] [维基百科-CAN总线](https://encyclopedia.thefreedictionary.com/Controller+Area+Network)